# Quill — Littlebird content pipeline (Claude Code instructions)

**SCOPE: this repo is content GENERATION ONLY.** No Webflow access, no CMS, no publishing, no deploys. Quill produces page copy as Markdown files on disk. Loading copy into a CMS and publishing happen elsewhere, by a human. Never assume network/CMS tools are available here; if asked to "publish," explain that this repo only generates `output/<slug>/final.md`.

## What this is
A five-stage, prompt-driven pipeline that turns a page brief into a fact-checked Littlebird SEO/AEO landing page (a top-level integration "spoke" or a single-capability "sub-spoke"). Each stage is a role prompt in `prompts/`. The **Bible** (`bible/littlebird-bible-v3.md`) is the only source of product facts.

## Run the stages IN ORDER, 1 -> 5
For a page named `<slug>` (matches a brief at `briefs/<slug>.md`):

1. **Orchestrator** (`prompts/1-orchestrator.md`) -> writes `output/<slug>/outline.md` — skeleton + fact map (with Bible section numbers) + a GATED-claims list. No prose.
2. **Writer** (`prompts/2-writer.md`) -> writes `output/<slug>/draft.md` — full page copy from the outline.
3. **Reviewer** (`prompts/3-reviewer.md`) -> writes `output/<slug>/review.md` — voice/Hard-Don't fixes, verdict PASS/REVISE. Apply required fixes to the draft.
4. **Fact-checker** (`prompts/4-factchecker.md`) -> writes `output/<slug>/factcheck.md` — per-claim PASS/FLAG table, overall PASS/FAIL. Resolve every FLAG before proceeding.
5. **Grader** (`prompts/5-grader.md`) -> writes `output/<slug>/grade.md` — blind rubric grade. Grade independently (do not read the page's own review/qa).

The finished page is **`output/<slug>/final.md`** (promote the passing, fact-checked draft to `final.md`). Read each stage prompt in full before running it — the prompts are the authoritative spec; the rules below are the summary.

## Non-negotiable rules
- **Bible is the only source of facts.** Every factual sentence must trace to a section of `bible/littlebird-bible-v3.md`. If a claim is not in the Bible, do not write it. Never invent or inflate a capability beyond what the Bible verifies.
- **Gating / `[GATED]`.** Any claim marked TODO / NEEDS-VERIFICATION / PENDING ENG SIGN-OFF in the Bible, or not present at all, is **never asserted as fact**. Write around it, or mark `[GATED: needs eng sign-off]`. See `prompts/GATING-POLICY.md`: Tier 1 claims are hard-gated; Tier 2 integration capabilities that are telemetry-backed/product-plausible may be written clean but noted in the QA report. An ungated gated-claim is a fact-check FAIL.
- **Composed claims** (combining two individually-verified capabilities, e.g. read a Plaud transcript -> create a Notion page) are allowed only if EVERY leg is verified in the Bible.

## Voice (v3 register — Bible Section 3 / 3.1)
- **Contractions are house style** (it's, you're, what's, don't).
- **Ambient-capture thesis is the spine:** the tool only knows what someone typed into it; Littlebird already saw the work happen, because it reads your screen and transcribes meetings. Lead with a concrete failure scene, then the capture turn, then one plain connect line. **Never open with a feature.**
- **Capability lines:** "Littlebird can [verb]…, so [the concrete moment it matters]." Anchor to a real moment/capture source. Never a flat list where every line is "Littlebird can X without opening Y" (the "Linear disease").
- **Punctuation: ASCII only.** No Unicode em dashes, en dashes, or smart quotes. Use `--` as the em-dash stand-in and straight quotes.
- **Banned words:** seamless, effortless, streamline, game-changer (plus the rest of the Bible Section 15 Hard Don'ts).

## H1 formula
- **Sub-spoke (single capability, the keyword play):** instructional, SEO-literal, Title Case — **"How to [X] with Littlebird's [Tool] Integration"** (or the variant **"How to [X] in [Tool] with Littlebird"** when the verb-object reads better). Must contain the tool name + plain verb-object + "Littlebird". The clever two-beat line does NOT go in the H1 — it becomes the **first line of the intro**.
- **Top-level spoke:** the v3 two-beat verb-led headline (a setup and a payoff), e.g. "Trace the bug, draft the PR, write your own standup." Never the older "Your X is Y. Doing Z should not interrupt you." form.

## Standard page structure
Intro (failure scene -> capture turn -> connect line; sub-spoke intro's first line is the two-beat hook) -> **answer-first question** heading -> capabilities (anchor capability first, then related ones that link up to the parent spoke) -> mini-FAQ (2 Qs) -> **Connect [Tool]** CTA. Sub-spokes are ~500-800 words and MUST link to their parent spoke page.

## Reference material (not facts — conventions)
- `reference/subspoke-titles-v4.md` — approved title conventions / anchor-capability mapping.
- `reference/subspoke-voice-spec.md` — field-level voice spec + exemplars (follow the v3 contraction register over any older no-contraction exemplars).
- `reference/subspoke-angle-map.md` — anti-duplication angle map, so sibling pages don't cannibalize each other.

## Output & git
- Generated work goes under `output/<slug>/` and is gitignored (only `output/.gitkeep` is tracked). Commit prompts, bible, reference, briefs, and docs — not drafts.
