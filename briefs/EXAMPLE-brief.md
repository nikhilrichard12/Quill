# Brief: EXAMPLE (copy this file to briefs/<slug>.md and fill in)

The orchestrator (stage 1) reads this brief plus the Bible. Keep it short — it's a
pointer to intent and the Bible facts, not the copy itself. Delete these notes when you fill it in.

- **slug:** example-slug
  URL-style name; the pipeline writes to `output/<slug>/`. For sub-spokes, match the
  convention in `reference/subspoke-titles-v4.md` (e.g. `github-code-search`).

- **page type:** sub-spoke
  `spoke` = a top-level integration page (two-beat verb-led H1).
  `sub-spoke` = one capability, one plain search query (instructional SEO-literal H1).

- **tool / integration:** <Tool name exactly as it appears in the Bible, Section 9>
  The tool must have a verified entry in the Bible. Only its listed capabilities may be used.

- **anchor capability:** <the ONE capability this page is built around>
  Must be a capability verified in the Bible for this tool. For a sub-spoke this is the
  single hero capability; 2-3 related verified capabilities may support it and link up to
  the parent spoke.

- **target search query / intent:** <the plain query a real user would type>
  e.g. "search a codebase with ai". Drives the H1 and the answer-first question heading.

- **parent spoke page:** /integrations/<tool>
  (sub-spokes only) the page this sub-spoke must link up to.

- **opening failure scene (optional hint):** <the concrete moment the page opens inside>
  A real artifact/moment — the client email, the Slack thread, the bug on screen. The writer
  turns this into the intro's failure scene before the ambient-capture turn.

- **notes / gated watch-list (optional):** anything you already know is NOT in the Bible or is
  PENDING ENG SIGN-OFF, so the writer gates it. The orchestrator will also derive this itself.
