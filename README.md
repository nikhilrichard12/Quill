# Quill

Quill is a multi-stage content pipeline for generating Littlebird SEO/AEO landing pages — the integration "spoke" pages and the single-capability "sub-spoke" pages. It's **prompt-driven**: each stage is a role prompt that Claude Code runs in order, grounded in a single source of product facts (the Bible). The output is clean Markdown page copy.

**Content generation only.** Quill has no Webflow/CMS access and does not publish anything. It writes `output/<slug>/final.md`; loading and publishing happen separately.

## Prerequisites
- [Claude Code](https://claude.com/claude-code) installed and working.
- That's it. No Node, no build step, no API keys: the pipeline is prompts + Markdown.

## Repository layout
```
prompts/     1..5 stage prompts + GATING-POLICY.md (the pipeline spec)
bible/       littlebird-bible-v3.md  (the ONLY source of product facts)
reference/   title conventions, voice spec, anti-duplication angle map
briefs/      one brief per page you want to generate (see EXAMPLE-brief.md)
output/      generated pages land in output/<slug>/ (gitignored)
CLAUDE.md    standing instructions Claude Code auto-reads
```

## Generate one page, start to finish
1. Write a brief at `briefs/<slug>.md`. Copy `briefs/EXAMPLE-brief.md` and fill in the tool, page type (spoke or sub-spoke), the anchor capability, and the target search query. `<slug>` is the page's URL-style name, e.g. `github-code-search`.
2. Open Claude Code in this repo and run the stages in order — for example:
   - "Run stage 1 (orchestrator) for `github-code-search`." -> produces `output/github-code-search/outline.md`
   - "Run stage 2 (writer)." -> `draft.md`
   - "Run stage 3 (reviewer)," then apply the required fixes.
   - "Run stage 4 (fact-checker)." -> resolve every FLAG. This is the anti-hallucination gate.
   - "Run stage 5 (grader)." -> an independent letter grade.
3. When the draft passes fact-check and reads at an A, promote it to `output/<slug>/final.md`. That's the deliverable.

Claude Code reads `CLAUDE.md` automatically, so the voice, gating, H1 formula, and structure rules are enforced without you restating them. Every factual claim must trace to the Bible; anything unverifiable is marked `[GATED]` and never shipped as fact.

## Add new titles
Follow the conventions in `reference/subspoke-titles-v4.md` (H1 formula, one anchor capability per page, plain search-query slugs). Check `reference/subspoke-angle-map.md` first so a new page doesn't cannibalize an existing one, then write its brief in `briefs/`.

## Contributing
Keep it simple: branch off `main`, add your briefs/pages, open a PR. Don't commit generated drafts (they're gitignored) — commit prompts, briefs, and reference/Bible changes.
