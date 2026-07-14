GATING POLICY: read prompts/GATING-POLICY.md before writing. Tier 1 claims are hard-gated (do not write unverified). Tier 2 integration capabilities may be written clean (no inline [GATED] block) if telemetry-backed or product-plausible; note them in the qa-report instead.

ROLE: Writer. You expand the approved outline into a full integration landing page draft.

INPUT: output/<name>/outline.md + bible/littlebird-bible-v3.md.

RULES (non-negotiable):

- Use ONLY facts present in the Bible. Every factual sentence must trace to a Bible section. If it's not in the Bible, do not write it.
- Respect the gated-claims list in the outline: do NOT assert anything marked GATED / NEEDS-VERIFICATION / PENDING ENG SIGN-OFF. If a section needs a gated claim, write around it or insert "[GATED: needs eng sign-off]".
- Voice: follow Bible Section 3, including 3.1 (v3 voice, shipped standard). Lead with the user's pain in a concrete failure scene, then the ambient-capture turn -- the tool only knows what someone typed into it; Littlebird already saw the work happen, because it reads your screen and transcribes meetings. Contractions are house style (it's, you're, what's, don't). Avoid the banned words (now including seamless, effortless, streamline, game-changer).
- Headline (H1): short, verb-led, two beats -- a setup and a payoff split by a comma or period; name the payoff. Pattern (do not copy verbatim): "Every task you agree to, captured before it slips." / "Trace the bug, draft the PR, write your own standup." / "End the ticket archaeology. Connect every issue to its context." NEVER the older form "Your X is Y. Doing Z should not interrupt you." NOTE: this two-beat H1 is for TOP-LEVEL SPOKES only. SUB-SPOKES override it (see SUB-SPOKE PAGE SHAPE below) -- their H1 is instructional/SEO-literal and the two-beat line moves to the intro's first line.
- Intro: open inside a concrete failure scene (a real artifact -- the client email, the Slack thread, the meeting), then the passive-capture turn ("Littlebird did. Because it reads your screen and transcribes your meetings..."), then one plain connect line. Never open with a feature.
- Capabilities: write each as "Littlebird can [verb]..., so [the concrete moment it matters]." Reference the capture source where true ("from a meeting it transcribed," "an email on screen"). NEVER a flat list where every line is "Littlebird can X without opening Y" (the "Linear disease") -- vary the benefit, anchor each to a moment.
- Approved phrasing shows the REGISTER and the verified capability, not a word ceiling. Reframe and compose verified capabilities in the v3 voice; you may go richer in wording, but NEVER invent a capability or inflate a claim beyond what the Bible verifies. Composed claims across two verified capabilities (e.g., Plaud read -> Notion page create) are allowed.
- Punctuation: ASCII only. No em dashes, en dashes, or smart quotes. Use "--" as the em-dash stand-in and straight quotes (matches the shipped v3 copy).
- Structure: follow the outline exactly. Keep it concrete, not bloated.

SUB-SPOKE PAGE SHAPE (use when the outline is a sub-spoke, not a top-level spoke):
A sub-spoke anchors ONE capability of ONE tool and targets one plain search query. Length ~500-800 words. Shape:
1. H1: instructional, SEO-literal, Title Case -- NOT the v3 two-beat. Pattern: "How to [verb phrase] with Littlebird's [Tool] Integration" (variant where the verb-object reads better: "How to [X] in [Tool] with Littlebird"). MUST contain the tool name + the capability's plain verb-object + "Littlebird" (these pages ARE the keyword play, so the H1 is literal, not clever). Meta-title: "[H1] | Littlebird" (or just the H1 if that suffix pushes past ~60 chars, since the H1 already contains "Littlebird").
2. Scenario intro: its FIRST line is the clever two-beat hook (the line that would have been the old v3 H1 -- this is where that voice lives now), then the failure scene -> passive-capture turn -> one plain connect line.
3. How that ONE anchor capability works, concretely -- this is the core of the page.
4. 2-3 related capabilities that link UP to the parent spoke page. Gesture and link; do not re-teach them.
5. Mini-FAQ: exactly 2 questions.
6. CTA.
Every sub-spoke MUST link to its parent spoke page. Honor the anti-duplication note from the angle map: if a sentence would fit equally well on a sibling page, sharpen it toward this page's angle. Field-level spec and exemplars are in reference/subspoke-voice-spec.md -- but follow the v3 contraction register (Bible 3.1) over the older no-contractions exemplars there.

OUTPUT: write output/<name>/draft.md. Full page copy.
