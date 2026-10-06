The Littlebird Bible (v3.5)
Single source of truth for the SEO and AEO content pipeline. Writer subagents draft pages from this. The editor subagent enforces voice and rejects hallucinations using this. A human approves from a queue. Treat every fact here as the only authoritative version. If a claim is not in this bible, it cannot go on a page.

Status: v3.5, updated October 5, 2026 (founder Reddit and Discord pass with carry-forward: public answers from u/Littlebird_Alex (Littlebird company account) on Reddit, 2026-09-23 to 2026-09-25, and by Alex and Tushar on Discord, 2026-09-24 to 2026-10-04, folded in as FOUNDER-STATED facts, plus the 50 founder-sourced changes from Magpie's closed Quill PRs #2, #4, and #5 (Alex's July 2026 AMA and July to August Reddit answers; Alex's and Tushar's Discord answers, May to September 2026; Tushar's 2026-09-13 Discord answers) re-integrated against v3.4, each cited inline with its date; assembled by Magpie -- see the changelog below) from v3.4, updated September 20, 2026 (changelog and founder Discord pass: six entries of Littlebird's public changelog, docs.littlebird.ai/changelog, dated 2026-07-24 to 2026-08-28, folded in as DOCS-VERIFIED facts, plus public Discord answers by Tushar of 2026-09-14 to 2026-09-17 as FOUNDER-STATED facts, each cited inline with its date; assembled by Magpie -- see the changelog below) from v3.3, updated August 30, 2026 (founder Reddit pass: public Reddit answers by Tushar folded in as FOUNDER-STATED facts, cited inline with dates; assembled by Magpie and delivered for review as Quill PR #1) from v3.2, updated July 30, 2026 (Power tier confirmed on the live pricing page) from v3.1 (July 27, 2026, docs-site reconciliation) from v3 (built June 23, 2026, from Bible v2 plus the ingested source library: Content Style Guide, Brand Guidelines, Positioning and Messaging, Marketing Personas, Day-in-the-life Use Cases, Stats and Metrics, Launch Tiers, Competitive Tracker, the six live comparison pages, Customer Quotes, Discord). Founder and Viktor confirmations noted inline. Open items are marked TODO or NEEDS-VERIFICATION.

Provenance tiers. PRODUCT-VERIFIED (first-hand app-tested by product) > DOCS-VERIFIED (confirmed on Littlebird's official support documentation, support.littlebird.ai/docs, blessed by Shahzad -- a second-party published source, stronger than telemetry, not first-hand product-tested) > FOUNDER-STATED (defined below) > TELEMETRY-VERIFIED (usage telemetry, Tier 2) > NEEDS-VERIFICATION (do not publish). A DOCS-VERIFIED fact is publishable unless a Hard Don't (section 15) says otherwise. The public changelog at docs.littlebird.ai/changelog (added v3.4) is a DOCS-VERIFIED source: Littlebird publishing what shipped, dated, in its own words. Cite it as DOCS-VERIFIED (docs.littlebird.ai/changelog, entry date). A changelog entry is a floor on what shipped on its date, not a ceiling and not proof a feature is still live; it rarely states plan gating, so it does not clear a NEEDS-VERIFICATION on tier availability unless it names the plan in words. Where a changelog entry and a FOUNDER-STATED line conflict, the changelog governs. FOUNDER-STATED (added v3.3): a founder's dated public statement -- a Reddit or Discord answer, an AMA reply -- cited with a permalink and a date (on the Littlebird Discord, Tushar posts as triptu). It ranks between DOCS-VERIFIED and TELEMETRY-VERIFIED. A FOUNDER-STATED fact belongs in this bible and is quotable in page copy with attribution. THE EXCEPTION IS CONTRACTUAL OR LEGAL claims: those still require founder or legal confirmation before they appear in page copy, however plainly a founder stated them in public. Separately, where a founder's wording is hedged ("should") or is a one-off description of a mechanic, product-confirm before building page copy on it. Account note (added v3.5, carried from the 2026-09-03 pass): u/Littlebird_Alex is the Littlebird company account. Alex answered the July 2026 r/littlebird AMA from it and confirmed on 2026-07-17 that u/Weak_Ad3685 is his personal account ("also just tbc this is Alex i was just on a personal account"); both count as Alex. From September 2026 other team members also post from the company account, so cite it as "u/Littlebird_Alex (Littlebird company account)" and treat its answers as official Littlebird statements unless the text names the author. u/YardLeast3268 is Tushar. Discord handles (added v3.5, carried from the 2026-09-12 pass): in the Littlebird Discord (littlebird.ai/discord) alexfgreen is Alex and triptu is Tushar. Discord answers are cited as "<founder> on Discord #<channel>, <date>" and carry the same FOUNDER-STATED weight as Reddit answers. They are often two or three words in reply to a message whose text the citation does not carry; where the question could not be recovered, the answer was not used.

CHANGELOG
v3.5 -- 2026-10-05 -- founder Reddit / Discord pass with carry-forward (Magpie). Source: public Reddit answers by u/Littlebird_Alex (Littlebird company account), 2026-09-23 to 2026-09-25, and public Discord answers by Tushar (triptu) and Alex (alexfgreen), 2026-09-24 to 2026-10-04, cited inline as FOUNDER-STATED; plus the changes Magpie proposed in Quill PRs #2 (2026-09-03: Alex's July 2026 AMA and his July to August Reddit answers), #4 (2026-09-12: Alex's and Tushar's Discord answers, May to September 2026, and one company-account Reddit answer), and #5 (2026-09-13: Tushar's Discord answers), all closed unmerged on 2026-09-22 and re-integrated here against v3.4 with the Hover rename applied and v3.4's DOCS-VERIFIED lines kept wherever they already cover the same fact; permalinks in the PR description. No new changelog entry since v3.4: docs.littlebird.ai/changelog still ends at 2026-08-28. This version was first assembled on 2026-09-27 and did not reach Quill main then (its PR could not be opened), so it lands here as assembled then, plus one addition from the week to 2026-10-05. Headlines: a font option under Settings > Appearance, per Tushar on 2026-10-04, control unconfirmed (6.1, Appendix A); text-to-speech is "already available for pro users" per the company account, the first plan statement on record for spoken output, surfaces unconfirmed (6.1, Appendix A); Routines do not yet support on-device integrations, per Tushar, roadmap (6.3, Appendix A); the Settings toggle for the collapsed sidebar promised on 2026-09-17 was released on 2026-09-24 (6.1, Appendix A); the retired Daily Journal can be recreated as a Routine from a prompt, confirmed again from the company account (6.3); the company account restated the positioning against ChatGPT and Claude on 2026-09-25 (7.5, 14.3); one unrecovered "we just changed the name" reply flagged (Appendix A). Carried headlines: the account note (u/Weak_Ad3685 is Alex) and the Discord handles (provenance note); data export and ownership, with the export-path flag (10.6, 10.11, 11); model-agnostic routing and "not a Claude wrapper" (new 4.9); the memory model, every past chat in the record (new 4.10); storage detail and the cloud rationale (10.3, 10.8); text-not-screenshots and the PII caveat (4.4); SOC 2 Type II and the HIPAA toggle (10.4); zero incidents stated with a date, gated (10.7); Quick, Default, and Max named, Ultra from the changelog, sources shown, any language, voice reported live (6.1); autonomy stance (new 7.8); founder framing for zero setup, the differentiator, and the privacy objection (7.3, 7.5, 10); usage as unit economics, metered by work (5.1); Routines from Discord, the retired journal and the founders' prompts (6.3); Hover Mac-only confirmed and in-meeting use (6.4); Meeting Notes confirmations (6.2); custom MCP click path, local MCP in beta, the MCP server's history, summaries outside the app (6.6); Assistant Notes guidance and the guardrail flag (6.6); Android capture history, iOS, the web app (4.5); no native task manager (9, 11); CRM category live and the Slack delay (9.10); beta program and the weekly changelog (14.3); founder capital (4.7); Obsidian and ChatGPT computer-history context (12); three Hard Don'ts (15); the Enterprise on-prem flag; the roadmap register rebuilt with Reddit and Discord dates (Appendix A). Base: v3.4 on Quill main (commit e668847).
v3.4 -- 2026-09-20 -- founder Discord / changelog pass (Magpie). Source: Littlebird's public changelog, docs.littlebird.ai/changelog, six entries dated 2026-07-24 to 2026-08-28, cited inline as DOCS-VERIFIED (docs.littlebird.ai/changelog, entry date); plus public Discord answers by Tushar (triptu), 2026-09-14 to 2026-09-17, cited inline as FOUNDER-STATED; permalinks in the PR description. Zero new Reddit items this week from u/Littlebird_Alex, u/Weak_Ad3685, or u/YardLeast3268. Headlines: Hummingbird is renamed to Hover (changelog 2026-08-28), applied in every place the old name appeared, and 6.4 gains the redesigned multi-conversation Hover (2026-08-14); Artifacts move from FOUNDER-STATED to DOCS-VERIFIED with the plan gate still NEEDS-VERIFICATION (6.6); Shared Projects and team analytics documented (6.6); multiple accounts per integration (9); App Mentions with @, including a one-off share of an excluded app (6.1, 4.8); usage notices at 70% and 90%, and Tushar's 2026-09-16 answer that Plus usage has not been lowered (5.1); Ultra mode named for Pro users (6.1); Meeting Notes email delivery, Send to attendees, automatic prep and recording (6.2); Routines created by asking, answered by email reply, and carrying the full report and any PDF in the email (6.3); Gmail send card, send from the phone, and readable attachments (9.1); adding a third-party MCP server by URL is now docs-verified, lifting the v3.3 hedge (6.6); closing the app keeps it running in the background (4.6); email as the founder-named support route and bug reports by asking in Chat (6.6); an Obsidian workaround through GitHub, support-only (9.10); the changelog added to the provenance tiers and section 2 as a DOCS-VERIFIED source. Flagged, not integrated: a 2026-07-24 changelog line on Android context collection conflicts with 4.5 (Appendix A). Roadmap: a Settings toggle for the collapsed sidebar (Appendix A). Base: v3.3 on Quill main (commit 0977a62).
v3.3 -- 2026-08-30 -- founder Reddit pass (Magpie). Source: public Reddit answers by u/YardLeast3268 (Tushar), June-August 2026, each cited inline with date; permalinks in the PR description (u/Weak-Ad-3583, Alex's listed handle, had no findable activity). Headlines: ZDR agreements with LLM providers publicly stated by Tushar (moves 10.9); meeting audio is never stored, only transcript + summary (6.2, 10.3); transcription is opt-in per meeting by default (6.2); Artifacts / file creation is live, server-side with download (6.6); diarization founder-confirmed in development, still do-not-claim (6.2); integration passthrough boundary added (10.10); third-party MCP servers connectable into Littlebird, hedged (6.6); founder tip on Custom Instructions for underused integrations (6.6); founder-stated roadmap items logged in Appendix A (not publishable as shipped).
v3.2 -- 2026-07-30 -- Power tier confirmed. Source: live littlebird.ai/pricing fetch, 2026-07-30 (the canonical source for section 5). Caught by Carson.
- B4 RESOLVED: the "Power" tier that appeared only on the docs MCP page in v3.1 is confirmed on the live pricing page. Added the Power block to section 5 between Plus and Pro ($42 per month with an annual subscription, $510 up front; $50 billed monthly; everything in Plus plus 2.5x the usage credits of Plus, access to MCP, access to premium image generation, priority support). Updated the Pro block to the pricing page's current wording (from $100 per month; everything in Power plus 5x or 12x the usage credits of Plus, auto-detect language in meeting notes, early access to new features).
- DELETED the now-false writer rule "There is no mid-tier between Plus and Pro." Replaced with the real tier ladder (Basic, Plus, Power, Pro, Team, Enterprise, plus Student) and a Power figures rule. Updated the matching section 15 Hard Don't, which carried the same false claim.
- MCP availability (5.1, 6.6) is now stated as a Power-and-above capability; removed the "do not name the tier" caution. Team/Enterprise MCP position remains unstated (the pricing page does not say).
- NEW flag (Appendix A, B6): the pricing page's download CTA still labels Windows "BETA" while the docs site and 4.5 dropped the qualifier -- surfaces diverge, confirm with the team.
- Live-copy-pass list extended: the pricing page's own FAQ says "GDPR and CCPA compliant" (same B5 divergence as the spoke pages).

v3.1 -- 2026-07-27 -- docs-site reconciliation. Source: support.littlebird.ai/docs (44 pages snapshotted to reference/docs-site-snapshot/, fetched 2026-07-27; diff report at output/docs-bible-diff-2026-07-27.md). Items below are DOCS-VERIFIED (support.littlebird.ai, 2026-07-27) unless noted.
- B1 (four features): kept the four canonical marketing pillars; added section 6.6 SUPPORTING SURFACES (Glance, Projects, Assistant Notes, Command Bar, MCP server, image generation); reworded the section 6 header and the section 15 "fifth feature" Hard Don't accordingly.
- B2 (capture mechanism, 4.4/15): adopted the docs-backed phrasings (not a screen recorder, no video or screenshots, not a keylogger, ignores password fields, password-manager auto-exclusion, credit-card/API-key auto-redaction). KEPT GATED as before: "not pixels," "never sees incognito or private windows," "if you can't see it, Littlebird can't either."
- B3 (languages): docs say Meeting Notes supports "25+ languages"; the live pricing page still says "10+." Inconsistent -- KEPT the Bible's "10+" and FLAGGED (6.2, Appendix A). Do not publish 25+ until the pricing page confirms it.
- B4 ("Power" tier): a "Power" tier appears on the docs MCP page but not in section 5. NOT added anywhere; logged as an open product question (5.1, Appendix A). Do not publish "Power" as a tier.
- B5 (privacy wording): adopted "GDPR-aligned / CCPA-aligned" and HIPAA-conditional-on-BAA (10.4); confirmed no-train covers LLM providers (10.5, upgrading 10.9). NOTE: live-site spoke Privacy sections still say "compliant" and now diverge from the Bible -- a copy pass is needed.
- B6 (Windows): dropped the "(beta)" qualifier from Windows (4.5, 11).
- Bucket C upgrades: Meeting Prep resolved as a Meeting Notes capability and Quick Access resolved as Hover's invocation (6.5; Hover was named Hummingbird when this entry was written); no-train-incl-providers (10.5/10.9); most 4.4 capture claims (above); Outlook mechanics promoted to a documented integration (new 9.12, DOCS-VERIFIED) plus Microsoft 365 admin setup (9.13); Outlook added to the Phase-1 allow-list (section 9) and the section 1 / section 15 gates.
- Bucket A additions folded in: context-awareness mechanics + exclusions/auto-privacy (4.4, 4.8, 10.6); platforms/mobile clarification (4.5); billing/usage/account mechanics (5.1); Chat mechanics + Chat Library + image generation (6.1); Meeting Notes structure + Meeting Prep + auto-start + import + iOS transcription (6.2); Routines templates + notifications + web-sourced + auto-pause (6.3); supporting surfaces (6.6); Slack status (9.10); Outlook + Microsoft 365 (9.12, 9.13).


1. How to use this bible (read first, subagents)
Cite by section. Every factual sentence you write must trace to a numbered section here. If you cannot point to the section, do not write the claim.
Atomic facts only. Use the short declarative statements in this bible. Do not embellish a fact into something stronger than written.
Approved phrasing shows the REGISTER and the verified capability, not a word ceiling. Where a section gives "approved phrasing," you may reframe and compose the verified capabilities in the v3 voice (section 3): lead with a concrete moment and the ambient-capture thesis. You may never invent a capability, assert a stronger absolute than is written, or describe a mechanic not documented here. In short: reframe the wording freely, never inflate the claim.
Composed claims. A claim that combines two VERIFIED capabilities (for example, read a Plaud transcript, then create a Notion page) is allowed. It is not a new mechanic. It is fact-checkable as the conjunction of its parts: PASS only if BOTH underlying capabilities are individually verified in this bible, and never compose with an unverified tool.
Never invent. No invented features, integrations, mechanics, stats, prices, quotes, or customer names. A gap is not an invitation to fill it.
Defer to a human (route to the approval queue with a flag, do not publish) when:
a claim depends on an item marked TODO or NEEDS-VERIFICATION,
you are tempted to state how an integration works beyond the documented set (Gmail, Google Calendar, Notion, Outlook; see section 9),
you would describe the capture mechanism in absolute terms (see 4.4 and 15),
a price, legal, or security specific is involved and is not verbatim from sections 5 or 10.
Punctuation: ASCII only. No em dashes, no en dashes, no smart quotes. Use periods, commas, parentheses, or the word "to" for ranges. Regular hyphens only inside genuine compound words (for example "bot-free").
The Content Style Guide allows em dashes for human-written content. That permission does not apply to pipeline output. Pipeline output bans them.
When two phrasings are both allowed, pick the one that leads with user pain, not a feature (see section 3).


2. Source-of-truth table
Section
Authoritative source
Last verified
3 Voice and tone
Content Style Guide; Bible v2 sec 2
June 23, 2026
4 Core product facts
littlebird.ai home, FAQ, privacy; Positioning and Messaging; Bible v2
June 17, 2026 (site)
5 Pricing
littlebird.ai/pricing (canonical); Viktor
July 30, 2026 (pricing page)
6 Features
littlebird.ai feature pages; Positioning and Messaging; Day-in-the-life; Launch Tiers
June 23, 2026
7 Positioning and messaging
Positioning and Messaging doc; Brand Guidelines (metaphors); Bible v2
April 3, 2026 (doc)
8 Personas
Marketing Personas; Day-in-the-life
June 23, 2026
9 Integrations
littlebird.ai FAQ list; product confirmation (Gmail, Calendar, Notion)
June 23, 2026
10 Privacy and security
littlebird.ai/privacy; Bible v2
June 17, 2026
11 FAQ
littlebird.ai/faq
June 17, 2026
12 Competitors
Competitive Tracker; six live comparison pages
April 2026 (tracker)
13 Stats
Stats and Metrics table
June 23, 2026
14 Customer proof
Customer Quotes table
June 23, 2026
15 Hard don'ts
Synthesized from all of the above
June 23, 2026


TODO: assign a single owner per row and a monthly re-check date. Competitor and stat rows decay fastest.

Added 2026-07-27: support.littlebird.ai/docs is now a recognized authoritative source for sections 4, 6, 9, and 10 under the DOCS-VERIFIED tier (see the changelog at the top). Snapshots of all 44 docs pages live at reference/docs-site-snapshot/ (fetched 2026-07-27).

Added 2026-09-20: docs.littlebird.ai/changelog, Littlebird's public dated changelog, is a recognized authoritative source for sections 4, 5.1, 6, and 9 under the DOCS-VERIFIED tier (see the provenance note at the top for how to cite it and what it does not settle). Six entries read in v3.4: 2026-07-24, 2026-07-31, 2026-08-07, 2026-08-14, 2026-08-21, 2026-08-28. The changelog also carries the current feature names; when it retires a name, this bible follows.

Added 2026-09-27 (carried from the 2026-09-12 pass): the Littlebird Discord (founder answers by Alex and Tushar, FOUNDER-STATED, cited with channel and date) is a recognized source for sections 4, 5.1, 6, 9, and 10. A Discord answer never outranks a newer DOCS-VERIFIED fact, and the changelog governs on a conflict (see the provenance note).


3. Brand voice and tone
Personality. Supportive, human, engaging, clear, confident. We are an encouraging partner. We are not robotic, generic, or overly technical. The restraint is the brand.

Tone shifts. When the reader is uncertain, be inviting and informative. When frustrated, be calm and empathetic. In marketing, be aspirational and benefit-driven. Humor is allowed when it is natural, never forced.

Core writing rules.

Short, declarative sentences. Confidence through calm, not hype.
Lead with the user's real pain, then the relief. Never open with a feature.
Be honest about tradeoffs, especially privacy. Credibility beats spin.
No emoji spam. No exclamation-heavy energy.

3.1 v3 voice (shipped standard, binding). This is the voice of the approved, shipped copy. It supersedes any older register in the exemplars below.

Contractions are house style. Use them where they read naturally: "it's," "you're," "what's," "don't," "can't," "the answer's." Do not force the formal "what is / you are / it is" register. (The shipped v3 copy uses contractions on every page.)

The ambient-capture thesis is the spine. Every integration page leads from the differentiator: the tool only knows what someone typed into it; Littlebird already saw the work happen, because it reads your screen and transcribes your meetings. Frame capabilities through how Littlebird knows, not just "ask without opening the app."

Headline formula. Short, verb-led, two beats: a setup and a payoff, split by a comma or a period. Name the payoff. Real shipped examples (use as the pattern, not to copy):
- "Every task you agree to, captured before it slips."
- "Trace the bug, draft the PR, write your own standup."
- "End the ticket archaeology. Connect every issue to its context."
- "Recall in plain language. Write back with judgment, not noise."
Do NOT write the older form "Your X is Y. Doing Z should not interrupt you."

Intro structure. Open in a concrete failure scene (a real artifact: the client email, the Slack thread, the meeting), then the passive-capture turn ("Littlebird did. Because it reads your screen and transcribes your meetings..."), then one plain connect line. No hype, no feature-first opening.

Capability voice. "Littlebird can [verb]..., so [the concrete moment it matters]" -- the benefit is a moment or the old cost, and it references the capture source where true ("from a meeting it transcribed," "an email or Slack thread on screen"). Never a flat list where every line is "Littlebird can X without opening Y" (this is the "Linear disease" -- vary the benefit, anchor each to a moment).

Punctuation stays ASCII (see section 1): "--" is the em-dash stand-in; straight quotes only.

DO and DON'T pairs.

DO: "You spend the first ten minutes of every task hunting for context. Littlebird already has it." DON'T: "Littlebird is a revolutionary AI-powered productivity solution."
DO: "Walk into Monday already briefed." DON'T: "Supercharge your workflow and unlock your potential."
DO: "The app runs on your computer. The memory it builds is encrypted and stored in the AWS cloud." DON'T: "Your data never leaves your machine."
DO: "Littlebird already knows your work, so you skip the explaining." DON'T: "Littlebird reads your mind."
DO: "Ask in Chat and get an answer grounded in your real work." DON'T: "Harness the power of next-gen AI."

Approved (USE) words. remember, recall, retrieve, capture, searchable, surface, organize, simplify, clear, precise, honest, direct, track, pay attention, already knows. (Removed from approved: "seamless," "effortless" -- now banned, see below; the shipped v3 voice does not use them.)

Banned words. revolutionary, game-changing, game-changer, cutting-edge, disruptive, next-gen, synergy, leverage, unlock, boost, transform, innovative, solution, ecosystem, supercharged, streamline, seamless(ly), effortless(ly), AI-magic, "harness the power of." Do not overuse "AI-powered" or "AI assistant."

Naming and capitalization (from the Content Style Guide).

"Littlebird." One word. Lowercase b. Never "Little Bird" or "LittleBird."
Capitalize feature names as proper nouns: Chat, Meeting Notes, Routines, Hover. Lowercase when used as a benefit or countable, for example "unlimited meeting notes."
"Chat" the feature is capitalized; "chat with Littlebird" the verb is lowercase.
Sentence case for all headlines and subheadings.
Spell out acronyms on first use.
Oxford comma in lists of three or more.
Numbers: spell out one through nine, numerals for 10 and up. Use % with numerals.
Other house spellings: use case (two words), workflow (one word), website (one word), email (no hyphen), login (noun) / log in (verb), signup (noun) / sign up (verb), real-time (adjective), help center (not support center).
Domain is littlebird.ai. (TODO R4: confirm no live littlebird.com exists; Brand Guidelines used .com, treated as placeholder.)
Punctuation: ASCII only, no em or en dashes in pipeline output (see section 1).


4. Core product facts (atomic, quotable)
4.1 What it is. Littlebird is a personal AI assistant that already knows your work. Secondary descriptor allowed: an ambient work-memory layer. (R5.)

4.2 The one-liner. "Littlebird is an AI assistant that already knows your work, so you can draft, plan, and stay on top of everything without having to catch it up on context."

4.3 How it works. Littlebird runs on your computer and pays attention to the active window you are working in. During meetings it listens along to transcribe and summarize, and no bot joins the call. It can optionally connect to apps for deeper context and to take actions. It works immediately, with zero setup, and gets more useful over time.

4.4 Capture mechanism (D2). Approved phrasing, writers may use this or weaker: "Littlebird reads the text and elements of your active window via macOS accessibility permissions." Also approved: "screenreading," "reads the text on your screen," "pays attention to the active window." Mechanic (DOCS-VERIFIED): capture runs every few seconds on the active window and builds a private, encrypted index of recent activity.

NOW APPROVED (DOCS-VERIFIED, support.littlebird.ai, 2026-07-27 -- the support Context-awareness/Privacy/Exclusions pages state these publicly): "Littlebird is not a screen recorder" / "does not record video of your screen" / "does not take screenshots"; "not a keylogger" / "does not log your keystrokes"; "designed to ignore password fields"; "password managers (1Password, Bitwarden, LastPass, and similar) are auto-detected and excluded by default"; "credit-card numbers and API keys are auto-redacted before storage." Caveat on passwords (do not overclaim): the docs say Littlebird is DESIGNED to ignore password fields, not that it never sees any secret -- the FAQ notes plain text visible elsewhere on screen may still enter context. So write "designed to ignore password fields" / "auto-excludes password managers," never an absolute "never sees your passwords."

STILL GATED, do not publish: "not pixels" (write "no video or screenshots" instead), "never sees incognito or private windows," "if you can't see it, Littlebird can't either." The docs do not make these specific claims. See section 15.
TODO (eng, Alex or Tushar): confirm the remaining gated absolutes (pixel-level capture, incognito/private-window exclusion). When signed off, move them to APPROVED and update section 15.
Why text and not screenshots (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17): "it's not only privacy. It's also because text is primarily what matters, and images are a lot more expensive to store and heavy weight, and I think they have less relevant information in general." Usable as the plain-language reason behind "no video or screenshots." Honest caveat on redaction (same answer): the PII filters "are not PERFECT," and an API key can occasionally be captured, though rarely. So write "auto-redacted" or "designed to catch and redact keys," never "never captures a key." Alex also stated that his own personal data sits on the same servers as every user's; usable with attribution when the objection is "would you trust it yourself."

4.5 Platforms. Mac and Windows. (The "Windows beta" qualifier was dropped 2026-07-27, DOCS-VERIFIED: the support site lists Mac and Windows with no beta label and gives full Windows instructions.) Companion apps on iOS and Android for asking questions away from your desk; the mobile apps give access to the context collected on your desktop and do not capture activity from your phone screen (DOCS-VERIFIED). The core product is desktop. Why the phone is not captured (FOUNDER-STATED, Alex on Discord): on iOS it is not possible because of Apple's policies (#mobile, 2026-06-09: "it's not possible to do this on IOS bc of apple's policies"); an Android capture permission shipped in June 2026 ("android is coming this week!") and was later removed, "because Google was giving us problems on app reviews. We will reintroduce it at some point" (#mobile, 2026-09-09). So the docs-verified line above stands: today the mobile apps do not capture phone activity. Do not claim Android capture until product confirms it is back (Appendix A). Mobile meeting capture (Alex on Discord #feature-requests, 2026-07-17): "you can record the mic on mobile but not system audio," which matches the iOS in-person transcription line in 6.2. Web app (FOUNDER-STATED, Tushar on Discord, June to August 2026): a browser app at app.littlebird.ai exists; you sign in and your chats are there, and support uses it as the first check when the desktop app misbehaves ("does https://app.littlebird.ai work?", #bugs, 2026-08-20; the same check on 2026-06-08, 2026-07-23, and 2026-07-24). It does not capture context (capture is the desktop app's job, 4.4). Its feature set is NEEDS-VERIFICATION: do not list "web" as a platform or describe web-app capabilities in page copy until the docs do.
Mobile app updates (DOCS-VERIFIED (docs.littlebird.ai/changelog), entry dates inline): Read aloud plays a finished Chat reply, a Routine report, or a meeting note out loud (2026-07-31); PDFs, spreadsheets, and documents Littlebird makes open inside the mobile app, where until then the app "showed a download card and handed the file to another app" (2026-08-07); you can write and send email from the phone through Gmail (2026-08-07, see 9.1); you can delete your account from the app (2026-08-07); the iPhone app works in landscape (2026-08-07); on Android, "Select text in any app, choose Ask Littlebird, and it opens a new chat with that text already in the composer" (2026-08-14) -- a share the user starts, not background capture; a Routine can be created, run, edited, and deleted from the phone (2026-08-28). The no-phone-capture line above is unchanged; see Appendix A for an open flag on Android context collection.

4.6 Controls. The app requires user-granted macOS accessibility permissions on Mac. You decide if it runs at startup. You can pause context collection, exclude apps, and delete your data at any time. Nothing is collected without your permission.
Running in the background (FOUNDER-STATED, Tushar on Discord #product-questions, 2026-09-14, in a thread titled "Start in the background"): "close still keeps it running in the background, in settings -> system you can change to just showing in status bar. when you close the app then, it won't show in dock." So closing the window does not stop Littlebird; pausing context collection (4.8) is the control for that. The Settings > System option is a one-off founder description of a mechanic: product-confirm the exact label before page copy; usable as a support answer with the date.

4.7 Company facts (citable). Littlebird raised an $11M seed round (March 2026). Littlebird launched on Product Hunt (March 2026). Co-founder: Alex. Lead engineer: Tushar. Before the seed round, initial capital came from one of the founders (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17: "one of the founders was able to provide us capital to get started"); usable on an about or company page, not as a fundraising claim beyond that sentence.

4.8 Context Awareness controls and exclusions (DOCS-VERIFIED, support.littlebird.ai, 2026-07-27). Context Awareness is the named capability that reads the active window; you decide when it runs and what stays out of view.
Controls: a status button (bottom-left of the app; green = active, gray = paused), a Mac menu-bar icon, and a Windows system-tray icon. Pause for 5, 15, 30, or 60 minutes, or until next launch; resume anytime.
Exclusions: exclude specific apps, specific website domains, or whole content categories (Banking, Social Media, Shopping, Entertainment, Health). Adult content is always excluded by default.
One-off share of an excluded app (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-21); macOS): an excluded app can still be handed to a single message with an @ mention. "A mention is a one-off share rather than a standing permission, so you can hand over one window once without letting Littlebird watch that app at all." The exclusion itself is unchanged. See 6.1.
Automatic protections: password managers (1Password, Bitwarden, LastPass, and similar) are auto-detected and excluded by default; credit-card numbers and API keys are auto-redacted before storage; password fields are always ignored (see 4.4, 10.6). FOUNDER-STATED (Tushar on Reddit, 2026-08-04) confirmation of the mechanism: key detection runs during the context-capture flow, so keys are kept out of ingestion in the first place rather than filtered later.
Tip: enabling Google Docs screen-reader support (Cmd+Option+Z) improves what Littlebird can read from a doc.

4.9 Models (FOUNDER-STATED, Alex on Reddit, AMA 2026-07-17 and r/littlebird 2026-07-23). Littlebird does not run its own foundation model. It uses several third-party AI models and routes requests among them, choosing by its own evals for the best quality per cost as the model landscape changes; the mix changes over time. Alex's framing: "Since we're not like OpenAI or Claude, married to our own models, we're happy to serve whatever models perform best for the lowest cost." Also stated on Discord (#product, 2026-05-18), answering a user who called the product a Claude wrapper: "We use a lot of different llms, not correct to call it a Claude wrapper. I would say it's more like a really complicating piece of software that uses llms rather than a wrapper around them." Usable with attribution to answer the wrapper objection. Premium image generation follows the same rule (Tushar on Discord #product-questions, 2026-06-22): the premium tier uses "whatever the best out there is for varied use cases" at the time, so do not name an image model either (6.6). Not every query goes to the most expensive model; routing weighs the task against the cost (2026-07-23: "makes no sense to run every query through" the top model when the question is what to make for dinner). Model quality is judged by human-written evals run against models, not by LLMs judging LLMs (2026-07-17: "I do not trust LLMs as judges of outputs"). Writer rules: never name a specific model as "the" Littlebird model, never promise a specific model on a plan, and never publish routing economics; say "the best available models for the task" or similar. Pairs with 10.5 (providers, plural, under ZDR and no-training agreements).

4.10 Memory model (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17). How Littlebird's memory is organized, in the founder's own conceptual terms: there are tiers of memory. A condensed layer, maintained by the agent, holds important, quickly accessible facts about your life. Beneath it, a master repository holds the full record of what you have seen, read, sent, or heard, where the agent can find any particular piece of data it needs. It requires no manual management by the user; the stated product goal is for all of this to stay invisible. The surfaces the user CAN edit are Assistant Notes and Custom Instructions (6.6). Writer rules: describe the two-layer idea in plain words ("a short list of key facts plus a full searchable record"); do not name internal stores or claim a specific data structure. Known limitation (same AMA): keeping facts current is an unsolved research problem, "the agents aren't smart enough to know whether some colleague that you used to work with quit or whether this project is complete"; a "personal world model" that updates a graph about your life to keep stale facts out of answers was in research as of 2026-07-17 (Appendix A). Do not claim Littlebird always knows when a fact has gone stale, and do not claim hallucinations are eliminated ("Completely eliminating all hallucinations is really difficult for any LLM product"). Scope of the record (FOUNDER-STATED, Tushar on Discord, 2026-05-28, 2026-06-08, and 2026-06-11): every previous chat is part of it; Littlebird "can find prev convos by chat content," "has access to all prev chats," and "has access to the whole chat history irrespective of the conversation length, and can always pull things on demand." Assistant Notes is not the memory (Tushar on Discord #product, 2026-06-03): "the memory is technically infinite, this is more of a place to keep notes for your preferences you explicitly mention" (see 6.6). Founder framing, September 2026 (FOUNDER-STATED, u/Littlebird_Alex, Littlebird company account, r/ClaudeAI, 2026-09-10): "There's a big difference between an ai simply saving information and an ai actually knowing what information is useful, keeping it updated, and bringing it back when you need it," and the stated next step is "assistants that can build a useful model of your ongoing work without requiring you to explicitly tell them what to remember every time." Quote with attribution as the thinking behind this section; it is a direction, not a shipped capability, and it does not lift the stale-facts limitation above.


5. Pricing (one canonical block, R3)
All figures confirmed against littlebird.ai/pricing and Viktor on June 17, 2026; re-confirmed against a live littlebird.ai/pricing fetch on July 30, 2026 (which added the Power tier, below). The live pricing page is the canonical source for this section. Safe to publish exactly as written. Never publish a price not in this block.

Basic: $0. Full context from day one. Limited daily chats, limited active routines, limited meeting notes, meeting notes in 10+ languages, web search, mobile chat, connect calendar and email, cross-app search, community support.
Plus: $17 per month billed annually ($204 per year up front), or $20 per month billed monthly. 14-day free trial. Adds advanced intelligence in chat, enhanced memory and personalization, more daily chats and routines, unlimited meeting notes, image generation, max intelligence for complex tasks and deep research, priority support.
Power: $42 per month with an annual subscription ($510 up front), or $50 per month billed monthly. Everything in Plus, plus 2.5x the usage credits of Plus, access to MCP, access to premium image generation, priority support.
Pro: from $100 per month. Everything in Power, plus 5x or 12x the usage credits of Plus, auto-detect language in meeting notes, early access to new features.
Team: from $17 per month per seat. Team seat management plus Plus-level capabilities.
Enterprise: custom pricing. SSO and centralized user management, self-hosted deployments, custom security and data controls, dedicated account manager, custom contract and invoicing.
Student: $15 per month for actively enrolled students. First two months free. Apply with a .edu email.

Writer rules. Pro is always "from $100 per month," never a flat $100. For Plus, show both the annual ($17) and monthly ($20) figures, or use the annual rate with the "billed annually" qualifier. For Power, do the same: show both the annual ($42) and monthly ($50) figures, or the annual rate with the "with an annual subscription" qualifier; the $510 up-front figure is the pricing page's own, use it verbatim and do not recompute it. The tier ladder is Basic, Plus, Power, Pro, Team, Enterprise (plus Student, a separate eligibility-gated plan). Power is the mid-tier between Plus and Pro, confirmed on the pricing page 2026-07-30 -- name it accurately and do not invent, rename, or reorder tiers.

5.1 Billing, usage, and account mechanics (DOCS-VERIFIED, support.littlebird.ai, 2026-07-27). Billing runs through the Stripe billing portal (Settings > Subscription > Manage Subscription): update payment method, billing address, cardholder name, and VAT/Tax ID; cancel (access continues to the end of the current period) and reactivate anytime. The invoice-recipient email is set separately in Settings > General. Usage: each plan includes a monthly usage pool shown as a single usage bar (Settings > Usage) with a reset date; usage packs can be purchased anytime, never expire, and do not require upgrading to a higher tier. Account email can be changed in Settings > General (one-time-password flow). B4 RESOLVED 2026-07-30: the "Power" tier the docs MCP page referenced is confirmed on the live pricing page and is now in the section 5 block above. Power is publishable as a tier, and MCP access is a Power-and-above capability (Power includes access to MCP; Pro includes everything in Power). See 6.6 and Appendix A. Usage limits, support context (FOUNDER-STATED, Alex on Reddit, AMA 2026-07-17, also 2026-07-23): the honest answer to "why are limits tight" is unit economics, not stinginess. Alex stated Littlebird is very expensive to run, that the company was losing money per user for a long time and as of the AMA only breaks even per customer, that inference is being moved to more cost-efficient models as they arrive, and that users "should see more improvements to limits soon." Free users also cost money to serve. The Usage tab in Settings is where a user checks their pool (confirmed in the same AMA). Support-doc and community-reply material only: never publish margins, break-even, or cost figures on a page, and never promise a specific limit increase. How usage is consumed (FOUNDER-STATED, Alex on Discord #product, 2026-05-22): usage correlates with messages but is not a message count, because Littlebird is an agent that can run many-step queries; Alex's example: saying "hi" is a lot cheaper than "pls summarize all my meetings last week." Routine runs draw from the same pool, and Routines set to Max mode or run more than once a day cost more (Alex on Discord #product-questions, 2026-07-12). Support-doc material: it explains a usage bar that moves faster than the message count. Not adopted: the per-day dollar cap Alex described for Plus on 2026-05-22 ("capped at $15 / day"), which predates the monthly usage pool the docs describe and is not a pricing-page figure; and the lowest usage-pack denomination Tushar mentioned before packs launched (Discord #feature-requests, 2026-06-16). Packs themselves are DOCS-VERIFIED above; prices come only from section 5. Economics, same gate as the AMA lines: "Our goal is simply not to lose money right now we're not marking up tokens at all" (Alex, #product, 2026-05-22) and "because we are so context heavy the product can be extremely expensive to run" (Alex, #user-show-and-tell, 2026-05-28); never on a page.
Usage visibility (DOCS-VERIFIED (docs.littlebird.ai/changelog), entry dates inline): "Littlebird tells you before your monthly usage runs out: a notice above the composer at 70% and 90%, the percentage spent and its reset date on the Usage menu, and each Routine's share of the cycle on its configure panel." (2026-08-28). The usage bar is reachable from the profile menu and "breaks your usage down by chat mode" (2026-07-31). "You'll now see a warning when monthly usage is being spent faster than usual." (2026-07-24). "When you run out of credits, the composer says so instead of being replaced by an upgrade prompt." (2026-08-07). The Artifacts page notes that building an artifact "can use more of your monthly usage than an ordinary chat" (2026-08-21). Publishable as written; do not attach usage amounts, which no source states.
Plus usage (FOUNDER-STATED, Tushar on Discord #product-questions, 2026-09-16; support context, not page copy): in a thread titled "Has Usage for plus accounts been lowered?" Tushar answered "no, what's the cost breakdown in settings-> usage". The same day, in a #product thread whose title the export truncates at "did they change the amount of usage you": "nope, replied on your other thread for more details". Support-doc guidance: to a user asking whether their plan's usage was cut, the founder-stated answer is no as of 2026-09-16, and the first diagnostic step is the breakdown in Settings > Usage. Section 5 still carries only the pricing page's multipliers.


6. Features (four canonical marketing pillars)
Four canonical marketing pillars: Chat, Meeting Notes, Routines, Hover. Do not promote a supporting surface to a fifth pillar (D3). Littlebird also ships additional product surfaces (Glance, Projects, Assistant Notes, Command Bar, MCP server, image generation) -- these are real and DOCS-VERIFIED, documented in section 6.6 as SUPPORTING SURFACES, not marketing pillars. Reference them factually where useful; never headline a spoke or hero as if one were a fifth pillar.

6.1 Chat.

What it is: your AI with the full picture.
What it does: ask questions and create content without catching it up, because it already knows your work.
Approved one-liner: "Chat with everything you have seen."
Do not claim: that it beats ChatGPT or Claude at general reasoning or writing (see 12, 15).
Chat mechanics (DOCS-VERIFIED, 2026-07-27): attach a document or image to a chat; dictate a request with the microphone; turn on Max mode for more thorough multi-step reasoning (available tools depend on plan, connected integrations, and permissions); share a chat as Private, Team members, or Public (the share is a snapshot up to the moment you create or update it); star, search, filter, archive (archived chats stay searchable and referenceable), or delete (deleting is permanent -- purged from Littlebird's memory) chats. The Chat Library offers ready-made starting prompts. Image generation runs inside Chat (create/draw an image from a text prompt; a Plus capability, see section 5).
App Mentions (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-21); macOS only): "Type @ in the composer and choose a window, and Littlebird reads it for that message." The menu lists what you have open with each window's title beside the app, so you hand over the tab or file you mean rather than the app in general. Name two windows and Littlebird holds them side by side. Apps you have excluded from context (4.8) sit in their own "Attach an excluded app" section: "A mention is a one-off share rather than a standing permission." Hover takes @ too (6.4).
Chat modes (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-28)): "A new Ultra mode for pro users, the max mode is also optimized and should cost lower now." The entry names Ultra and its audience ("pro users," lowercase in the entry; the section 5 Pro plan is the natural reading, confirm before pricing copy) and says nothing about what Ultra does: name it, and do not describe its behavior (Appendix A). The Max cost line is hedged ("should"); do not quantify it. Every chat mode shows a description in the mode menu with its keyboard shortcut (2026-07-31).
Modes (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17): both the main app and Hover (then named Hummingbird) offer three modes, Quick, Default, and Research, and each surface has its own selector ("Just make sure to select the correct one in Hummingbird and the main app"). Research mode is "the most powerful agent" and, per Alex, the one most exposed to the universal AI failure of overconfident and sometimes wrong answers. Naming, resolved in v3.5 (FOUNDER-STATED, Discord): "Max" is the product name for the deep mode. Alex, #user-show-and-tell, 2026-05-28: "We have the 'max' mode for when you need max intelligence too"; Tushar, #lounge, 2026-07-10: "it's limited to max mode btw, regular should be working fine"; the docs say "Max mode" (2026-07-27). "Research mode" is the founders' informal name for the same mode (Alex, AMA, 2026-07-17; Alex on Discord #lounge, 2026-07-26: "we've been improving research mode if that's what you mean? or do you mean the default mode?"). Write Quick, Default, and Max, plus Ultra for Pro users per the 2026-08-28 changelog line above (DOCS-VERIFIED, which outranks the founder count of three); never "Research mode" in page copy. One product confirm of the full mode list before a page explains the modes. How Max works (Tushar on Discord #product-questions, 2026-05-16): Max runs "a form of subagents" (v1 released mid-May 2026), with "multiple types of subagents" so that cheap exploration goes to a cheaper subagent; the team was optimizing Max for both cost and quality. Support context; do not publish the architecture. A mode beyond Max, or a customizable Max, was under discussion on 2026-07-08 (Tushar, #product; Appendix A).
Sources and feedback (FOUNDER-STATED, Alex on Reddit): the stated design is that "everything the model outputs is grounded in the user's actual documents with sources shown, so people can verify instead of trusting it blind" (r/artificial, 2026-07-29). Link inclusion is measured by specific evals but is not perfect (AMA, 2026-07-17: "I'm not sure why it's not quoting the links"), so write "answers cite their sources" rather than "always cites every source." Feedback path (AMA, 2026-07-17): downvote a bad chat and file an in-app support request; downvotes are used to debug and improve the system. Related tip from Tushar (2026-07-17): ask Littlebird to remember to always link its references (see 6.6).
Languages (FOUNDER-STATED, Tushar on Discord #feature-requests, 2026-05-28): "yes you can talk in any language," the chat title is generated in the language you use, and "multiple languages do work for both chat and meeting notes." The interface itself (button labels, menus) had no language setting as of 2026-05-27 and 2026-05-28 ("we don't yet have different interface langauges"). Write "chat in your language"; do not claim a localized interface. The Meeting Notes language count stays governed by B3 (6.2).
Voice conversation mode (FOUNDER-STATED, hedged, Alex on Discord #feature-requests, 2026-09-03): to a request for a voice mode that reads briefings aloud and takes spoken replies (the user asked for it on iOS), Alex answered "this is live!" Two words and no docs page yet: treat voice conversation as reported live on 2026-09-03 and product-confirm what exactly shipped (read-aloud, hands-free back-and-forth, which platforms) before any page copy. Voice input by dictation is DOCS-VERIFIED above; voice output was a roadmap item on 2026-07-17 (Appendix A). Text-to-speech, plan (FOUNDER-STATED, u/Littlebird_Alex (Littlebird company account), r/littlebird, 2026-09-23, in a thread titled "TTS ETA?"): "it's already available for pro users!" This is the first plan statement on record for spoken output: Pro. The answer does not say which surface it covers (the mobile Read aloud of 2026-07-31 in 4.5, a desktop read-aloud, or the voice conversation mode above), so write spoken output as a Pro capability only after product confirms which surfaces carry it, and do not write it as available on Basic or Plus (Appendix A).
Chat housekeeping (DOCS-VERIFIED (docs.littlebird.ai/changelog), entry dates inline): the full Chats view previews every conversation, with search and filters, and several chats can be selected at once to add to a project, archive, or delete (2026-07-24); an attached PDF opens in a preview before you send it (2026-07-31); the composer sets which project a message belongs to (2026-08-14); macOS dictation "runs to twenty minutes, and reaching the limit transcribes what you said rather than discarding it" (2026-08-14).
Sidebar toggle (FOUNDER-STATED, Tushar on Discord #feature-requests, 2026-09-24): in the thread that asked for a toggle so the collapsed sidebar does not open when the cursor reaches the screen edge, Tushar had said "we'll have a toggle in settings for this in the next release" (2026-09-17) and then wrote "released now" (2026-09-24). So the toggle is shipped as of 2026-09-24 on the founder's word; the exact Settings label is not stated, so product-confirm it before page copy and use it as a support answer with the date until the changelog carries it.
Appearance settings (FOUNDER-STATED, hedged, Tushar on Discord #feature-requests, 2026-10-04): in a thread whose request the export truncates at "Hello, any chance we can get one font", Tushar answered "there should be an option in settings -> appearance." So Settings has an Appearance section, and that is where a font request is pointed. What the option controls (font size, typeface, or both) is not stated, and "should be" is hedged: use it as a support answer with the date ("look in Settings > Appearance") and product-confirm the control before page copy names it (Appendix A).

6.2 Meeting Notes.

What it is: notes that write themselves.
What it does: transcribes and summarizes your meetings so you stay present. No bot joins the call. Works for any audio or video playing on your computer, not only live calls.
Approved one-liner: "Focus on the conversation. The notes take care of themselves."
Audio handling (FOUNDER-STATED, Tushar on Reddit, 2026-08-04): the actual recording or audio isn't stored anywhere; only the transcript and summary are stored, on the server. A strong, quotable privacy fact -- pair it with the 10.1 cloud frame, never against it.
Consent and defaults (FOUNDER-STATED, Tushar on Reddit, 2026-08-04, confirming the Join Meeting mechanic below): by default Littlebird only transcribes a meeting if you ask it to -- you get a notification when you join a call -- and it can be configured to ignore meetings entirely while you use the other features.
Do not claim: accurate speaker attribution or speaker diarization (users report this is imperfect; NEEDS-VERIFICATION on current state -- the docs do NOT resolve this). Update (FOUNDER-STATED, Tushar on Reddit, 2026-08-04): "we're working on diarization now" -- in development, still not claimable as shipped until product confirms.
Meeting Notes mechanics (DOCS-VERIFIED, 2026-07-27): every note produces an editable, shareable structured summary -- Executive summary, "For you" (your personalized action items), Topics discussed, Decisions, Action items (split You vs Others), and Risks/open questions -- alongside the full transcript and your own notes tab. Capture two ways: an automatic pre-meeting prompt (Join Meeting) or manual (+ New Note). Auto-start transcription can be enabled for supported meeting apps (Settings > Meetings), with calendar filtering to choose which calendars are monitored. A Meeting Prep button on future event cards produces a pre-meeting briefing from your context (see 6.5). After a meeting you can chat directly from the summary. iOS supports in-person transcription via the device mic (no system audio, so online meetings stay desktop-only). Existing transcripts/summaries from other apps can be imported (Settings > Import) and become searchable Meeting Notes.
Founder confirmations on Discord (FOUNDER-STATED, Tushar unless noted): chat on the meeting note page shipped 2026-06-03 ("released now," #meeting-notes; announced 2026-05-28 as the no-delay way to ask about a meeting), which is the docs-verified "chat directly from the summary" above. Meeting Prep does not need the calendar entry: "you can just ask LB to prep you for the meeting" and "asking to prep in chat works too" (#product-questions, 2026-05-16). Per-meeting-type structure: asked for a specific note template, Tushar pointed to Settings > Meetings, "sth like for <this> type of meetings, follow this structure" (#lounge, 2026-09-10), so a user can steer the summary structure by meeting type with an instruction there; write it as an instruction setting, not a template picker, until the docs describe the UI (Appendix A). Speaker separation: Alex on Discord #meeting-notes, 2026-07-17, "speaker separation within the next few weeks"; still do-not-claim (Appendix A).
Organizing notes (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-07-24)): filter the list by project, select several notes at once to batch delete or move them to a project, and add an upcoming event to a project -- "for a recurring event, all of its meeting notes become part of the project." "Meeting summaries now follow your Project Instructions, too."
Automatic prep and recording (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-07-31)): automatic meeting prep can be enabled in Settings > Meetings, arriving 30 minutes before the meeting starts; automatic recording can be turned on "so you do not have to remember to start recording every time," and apps can be excluded from it. Apps can also be excluded from automatic meeting detection (2026-07-24). Both are settings the user turns on, consistent with the opt-in default above. Meeting prep "now takes your connected integrations into account, alongside your screen context and web search" (2026-08-07).
Email delivery (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-14)): "When Littlebird finishes meeting prep or a meeting summary, it emails you the result." Either can be turned off in Settings > Meetings, or with the unsubscribe link in the email.
Send to attendees (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-21)): a summary is written for the note-taker and carries a private For you section, so Send to attendees rewrites it for other readers. "Littlebird drops your private section, recasts the summary for a group, and opens an email draft addressed to the other people on the invite." "Nothing sends on its own." The draft goes out from the user's own connected Gmail account (9.1), so replies come back to the user rather than to Littlebird.
During and after a call (DOCS-VERIFIED (docs.littlebird.ai/changelog), entry dates inline): the floating widget has a composer while a meeting is recording, and the answer lands in that meeting's chat (2026-08-14); a composer at the bottom of the meetings list lets you ask about several meetings at once (2026-07-31); manually stopping a recording generates the summary automatically again unless the transcript was short (2026-08-28, replacing the 2026-07-24 step where you reviewed the transcript and chose Generate summary); on Mac, an interrupted recording "recovers in the background instead of being lost" (2026-07-24). Word note: the changelog says "recording" for a transcription session. It says nothing about audio being stored, so the audio-handling line above stands.
Granola import (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-07-24)): "The Granola import screen now supports drag and drop, lets you review a CSV before importing it, and explains where to find your Granola export."
Number to reconcile (B3, flagged 2026-07-27): the support FAQ says Meeting Notes supports "25+ languages"; the live pricing page still says "10+ languages" (Basic). Kept at 10+ pending reconciliation -- do NOT publish 25+ until the pricing page confirms it.

6.3 Routines.

What it is: insights from your real work.
What it does: delivers proactive, personalized updates on your schedule, for example a morning briefing or a weekly project recap. Auto-pause is a real setting.
Example use case: Littlebird can function as a daily journal through a Routine. "Daily journal" is an example use of Routines, not a separate feature (D3).
Approved one-liner: "Proactive insights, on your schedule."
Routines mechanics (DOCS-VERIFIED, 2026-07-27): a Routine is a saved prompt that runs on a schedule (daily, weekly, or monthly at a chosen time) and pushes the result back to you. Ready-made Daily/Weekly/Monthly templates exist. Routines can draw from your own work or from the web (e.g. a custom news feed). Auto-pause is on by default (a Routine pauses if you stop opening its output; resume anytime from the Routines dashboard). Configure push and email notifications when an output is ready. You can ask about Routines in Chat ("what did my morning briefing say today").
Routines updates (DOCS-VERIFIED (docs.littlebird.ai/changelog), entry dates inline). Create by asking (2026-07-31): setting up a Routine "no longer means filling in a form" -- describe it in Chat and Littlebird creates it; the prompt, schedule, or notifications of an existing Routine change the same way, and you can ask what one is set to before changing it. Reply by email (2026-08-07): "Reply to the email and Littlebird picks up the same chat that wrote the report"; "The answer comes back in the same email thread." Full report in the email (2026-08-14): "The report is now in the body of the email, and any PDF it produced comes attached." Each Routine email has an unsubscribe link that turns off email for that Routine. Artifacts on a schedule (2026-08-28): a Routine can build a new Artifact every run, for example a weekly PDF that arrives in Littlebird and by email (see 6.6). Memory across runs (2026-07-24): "Chat can answer questions about past Routine outputs, and a Routine can refer back to its own or another Routine's previous reports." Suggestions (2026-08-28): "Ask Littlebird what you could automate and it suggests Routines drawn from how you actually work, then offers to set them up." Phone (2026-08-28): a Routine can be created, run, edited, and deleted from the phone. Housekeeping: search finds what Routines produced and Routine runs stay out of the chat list (2026-08-21); a Routine that Littlebird paused explains why (2026-08-14); deleting a Routine removes the chats it created (2026-08-14); each Routine's share of the usage cycle shows on its configure panel (2026-08-28, see 5.1).
Founder-described example (FOUNDER-STATED, Alex on Reddit, r/AI_Agents, 2026-08-11; also stated 2026-08-05 in r/ProductivityGuide and 2026-08-11 in r/smallbusiness): a daily digest Routine that pulls decisions made and action items from across Slack, calendar, documents, and meeting notes, set up once and run automatically, so he does not have to prompt for it each day. Usable as a Routines example in the register of this section; it adds no capability (the native Slack integration is still "coming soon" per 9.10; on-screen Slack is captured like any other active window, 4.4).
Routines on Discord (FOUNDER-STATED). Correcting a Routine (Tushar, #lounge, 2026-09-01): "you can now reply to the routine itself in chat, it can improve its own prompt and remember things for future runs." Usable as a support answer and as a Routines capability line ("reply to a Routine to correct it, and it adjusts its own prompt"); dated 2026-09-01 and not yet on the docs site, so product-confirm before a hero claim (the docs-verified Reply by email line above, 2026-08-07, covers the reply path; the self-improving prompt is founder-stated only). Routines use connected integrations: a Routine "connects to your other integrations like calendar and mail" (Tushar, #bugs, 2026-05-31), and a Routine can write its output to a Notion page but "can't write to sheets" as of 2026-07-03 (Tushar, #lounge). Routines have a mode selector and consume the plan's usage pool: the selector was being added on 2026-06-03 (Tushar, #product), and Alex asked a user with a drained pool whether they had "routines running on max mode or routines running frequently like more than 1x a day" (#product-questions, 2026-07-12). A Routine can refresh an artifact on its schedule ("it should already work in routines," Tushar, #feature-requests, 2026-08-26; DOCS-VERIFIED since as Artifacts on a schedule, 2026-08-28, above). Downvoting applies to Routine outputs, not only chats ("If you are getting incorrect results in routines pls downvote," Alex, #feature-requests, 2026-05-16; again 2026-05-30). Why "Daily journal" is an example and not a feature (Tushar, #bugs, 2026-05-31): "we didn't really see much usage of the journal feature. and everyone had some customization they wanted which made it tricky to support. so we're focusing on routines which is a more general abstraction." Confirmed again from the company account (u/Littlebird_Alex, r/littlebird, 2026-09-24, in a thread titled "Daily Journal removed, artifacts removed, no changelog since August"): "you can bring it back manually with the prompt above from u/littlebird_shahzad" (Shahzad's prompt is not in the export; Tushar's own journal prompt below serves the same purpose). Founder-shared prompts, usable as Routine examples with attribution: Tushar's full daily-journal prompt (#bugs, 2026-05-31), a "what did I get wrong today" decision-review prompt (#a-littlebird-told-me, 2026-06-10, with his warning that Littlebird "can be really brutal with this one"), and "Am I spending my time on the right things?" (2026-06-07); permalinks in the v3.5 PR description. Workaround for event-triggered Routines (Tushar, #feature-requests, 2026-09-09): schedule it weekly and "in instructions ask it to stop if there is no calendar entry"; real triggers are roadmap (Appendix A).
Routines and on-device integrations (FOUNDER-STATED, Tushar on Discord #integrations, 2026-09-24): "routines don't yet support on device integrations, we're working on it." The same question was raised in #product on 2026-09-27 by a user who described Routines as running server-side even with the desktop app open and therefore unable to see the integrations that live on the machine; Alex asked whether it is planned (the user's description is context, not a founder statement). Which integrations count as on-device is not stated; local (stdio) MCP servers (6.6) are the clear case. Writer rule: describe Routines as using cloud-connected integrations (calendar, mail, Notion, per the lines above) and never as using a local MCP server or any on-device integration; roadmap, "we're working on it" (Appendix A).

6.4 Hover.

Name (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-28)): "Hummingbird is renamed to Hover. The window, the shortcut, and everything it does are unchanged." Write Hover everywhere. Hummingbird is the retired name; use it only where a reader needs the link between the two, as "Hover (formerly Hummingbird)."
What it is: Littlebird wherever you are working.
What it does: open Littlebird over whatever you are doing (double-tap Option), ask, and keep going without breaking flow.
Platform note: currently Mac-only. Confirmed (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17, before the rename): "Hummingbird is not yet live on Windows," with no firm ETA ("within a month or two max" as of that date; Appendix A). Do not claim Hover on Windows until product confirms. Hover has its own Quick / Default / Max mode selector, separate from the main app's (see 6.1 on naming; the founder's "Research" is Max).
Approved one-liner: "Get answers without breaking your flow."
In-meeting use (FOUNDER-STATED, Tushar on Discord #feature-requests, 2026-05-16, before the rename): you can ask Littlebird questions during a live meeting, "and if you're on mac you can also use Hummingbird to do this without moving away from the meeting window." Usable as the Hover example for the meeting moment.
Hover mechanics (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-14), other entry dates inline): Hover "opens as overlay, so you can ask for help without leaving the work behind," with "situational awareness about your windows, ongoing meetings and everything else Littlebird knows." "We've redesigned the experience to run multiple conversations simultaneously with a new conversation rail." You can type @ to bring in another window (App Mentions, 6.1) and move between chats with keyboard shortcuts without opening the Littlebird app. "Ask about the email, the spreadsheet, or the page in front of you without attaching it first." Ctrl+E moves the Hover conversation you are in into the main window (2026-08-21). A Hover thread shows which project it belongs to, and you can remove it from the project (2026-08-07). Rollout note: the multi-conversation rail first appeared in the 2026-07-24 entry for Beta program members; the 2026-08-14 entry announces the redesign with no beta label.
Screenshot scope note: "You can take a screenshot from the overlay and auto attach." That is a screenshot the user takes and attaches to one message. It does not change the 4.4 capture facts: background context capture takes no screenshots or video. Keep the 4.4 phrasings scoped to background capture, and do not write that Littlebird never handles a screenshot.

6.5 Resolved candidate features (DOCS-VERIFIED, support.littlebird.ai, 2026-07-27).

Meeting Prep: RESOLVED -- a capability of Meeting Notes, not a separate feature. It surfaces as a "Meeting Prep" button on a future event's card and produces a pre-meeting briefing from your context. Write it as a Meeting Notes capability (see 6.2); do not promote it to a fifth pillar.
Quick Access: RESOLVED -- "Quick Access" is the name of Hover's on-demand invocation (double-tap Option), the same surface as Hover, not a distinct feature (the docs called it "Hummingbird Quick Access" when snapshotted 2026-07-27, before the 2026-08-28 rename to Hover). Keep "Hover" as the feature name; "Quick Access" may be used to describe the invocation.

6.6 Supporting surfaces (DOCS-VERIFIED, support.littlebird.ai, 2026-07-27). Real product surfaces, NOT marketing pillars (D3). Reference them factually; never headline a spoke or hero as if one were a fifth feature.
- Glance: a collapsible panel on the home (new-chat) page (Cmd+G / Ctrl+G) that surfaces your day before you type -- widgets for Schedule, Routines, Yesterday's meetings, Continue (your last chat), and Connect more. Reorderable; remembered across sessions.
- Projects: folders that group related chats and meetings, with a per-project Instructions field (standing guidance), per-project file uploads shared to every chat in the project, and a context-scope setting (a project can't see outside conversations by default; toggleable). Updates (DOCS-VERIFIED (docs.littlebird.ai/changelog), entry dates inline): Shared Projects for teams (2026-08-28) -- on a team, a project can be shared so that "every chat and note part of the project is shared with others." "Open a project, choose Share, and give each person or team Member or Admin access. You can share a project with the whole team or specific people within a team." Also: a project can carry a colored icon or emoji, and existing chats and notes can be added from the project page (2026-08-28); in a project chat, questions about meetings follow the project's awareness setting (2026-07-31); project uploads accept files up to 30 MB (2026-08-07). Founder-described pattern (Tushar on Discord #feature-requests, 2026-06-05): keep the data where it already lives (for example a Notion page), add that page and what you care about as the project Instructions, and chat inside the project; the same pattern works for a reading list kept on a Notion or GitHub page that Littlebird updates on request.
- Assistant Notes and Custom Instructions: user-editable persistent memory. Custom Instructions (Settings > Chat) are standing rules only you can edit. Assistant Notes are editable from chat -- Littlebird can add, update, or remove them on request; they persist across inactivity. Founder-endorsed tip (Tushar on Reddit, 2026-07-17): if Littlebird underuses a connected integration or a reference, tell it to remember to use it, or add a standing rule in Settings > Chat > Instructions -- usable as support-doc guidance. How the founders say to use each (FOUNDER-STATED, Tushar on Discord): Assistant Notes is "essentially a field for Littlebird to remember the most important preferences," editing it is "supported more to delete or update outdated/incorrect statements which may be affecting responses," and "manual should generally be limited to custom instructions" (#product-questions, 2026-06-07; repeated 2026-07-22, "can you add it in custom instructions than assistant notes"). The notes have a size cap that was "being increased" on 2026-06-03 and is not a memory cap ("the memory is technically infinite," #product; see 4.10). Assistant Notes are viewable in Settings > Chat (2026-05-28). Things you can just tell it: "tell Littlebird to take note of it, it'll remember across conversations" (an About Me, 2026-05-27); "figure out my writing style and remember so you can use whenever i ask you to write in future" (2026-05-15; automatic style learning was in the works); and, when it does not search meetings for a question about "calls," ask it to remember to search meetings too, or add that line in Settings > Chat (#meeting-notes, 2026-06-01), the same tip as the 2026-07-17 Reddit one. Caution (Alex on Discord #feature-requests, 2026-09-03): a sensitive-information guardrail blocked a user from saving medical corrections to Assistant Notes; Alex called it something to "fix asap." Until product confirms the intended behavior, do not write copy that promises Assistant Notes will hold health details (see 8.5, 10.4, Appendix A).
- Command Bar: a Cmd+K / Ctrl+K palette to jump between chats, meeting notes, and settings, with contextual actions (e.g. download a chat as markdown, copy a chat link) and Reset Local Database (a hard refresh from the cloud). Settings search (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-21)): "Settings has a search box that finds a setting across every section and jumps to the exact row, typos included." It reaches connected accounts, MCP servers, keyboard shortcuts, and archived chats, and individual settings turn up in the command bar. Support use (FOUNDER-STATED, Tushar on Discord #bugs, 2026-08-19 to 2026-08-21): when chats look missing, Cmd+K then Reset Local Database (Tushar also calls it "refresh local DB") re-syncs from the cloud; "the chat itself shouldn't be lost." Export of a single chat is Cmd+K then copy as markdown (#feature-requests, 2026-08-26).
- MCP server: connect an external AI client (Claude Code/Desktop, Cursor, ChatGPT, and others) to Littlebird tools via OAuth at mcp.littlebird.ai/mcp, scoped to your account permissions. (A Slack MCP server is also offered today; see 9.10.) Availability is plan-gated: MCP access is a Power-and-above capability (Power includes access to MCP; Pro includes everything in Power), confirmed on the live pricing page 2026-07-30 (B4 RESOLVED; see 5.1 and section 5). You may name the tier. Do not claim MCP on Basic or Plus, and do not state where Team or Enterprise sit on MCP -- the pricing page does not say. Reverse direction, Littlebird as the MCP client (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-07-24), which lifts the v3.3 hedge on Tushar's 2026-07-17 Reddit "should"): a third-party MCP server can be added to Littlebird from the catalog or by URL. The 2026-07-24 entry says Remember The Milk "now completes sign-in whether you connect it from the catalog or add its MCP URL yourself" and "If browser sign-in for an MCP server gets stuck, you can switch to an API key. Servers that use Basic authentication can also accept an email or username." Connected MCP servers are reachable from Settings search (2026-08-21). No changelog entry states a plan gate for adding MCP servers; do not state one. Founder detail on that reverse direction (FOUNDER-STATED; the docs-verified 2026-07-24 entry above governs the mechanic, these answers add the click path and the limits): Littlebird can act as the MCP client and connect any third-party remote MCP server as a custom integration. Mechanic, stated by Tushar on Discord repeatedly from May to August 2026: "there is a custom mcp button, you can add any MCP if it's not in the list. as long as you're on the latest version of the app" (#feature-requests, 2026-05-17); "go to settings -> integrations -> add custom(on top right)" and enter the server URL (#integrations, 2026-06-06, giving a CRM's MCP endpoint as the example, right after "if it has MCP, you can connect it today"); the same for Egnyte's remote MCP server, "it should be possible" (#integrations, 2026-06-16); and the docs pointer littlebird-docs.vercel.app/docs/mcp (#feature-requests, 2026-07-30). A connected server's write tools work too: "any MCP with write would also just work" (2026-05-17). Alex: "sure esp if they have an MCP should be easy" (#feature-requests, 2026-05-21), matching his AMA lines ("our aim is to support basically everyone with a public MCP server"; "if they have MCP servers yes, otherwise, maybe," 2026-07-17) and Tushar's hedged Reddit line of the same date. Approved phrasing: "Connect any tool that has a public MCP server as a custom integration in Settings > Integrations." Connecting a tool this way does NOT document its mechanics: what Littlebird reads or writes inside that tool stays under the 9.10 rule unless its own section 9 block exists. Plan gate for custom MCP connections is NEEDS-VERIFICATION: the pricing page's "access to MCP" line (Power and above) is the Littlebird MCP server; on 2026-08-24 Tushar told a user on the Plus plan "it does, do you not see add custom in integrations?" (#feature-requests), which suggests custom connections are available on Plus, but the question text is truncated. Do not state a tier for custom MCP connections until product confirms (Appendix A). Local (stdio) MCP servers: promised through June ("within the next 2 weeks," Alex, #integrations, 2026-06-08; "that support will come this month," Tushar, #lounge, 2026-06-08; "Will custom local MCPs be supported? yes," 2026-06-16), "in the next week or so" in the AMA (2026-07-17), and "in beta rn, should be released soon" on 2026-08-03 (Tushar, #feature-requests). Still not claimable until docs or product confirm general release (Appendix A). The Littlebird MCP server itself, history and shape (FOUNDER-STATED, Discord): an experimental API was offered to early users on 2026-05-22 (Alex, #feature-requests), a v1 went to beta on 2026-06-16 (Tushar, #integrations), it was "recently rolled out on pro" by 2026-07-08 (Tushar, #product: "you can connect LB in your claude"), and Alex said on 2026-07-17 "it will def be available on power plan" (#lounge), which the pricing page confirmed on 2026-07-30. Support article: support.littlebird.ai/article/littlebird-mcp-server (Tushar, 2026-07-23). What it exposes (Tushar, #product, 2026-07-09): "it exposes all the context," as atomic tools; there is no single "get daily summary" tool, so a client pieces the day together from the summaries and context it queries, and a programmatic or headless MCP client works ("a usecase like - openclaw sending an evening brief on a schedule would work perfectly fine"). Write "connect your AI client to your Littlebird context"; do not list tool names. Automations through Zapier, Make, n8n, or webhooks are not available: "we are working on this!" (Alex, #lounge, 2026-07-17; Appendix A). Alex also noted the MCP server was so new that Littlebird's own self-knowledge did not yet describe it (2026-07-17), a useful support answer when Littlebird cannot explain one of its newest features.
- Image generation: create an image from a text prompt inside Chat (a Plus capability; also noted in 6.1). Premium image generation (Power and above, section 5) uses "whatever the best out there is for varied use cases" at the time, with "much better editing capabilities and text in images" than the standard tier (FOUNDER-STATED, Tushar on Discord #product-questions, 2026-06-21 and 2026-06-22). Do not name the image model (4.9).
- Artifacts (file creation): DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-28): "You can now ask Littlebird for a webpage, a PDF, a CSV, or a Markdown document and it will build the file." "An HTML Artifact can also be published as a web page and shared with others." A Routine can build a new one every run (6.3). The Artifacts page gathers everything Littlebird has built: search by the artifact's name or the chat it came from, filter by type, switch between a grid and a list, and open, refine, download, share, or delete from the menu (2026-08-21). Artifacts open inside the mobile app (2026-08-07) and download straight from the full view (2026-07-31). Usage: the Artifacts page notes that building one "can use more of your monthly usage than an ordinary chat" (2026-08-21). Earlier FOUNDER-STATED detail (Tushar on Reddit, 2026-07-30 and 2026-08-01): generation runs server-side with a download; stated as available on Pro plans as of 2026-07-30. PLAN GATE still NEEDS-VERIFICATION: no changelog entry names the plans that get Artifacts, so confirm the current tier gate before publishing any plan specifics (Appendix A). A supporting surface, not a fifth pillar (D3). Founder-stated detail within the docs-verified output list above (Tushar on Discord): PDFs ("it can def generate pdfs," #product, 2026-07-27) and HTML, including an HTML page modeled on a screenshot you give it (#feature-requests, 2026-06-04). A Routine can refresh an artifact on its schedule (2026-08-26; see 6.3). Canvas, a related surface for "dashboards and visualizations in chat or routines" (for example a morning brief shown visually rather than as markdown), was "not fully rolled out yet" on 2026-08-07 (#mobile); roadmap, not claimable (Appendix A).
- Team analytics (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-07-24 and 2026-07-31)): "Team admins can now see how Littlebird is landing across the team: adoption and engagement, messages over time, feature use and top integrations." Found in Settings > Team > Analytics. From 2026-07-31: "Every member of a team can now open team analytics from the profile menu, not just admins." With Shared Projects (above), these are the team surfaces the changelog documents; the section 5 Team block stays the pricing page's wording. A supporting surface, not a fifth pillar (D3).
- Feedback and support. Report by asking (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-07-31)): say "report a bug: my meeting notes did not sync this morning" in Chat and Littlebird drafts the report for you to read and send; "It works the same way for a feature you wish existed, or an answer worth flagging as poor." Support route (FOUNDER-STATED, Tushar on Discord #lounge, 2026-09-16, in a thread titled "What's the best way to get support?"): "we usually get back fast on email." Hedged ("usually") and no address is given: do not state a response time or invent a support address. Support-doc guidance, not page copy.
- Summaries outside the app (FOUNDER-STATED, Tushar on Discord #lounge, 2026-09-13; carried from the 2026-09-13 pass). In a #lounge thread whose original request is not in the export, Tushar replied to a user's follow-up with "what form would be ideal for you?" and named two live paths and one interim workaround for getting summaries out of Littlebird. (1) The Littlebird MCP server: "we do give this in Littlebird's MCP server which can be connected to other things" -- the MCP server bullet above governs how to describe it, including the plan gate. (2) Email: "we do now also send the summaries on email(toggleable in settings)." The scope this answer left open is DOCS-VERIFIED since: meeting prep and meeting summaries are emailed, with the off-switch in Settings > Meetings (6.2, changelog 2026-08-14), and Routine reports arrive in full by email (6.3). (3) Automation workaround, hedged ("prob"): "In the mean time you can prob do this via email, with n8n/zapier taking the Email from LB as their input." Support-doc guidance only, stated as the user's own automation on top of the email: Zapier and n8n are not documented integrations (section 9) and public APIs are roadmap (Appendix A), so never write "integrates with Zapier," "n8n integration," or "API access." A supporting note, not a fifth pillar (D3).
- Also available (no dedicated page treatment needed): an in-app Learn course / guided tour.


7. Positioning and messaging
7.1 Positioning statement (canonical). For busy professionals who constantly context-switch across meetings, docs, and messages, Littlebird is a personal AI assistant that already understands your work without you having to explain it. Unlike generic AI chatbots and single-purpose AI tools, Littlebird pays attention to your screen and meetings to build a private memory of your work, so every answer, draft, and plan is grounded in what you are actually doing.

7.2 Canonical hero lines (D4). "Remember everything." "AI that remembers every doc, meeting, and decision." "Littlebird pays attention."

7.3 Value props.

No cold start. It already has the context, so you skip the explaining.
Zero setup. Works the moment you install it. No integrations required.
Cross-app memory. Connects your apps, meetings, and conversations into one searchable memory.
Proactive, not just reactive. Routines surface what matters before you ask.
Founder framing for zero setup (FOUNDER-STATED, Tushar on Discord #feature-requests, 2026-06-19): "many people also over worry about the right workflows and setup. it's very easy in this space to spend time on work around the work than actual work," and "with Littlebird we want to get to a state where you don't really have to worry about all this." Until proactive suggestions ship, "you can just ask Littlebird for ways it can be more helpful and all the apps you use which you can connect directly." Quotable with attribution; the tip (ask Littlebird how it can help and which of your apps it can connect) is a support answer.

7.4 Messaging pillars (need, benefit).

Effortless recall: never lose track of anything you have seen.
Instant creation: go from a blank page to a strong first draft in seconds, grounded in your real work.
Complete clarity: Littlebird connects the dots across your work so insights do not slip through the cracks.
Stay present: be in the meeting, not buried in notes.

7.5 Signature differentiator (use often). A general AI is a brilliant stranger you must re-brief every time. Littlebird is the colleague who was already in the room. Strongest proof point: meetings. ChatGPT can only summarize a transcript if you paste one in. Littlebird captured it automatically and it is already in your memory. Founder framing (FOUNDER-STATED, Alex on Reddit, August 2026), usable as the thinking behind this section: "The difference is memory plus access, not raw intelligence" (r/ArtificialInteligence, 2026-08-11, with the example of asking "did we ship the pricing change?" and getting an answer from yesterday's meeting notes and the Slack thread where it was punted); "the harder problem isn't depth of recall inside one conversation, it's breadth, pulling from the places where work actually happens" (r/ChatGPT, 2026-08-26); and an assistant becomes a coworker "the day they've absorbed enough ambient context, past decisions, who actually cares about what, that they can tell what matters without being told" (r/AI_Agents, 2026-08-19). Quote with attribution or paraphrase in the v3 voice; do not turn these into capability claims beyond sections 4 and 6. Restated from the company account on 2026-09-25 (u/Littlebird_Alex (Littlebird company account), r/ProductivityGuide): Claude and ChatGPT "are great when you give them the context for a task, but they don't always have the full context of everything you've been working on, whereas Littlebird keeps that context connected for you." Same framing, newer date; quotable with attribution under the section 12 rules.

7.6 Allowed metaphors (D4): "second brain," "the colleague who was already in the room," "already knows your work." 7.7 AVOID metaphors (D4): "reads your mind" (overclaim and privacy tension). "digital twin" (competitors own this term; see 12).

7.8 Autonomy stance (FOUNDER-STATED, Alex on Reddit, r/artificial 2026-07-29 and 2026-08-03). Littlebird is deliberately conservative about autonomy: outputs are grounded in the user's own documents with sources shown, and are "treated as drafts a human looks at, not actions the system takes on its own." The line Alex draws: "AI should own recall, you should own interpretation." Use this to frame human-in-the-loop copy honestly. It is consistent with the section 15 rule against claiming interactive task management, and it does not cancel the documented write actions in section 9, which run on the user's explicit request.


8. ICPs and personas
Seven use-case segments (slugs confirmed live). Hooks: Leadership "Stop hunting for information. Start leading." (confirm verbatim). Creative "Stop digging for inspiration. Start creating." Client-facing "Manage more clients without losing track of details." Technical and Product "Stay in flow. Ship faster." Knowledge and Education "Remembers everything you read, hear, and learn." Health and Wellness "Focus on your patients, not admin work." Personal "Keep life organized without the mental load."

Slugs: /use-cases/leadership, /creative, /client-facing, /technical-and-product, /knowledge-and-education, /health-wellness-professionals, /personal-and-productivity. Nav labels the health segment "Health Professionals" but the slug is health-wellness-professionals; use the slug for internal links.

Five personas (use for pain language in briefs).

8.1 Mara, the founder-operator. Maps to Business and Leadership. Largest paid segment. Seed to Series A founder, 6 hours of meetings a day, no EA. Pain: reconstructing the week, drafting investor updates from memory, staying present. How LB helps: it already saw the week, so she walks into Monday briefed and drafts the update from real activity. Angle: "Walk into Monday already briefed." Reach: LinkedIn, founder Discords, Lenny's, Product Hunt.

8.2 Devin, the senior IC engineer. Maps to Technical and Product. Second-biggest paid segment and the most credentialing audience on privacy. Deep-focus engineer, privacy-conscious. Pain: PR and decision archeology across Slack, tickets, docs. How LB helps: pulls the full context behind a PR or decision without 20 minutes of digging; no bots in meetings, no model training on his work. Angle: no bots, no training, AWS East with audits and pen tests. Note: do not use "local-first" for this persona; the accurate story is managed cloud with strong controls (see 10, 15). Reach: Hacker News, r/LocalLLaMA, GitHub.

8.3 Priya, the independent pro. Maps to Client-facing and Creative (freelancers). Consultant or fractional with 4 to 7 clients. Pain: 15-minute call prep, capturing billable time, per-client recall. How LB helps: prep any client call in under 2 minutes, build Friday timesheets from real activity, recall every client conversation. Angle: recovered revenue and photographic client memory. Reach: LinkedIn fractional and consultant communities, Superpath, Pavilion.

8.4 Jordan, the cross-functional connector. Maps to Creative Professionals (marketers, PMM) with Business and Leadership overlap. Senior PMM, marketing manager, head of ops, or chief of staff. Pain: synthesizing 8 teams into a deck or launch from a blank page. How LB helps: it watched the week, so readouts and launch copy start from the actual work. Angle: stop being the human RAM of the company. Reach: LinkedIn, Sharebird, Pavilion, Lenny's.

8.5 Sam, the cognitive load carrier (ADHD and neurodivergent). Cross-cutting persona, strongest organic resonance; maps most to Personal Life and Productivity. Pain: executive-function tax, meeting panic, half-remembered follow-ups. How LB helps: passive capture (no need to remember to use it), the morning brief Routine, find the half-remembered thing without spiraling. Reach: r/ADHD, r/adhdwomen, ADHD TikTok and Substacks. Note: Sam is a persona, not a use-case slug.


9. Integrations (Phase 1 priority)
Littlebird supports hundreds of integrations. They are optional. Littlebird works automatically by paying attention to your screen; connecting an app gives deeper access and lets Littlebird take actions. Users browse the full list in Settings > Integrations. Custom MCP: any tool with a public MCP server can be added as a custom integration (Settings > Integrations > Add custom; FOUNDER-STATED, see 6.6). That makes the tool connectable, not documented: its mechanics stay NEEDS-VERIFICATION under 9.10 unless a section 9 block exists. No native task manager, by design (FOUNDER-STATED, Tushar on Discord #feature-requests, 2026-07-22): "we're doing more on the side of integrating with different todo lists than building one ourselves as we found in past that it's really hard to figure out the minimal subset which works well for everyone." Teach it which list to use: "remember to use my todoist, when ever i ask you to create or fetch todos," and creating tasks from chat "should just work" (same answer); a connected list can also feed a morning-brief Routine (Tushar, 2026-07-10). Write task features as integration capabilities (9.4, 9.11), never as a built-in task manager; a synced-todos view and push-to-task-app buttons for meeting action items were "in works" on 2026-07-22 (Appendix A).

Multiple accounts per integration (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-21)): you can connect several accounts of the same integration, "so your work and your personal life do not have to share one connection." The entry's examples: "Add two Gmail inboxes, both of your calendars, a second Slack workspace, or two Notion or Linear workspaces, then ask for the one you mean." Path: Settings > Integrations, choose an integration, select Add another account. "Littlebird names each one from the account you signed in with" and "uses that name when it decides where a request should go"; rename any of them with the pencil beside the name. "Each account keeps its own controls, so you can pause, remove, or reconnect one without touching the others." Limits of this entry: it does not name Outlook, so 9.12's one-account line stands until the docs say otherwise (Appendix A); and it names Slack workspaces without saying which connection path, so the 9.10 Slack status line is unchanged -- do not describe the native Slack integration as shipped on the strength of this entry.
How connected integrations are used (DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-21)): "Improved how Littlebird uses your connected integrations, so it checks your email, calendar, Slack, or ticket tracker for an answer instead of relying on what happens to be on your screen."

Phase 1 build rule. Build integration pages only for the fully documented integrations -- Gmail (9.1), Google Calendar (9.2), Notion (9.3), and Outlook (9.12) -- plus the product-verified Todoist (9.4) and TickTick (9.11). Outlook was added 2026-07-27 as DOCS-VERIFIED (mechanics documented on the support site; treat one tier below product-verified). Do not build pages for any integration whose mechanics are still NEEDS-VERIFICATION. Do not invent mechanics for any integration (V3).

Register note (how to read the approved phrasing below). The "Approved phrasing" and "User benefit" lines in every 9.x block state the MINIMUM verified claim and its register floor -- not a word ceiling. Writers reframe them in the v3 voice (section 3.1): lead with the capture source and a concrete moment. The verified CAPABILITY is fixed; the wording is not. Example transform (Asana search):
- Register floor (as written below): "Littlebird can search tasks across your Asana workspace." + "find any task by keyword, assignee, or project without switching to Asana."
- v3 reframe (allowed, no new capability): "Littlebird can search tasks across your Asana workspace. Ask by keyword, assignee, project, or by what you remember from a meeting, and the exact task surfaces in Chat -- no context switch required."
The reframe adds a moment and the capture source; it asserts no capability not listed. That is the bar for all of section 9.

Composed capabilities (allowed, fact-checkable). Combining two or more VERIFIED capabilities across connected tools is not a new mechanic. Example: read a Plaud transcript (9.8 read) then create a Notion page from it (9.3 write) -- "turn a recording into a written-up Notion page." A composed claim is PASS only if every capability it invokes is individually verified in this section, and never if any leg uses an unverified tool or an unlisted capability. Fact-check it as the conjunction of its parts.
9.1 Gmail (Phase 1)
PRODUCT-VERIFIED - all capabilities tested and confirmed working in the live Littlebird app by product (Nikhil), 2026-06-27. Read, write, and send behavior is first-hand verified, including the send-on-behalf capability and multi-account retrieval. The page may publish once the standard editorial review is complete. No eng sign-off gate remains on this section.

What Littlebird does with it: reads your email to surface open loops and to draft follow-ups, and can send and act on email on your behalf.
How it works: connect your Gmail account or accounts. Littlebird reads message content to build context and can compose, draft, and send. Multiple Gmail accounts can be connected.
User benefit: nothing gets missed because it came from the wrong inbox; follow-ups are drafted from the real thread, not from memory.
Approved phrasing: "Connect Gmail and Littlebird surfaces open loops, drafts replies in context, and can send on your behalf." "Ask what a client emailed this week and Littlebird pulls it from the right account."
Updates (DOCS-VERIFIED (docs.littlebird.ai/changelog), entry dates inline): sending runs through an approval step -- "When Littlebird drafts an email, you can now revise and format it directly in the send card before you approve it" (2026-07-24). From the phone, the draft appears in the chat with the recipient and subject filled in; tap Edit, then Send, "and it goes out through Gmail" (2026-08-07). Attachments: "You can now ask Chat about a PDF, RTF, or plain-text file attached to an email." (2026-08-14). Meeting summaries can be sent to attendees from the user's own Gmail account (6.2).
Do not claim: any data handling that contradicts section 10. Do not state inbox or attachment specifics not listed here.
9.2 Google Calendar (Phase 1)
PRODUCT-VERIFIED - all capabilities tested and confirmed working in the live Littlebird app by product (Nikhil), 2026-06-27. Read, write, scheduling, and calendar-action behavior is first-hand verified, including create, edit, move events, and find-time-and-send-invite. The page may publish once the standard editorial review is complete. No eng sign-off gate remains on this section.

What Littlebird does with it: reads your events to prep you for meetings, and can create and edit events.
How it works: connect Google Calendar. Littlebird reads upcoming events to generate prep, and can schedule, create, and edit events.
User benefit: walk into every meeting prepared; scheduling happens without leaving Littlebird.
Approved phrasing: "Connect Google Calendar and Littlebird preps you before each meeting and can create or move events for you." "Ask Littlebird to find time and send the invite."
Do not claim: availability-negotiation or conference-room features unless added here later. Do not restate Section 4.4 capture claims.
9.3 Notion (Phase 1)
PRODUCT-VERIFIED - all 9 capabilities below tested and confirmed working in the live Littlebird app by product (Nikhil), 2026-06-25. Read, write, and action behavior is first-hand verified, not telemetry-inferred. The page may publish once the standard editorial review is complete. No eng sign-off gate remains on this section.

Note: Notion connects as an integration in Settings > Integrations (confirmed).

What Littlebird does with it: searches and retrieves your Notion content for recall, queries your databases and data sources, and can write back to Notion (create pages, update pages, update data sources, create databases, move pages).

How it works: connect Notion in Settings > Integrations. Littlebird reads pages and databases to answer and recall, and can write back into Notion.

READ capabilities (approved phrasing, ordered by adoption):

Search across pages and databases. Approved phrasing: "Ask Littlebird to search your Notion workspace and it surfaces the page, database, or block you need." User benefit: find anything in Notion by asking, without remembering where it lives. Source: notion-search, 549 active users.

Fetch and pull the full content of a specific page. Approved phrasing: "Littlebird can pull the full content of any Notion page into context." User benefit: read a page without opening Notion. Source: notion-fetch, 487 active users.

Query database views and filtered data sources. Approved phrasing: "Littlebird can query a Notion database view and return filtered results." User benefit: ask a question against a Notion database the way you would ask a colleague. Source: notion-query-database-view (110 active users), notion-query-data-sources (70 active users).

WRITE / ACTION capabilities (approved phrasing, ordered by adoption):

Create new pages. Approved phrasing: "Littlebird can create a new Notion page, including from a chat message or a meeting summary." User benefit: turn a conversation or a Littlebird Chat response directly into a Notion page. Source: notion-create-pages, 308 active users.

Update existing pages. Approved phrasing: "Littlebird can update an existing Notion page." User benefit: keep a page current without switching to Notion to edit it manually. Source: notion-update-page, 246 active users.

Create new databases. Approved phrasing: "Littlebird can create a new Notion database." User benefit: spin up a structured database from a chat request. Source: notion-create-database, 123 active users.

Update a database's data source. Approved phrasing: "Littlebird can update a Notion database's data source." User benefit: keep a database's underlying data current without editing it by hand in Notion. Source: notion-update-data-source, 89 active users.

Move pages and reorganize. Approved phrasing: "Littlebird can move a Notion page to a different location in your workspace." User benefit: reorganize Notion from Chat without navigating the sidebar. Source: notion-move-pages, 59 active users.

User benefit (summary): find anything across Notion by asking, and let Littlebird keep your pages and databases updated as work happens.

Approved phrasing (existing, still valid): "Connect Notion and Littlebird recalls anything across your pages and can write updates back." "Ask across your Notion workspace without hunting through pages."

Do not claim: row-level or permissions behavior, or anything not listed here. Do not claim notion-duplicate-page, notion-get-users, notion-get-teams, notion-create-comment, notion-get-comments, or notion-create-view as approved capabilities - these appear in the telemetry but are not in this approved showcase set.
9.4 Todoist
PRODUCT-VERIFIED - all 11 capabilities (6 read + 5 write) personally app-tested by Nikhil, 2026-06-28. 11/11 PASS against a live Todoist account. Read, write, and action behavior is first-hand verified. The page may publish once the standard editorial review is complete. No eng sign-off gate remains on this section. Telemetry citations below remain as the original evidence basis and usage context.

Note: category-level mechanic ("Littlebird connects with Todoist for deeper context and actions") was confirmed by product prior to app testing. All specific capabilities below are now personally verified in addition to being telemetry-backed.

What Littlebird does with it: finds and surfaces your tasks, projects, and overviews, and can add tasks, update tasks, complete tasks, create projects, and reschedule tasks.

How it works: connect Todoist. Littlebird reads your tasks and projects for recall and surface, and can take action on your Todoist workspace.

READ capabilities (approved phrasing, ordered by adoption):

Find tasks. Approved phrasing: "Littlebird can find your tasks across Todoist." User benefit: surface the tasks you need without opening Todoist to search. Source: find-tasks, 178 active users.

Find projects. Approved phrasing: "Littlebird can find your Todoist projects." User benefit: see which projects exist and what is in them without switching to Todoist. Source: find-projects, 125 active users.

Find tasks by date. Approved phrasing: "Littlebird can find your tasks by due date." User benefit: see what is due today, this week, or on a specific date without opening Todoist. Source: find-tasks-by-date, 123 active users.

Get an overview. Approved phrasing: "Littlebird can get an overview of your tasks and projects." User benefit: see the full picture of what is on your plate without switching to Todoist. Source: get-overview, 86 active users.

Search across Todoist. Approved phrasing: "Littlebird can search across your Todoist." User benefit: find anything in Todoist by asking. Source: search, 55 active users.

Find completed tasks. Approved phrasing: "Littlebird can find your completed tasks." User benefit: look back at what you have finished, useful for weekly reviews or tracking billable work. Source: find-completed-tasks, 48 active users.

WRITE / ACTION capabilities (approved phrasing, ordered by adoption):

Add tasks. Approved phrasing: "Littlebird can add a new task to Todoist, including from a chat message, a meeting, or a passing thought." User benefit: capture tasks without breaking your flow or switching to Todoist. Source: add-tasks, 180 active users.

Update tasks. Approved phrasing: "Littlebird can update an existing task in Todoist." User benefit: edit a task's details without switching to Todoist. Source: update-tasks, 83 active users.

Mark tasks complete. Approved phrasing: "Littlebird can mark a task as complete in Todoist." User benefit: check off tasks without opening Todoist. Source: complete-tasks, 61 active users.

Create projects. Approved phrasing: "Littlebird can create a new project in Todoist." User benefit: spin up a project from a chat request without switching to Todoist. Source: add-projects, 62 active users.

Reschedule tasks. Approved phrasing: "Littlebird can reschedule a task to a new due date in Todoist." User benefit: move a task to a different date without opening your task list. Source: reschedule-tasks, 29 active users.

User benefit (summary): find what is on your plate, capture tasks in the moment, and keep your Todoist workspace current, all without switching to Todoist.

Approved phrasing (template, still valid): "Littlebird connects with Todoist for deeper context and actions."

Do not claim: delete-object (56 users), add-sections (36 users), find-sections (35 users), find-labels (27 users), fetch-object (22 users), add-labels (17 users), add-reminders (17 users), find-activity (12 users), or user-info (12 users) as approved capabilities - these appear in the telemetry but are not in this approved showcase set. Do not claim any task or project behavior not listed above.

9.5 GitHub
TELEMETRY-VERIFIED - capabilities sourced from real usage telemetry (benchmarks/usage-data.md, 30-day active users, as of 2026-06-23). Not yet personally app-tested by product. Per prompts/GATING-POLICY.md Tier 2, these may be written clean on pages. Flag for app verification before promoting to PRODUCT-VERIFIED.

Note: get_me (111 active users) is a session-initialization tool (authenticates the connection), not a user-requested capability. Not listed below. search_users (16 active users) is an identity lookup tool, not a core user-facing capability. Not listed below.

What Littlebird does with it: searches repositories, reads file contents, surfaces commits, branches, pull requests, and issues for context; and can create or update files in repositories, create branches, create pull requests, and create repositories.

How it works: connect GitHub. Littlebird can search and read across your repositories for recall and context, and can write to repositories and take actions on your behalf.

READ capabilities (approved phrasing, ordered by adoption):

Search repositories. Approved phrasing: "Littlebird can search your GitHub repositories." User benefit: find any repo by name, topic, or keyword without switching to GitHub. Source: search_repositories, 112 active users.

Read file contents. Approved phrasing: "Littlebird can read the contents of any file in your GitHub repositories." User benefit: pull code, configs, or docs from any file into Chat without switching to GitHub. Source: get_file_contents, 104 active users, 5,881 calls (~57 calls/user -- heavily used in agentic read loops).

List commits. Approved phrasing: "Littlebird can list and surface commits across your repositories." User benefit: see what changed and when, across any branch, without opening GitHub. Source: list_commits, 74 active users.

Search code. Approved phrasing: "Littlebird can search code across your GitHub repositories." User benefit: find any function, pattern, or string across your codebase by asking. Source: search_code, 63 active users.

Read pull request details. Approved phrasing: "Littlebird can read the full details of any pull request." User benefit: get the full context of a PR -- description, diff, and comments -- without leaving your current work. Source: pull_request_read, 36 active users, 1,057 calls (~29 calls/user -- high call volume indicates deep PR context reads in agentic flows).

Search pull requests. Approved phrasing: "Littlebird can search your pull requests." User benefit: find any PR by author, branch, or keyword without switching to GitHub. Source: search_pull_requests, 36 active users.

List branches. Approved phrasing: "Littlebird can list the branches in your repositories." User benefit: see what branches exist and what is in progress without opening GitHub. Source: list_branches, 35 active users.

Search commits. Approved phrasing: "Littlebird can search commits across your repositories." User benefit: find who changed what, when, and why without scrolling through git log. Source: search_commits, 32 active users.

List pull requests. Approved phrasing: "Littlebird can list open and closed pull requests." User benefit: see the full PR queue across any repository at a glance. Source: list_pull_requests, 29 active users.

Search issues. Approved phrasing: "Littlebird can search issues across your repositories." User benefit: find any bug report, feature request, or discussion by keyword without switching to GitHub. Source: search_issues, 24 active users.

Get commit details. Approved phrasing: "Littlebird can pull the details of a specific commit." User benefit: read the diff, message, and context of any commit by asking. Source: get_commit, 20 active users.

List issues. Approved phrasing: "Littlebird can list issues in your repositories." User benefit: see the open issue queue for any repository without leaving Chat. Source: list_issues, 14 active users.

WRITE / ACTION capabilities (approved phrasing, ordered by adoption):

Create, update, or push files. Approved phrasing: "Littlebird can create, update, or push files to your GitHub repositories." User benefit: write or commit to a repo from Chat without opening GitHub or your editor. Source: create_or_update_file, 41 active users; push_files, 37 active users.

Create a repository. Approved phrasing: "Littlebird can create a new GitHub repository." User benefit: spin up a new repository from a Chat request without opening GitHub. Source: create_repository, 16 active users.

Create a pull request. Approved phrasing: "Littlebird can create a pull request." User benefit: open a PR from Chat without switching to GitHub. Source: create_pull_request, 14 active users.

Create a branch. Approved phrasing: "Littlebird can create a new branch in your repositories." User benefit: create a branch for new work from a Chat request. Source: create_branch, 14 active users.

User benefit (summary): search and read across your entire GitHub codebase from Chat -- repositories, files, commits, branches, pull requests, and issues -- and take actions like creating files, branches, and pull requests without leaving your current work.

Approved phrasing (template, still valid): "Littlebird connects with GitHub for deeper context and actions."

Do not claim: delete_file (9 users -- destructive action, low adoption), get_me (session initialization, not a user capability), search_users (identity lookup, not a core use case). Do not claim any GitHub behavior not listed above.

9.6 ClickUp
TELEMETRY-VERIFIED - capabilities sourced from real usage telemetry (benchmarks/usage-data.md, 30-day active users, as of 2026-06-23). Not yet personally app-tested by product. Per prompts/GATING-POLICY.md Tier 2, these may be written clean on pages. Flag for app verification before promoting to PRODUCT-VERIFIED.

Note: resolve_assignees (32 active users) and find_member_by_name (19 active users) are identity-resolution utilities used internally when other operations require an assignee ID -- they are not user-facing capabilities. Not listed below.

What Littlebird does with it: reads your workspace structure, filters and searches tasks, reads task details and comments, and can create tasks, update tasks, create lists, and set reminders.

How it works: connect ClickUp. Littlebird can read and search across your workspace for recall and context, and can create and update tasks and workspace structures on your behalf.

READ capabilities (approved phrasing, ordered by adoption):

Read workspace structure. Approved phrasing: "Littlebird can read your ClickUp workspace structure." User benefit: see how your workspace is organized -- spaces, folders, and lists -- without opening ClickUp. Source: get_workspace_hierarchy, 91 active users.

Filter tasks. Approved phrasing: "Littlebird can filter tasks across your ClickUp workspace." User benefit: find exactly the tasks you need by assignee, due date, status, or priority without navigating to ClickUp. Source: filter_tasks, 86 active users.

Search ClickUp. Approved phrasing: "Littlebird can search across your ClickUp workspace." User benefit: find any task, list, or discussion in ClickUp by asking. Source: search, 68 active users.

Read task details. Approved phrasing: "Littlebird can read the full details of any task in ClickUp." User benefit: get the description, assignees, status, and priority of any task without opening ClickUp. Source: get_task, 44 active users.

Read a list. Approved phrasing: "Littlebird can read the contents of any ClickUp list." User benefit: see every task in a list without switching to ClickUp. Source: get_list, 23 active users.

Read workspace members. Approved phrasing: "Littlebird can read your ClickUp workspace members." User benefit: see who is in your workspace without opening ClickUp. Source: get_workspace_members, 20 active users.

Read task comments. Approved phrasing: "Littlebird can read the comments on any ClickUp task." User benefit: follow the discussion on a task without opening it in ClickUp. Source: get_task_comments, 19 active users.

WRITE / ACTION capabilities (approved phrasing, ordered by adoption):

Create a task. Approved phrasing: "Littlebird can create a new task in ClickUp." User benefit: capture tasks without breaking your flow or switching to ClickUp. Source: create_task, 57 active users, 1,759 calls (~31 calls/user -- high automation signal, heavily used in agentic task-creation flows).

Update a task. Approved phrasing: "Littlebird can update an existing task in ClickUp." User benefit: edit a task's details, status, or assignee without opening ClickUp. Source: update_task, 38 active users, 1,245 calls (~33 calls/user -- high automation signal).

Create a list. Approved phrasing: "Littlebird can create a new list in your ClickUp workspace." User benefit: add a list from a Chat request without opening ClickUp. Source: create_list_in_folder, 19 active users.

Create a reminder. Approved phrasing: "Littlebird can create a reminder in ClickUp." User benefit: set a reminder for any task or deadline from Chat without switching to ClickUp. Source: create_reminder, 14 active users.

User benefit (summary): search and read across your ClickUp workspace from Chat -- tasks, lists, comments, and structure -- and create or update tasks without leaving your current work.

Approved phrasing (template, still valid): "Littlebird connects with ClickUp for deeper context and actions."

Do not claim: delete_task (17 users -- destructive, do not claim), resolve_assignees (utility/internal), find_member_by_name (identity lookup, internal), create_folder (13 users -- not in approved set), create_list (12 users -- not in approved set), create_comment (11 users -- not in approved set), get_document_pages (12 users -- not in approved set), get_custom_fields (12 users -- not in approved set), list_document_pages (11 users -- not in approved set). Do not claim any ClickUp behavior not listed above.

9.7 Asana
TELEMETRY-VERIFIED - capabilities sourced from real usage telemetry (benchmarks/usage-data.md, 30-day active users, as of 2026-06-23). Not yet personally app-tested by product. Per prompts/GATING-POLICY.md Tier 2, these may be written clean on pages. Flag for app verification before promoting to PRODUCT-VERIFIED.

Note: get_me (39 active users) is a session-initialization tool, not a user-requested capability. Not listed below.

What Littlebird does with it: searches tasks and objects, surfaces your tasks and projects, reads task and project details, and can create tasks, update tasks, and create projects.

How it works: connect Asana. Littlebird can search and read across your workspace for recall and context, and can create and update tasks and projects on your behalf.

READ capabilities (approved phrasing, ordered by adoption):

Search tasks. Approved phrasing: "Littlebird can search tasks across your Asana workspace." User benefit: find any task by keyword, assignee, or project without switching to Asana. Source: search_tasks, 70 active users.

Get projects. Approved phrasing: "Littlebird can surface your Asana projects." User benefit: see what projects exist and what is in them without opening Asana. Source: get_projects, 61 active users.

Get my tasks. Approved phrasing: "Littlebird can surface the tasks assigned to you in Asana." User benefit: see your personal task list without opening Asana. Source: get_my_tasks, 57 active users.

Get tasks. Approved phrasing: "Littlebird can retrieve tasks from any project or section in Asana." User benefit: pull the full task list for any project without switching to Asana. Source: get_tasks, 43 active users.

Search objects. Approved phrasing: "Littlebird can search across Asana tasks, projects, and other objects." User benefit: find anything in Asana by asking, not just tasks. Source: search_objects, 41 active users.

Read task details. Approved phrasing: "Littlebird can read the full details of any task in Asana." User benefit: get the description, assignee, due date, and subtasks for any task without opening Asana. Source: get_task, 36 active users, 503 calls (~14 calls/user -- high call volume indicates repeated deep task reads in agentic flows).

Read project details. Approved phrasing: "Littlebird can read the details of any Asana project." User benefit: get the status, members, and tasks for any project without switching to Asana. Source: get_project, 30 active users.

WRITE / ACTION capabilities (approved phrasing, ordered by adoption):

Create a task. Approved phrasing: "Littlebird can create a new task in Asana." User benefit: capture tasks without breaking your flow or switching to Asana. Source: create_tasks, 48 active users.

Update a task. Approved phrasing: "Littlebird can update an existing task in Asana." User benefit: edit a task's details, assignee, or due date without opening Asana. Source: update_tasks, 22 active users.

Create a project. Approved phrasing: "Littlebird can create a new project in Asana." User benefit: spin up a project from a Chat request without switching to Asana. Source: create_project, 16 active users.

User benefit (summary): search and read across your Asana workspace from Chat -- tasks, projects, and assignments -- and create or update work without leaving your current context.

Approved phrasing (template, still valid): "Littlebird connects with Asana for deeper context and actions."

Do not claim: delete_task (8 users -- destructive, low adoption), get_me (session initialization, not a user capability), get_users (11 users -- identity lookup, low adoption), get_teams (10 users -- identity lookup, low adoption), get_portfolios (9 users -- too low), add_comment (9 users -- too low). Do not claim any Asana behavior not listed above.

9.8 Plaud
TELEMETRY-VERIFIED - capabilities sourced from real usage telemetry (benchmarks/usage-data.md, 30-day active users, as of 2026-06-23). Not yet personally app-tested by product. Per prompts/GATING-POLICY.md Tier 2, these may be written clean on pages. Flag for app verification before promoting to PRODUCT-VERIFIED.

Note: Plaud is a READ-only integration. No write or action tools appear in the 30-day telemetry. Do not claim any ability to create, edit, or post content in Plaud. Note: get_current_user (11 active users) is a session-initialization tool, not a user-requested capability. Not listed below.

What Littlebird does with it: surfaces your Plaud recordings and retrieves the AI-generated notes and verbatim transcripts from them.

How it works: connect Plaud. Littlebird can read your recordings, notes, and transcripts for recall and context in Chat.

READ capabilities (approved phrasing, ordered by adoption):

List recordings. Approved phrasing: "Littlebird can list your Plaud recordings." User benefit: see all your recorded meetings and audio files without opening the Plaud app. Source: list_files, 81 active users.

Read a note. Approved phrasing: "Littlebird can retrieve the AI-generated note for any Plaud recording." User benefit: pull the summary and key points from a Plaud recording into Chat without opening the app. Source: get_note, 55 active users, 931 calls (~17 calls/user -- users are actively and repeatedly pulling notes from multiple recordings).

Read a transcript. Approved phrasing: "Littlebird can retrieve the full transcript of any Plaud recording." User benefit: search and reference the verbatim text of any recorded conversation from Chat. Source: get_transcript, 39 active users, 561 calls (~14 calls/user -- high usage signal).

Read recording metadata. Approved phrasing: "Littlebird can read the metadata for any Plaud recording." User benefit: see the title, date, and details of any recording without opening the Plaud app. Source: get_file, 18 active users.

User benefit (summary): access your Plaud recordings, AI notes, and transcripts from Chat -- surface any meeting content by asking, without opening the Plaud app.

Approved phrasing (template, still valid): "Littlebird connects with Plaud for deeper context and actions."

Do not claim: get_current_user (session initialization, not a user capability). Do not claim any write, edit, or create behavior in Plaud -- no such tools exist in the telemetry. Do not claim any Plaud behavior not listed above.

9.9 Linear
TELEMETRY-VERIFIED - capabilities sourced from real usage telemetry (benchmarks/usage-data.md, 30-day active users, as of 2026-06-23). Not yet personally app-tested by product. Per prompts/GATING-POLICY.md Tier 2, these may be written clean on pages. Flag for app verification before promoting to PRODUCT-VERIFIED.

What Littlebird does with it: lists and reads issues, teams, projects, statuses, comments, and labels, and can create or update issues.

How it works: connect Linear. Littlebird can read across your Linear workspace for recall and context, and can create or update issues on your behalf.

READ capabilities (approved phrasing, ordered by adoption):

List issues. Approved phrasing: "Littlebird can list issues across your Linear workspace." User benefit: see the full issue queue for any team without opening Linear. Source: list_issues, 63 active users.

List teams. Approved phrasing: "Littlebird can list the teams in your Linear workspace." User benefit: see how your workspace is organized by team without opening Linear. Source: list_teams, 38 active users.

Read an issue. Approved phrasing: "Littlebird can read the full details of any Linear issue." User benefit: get the description, status, assignee, and priority of any issue without switching to Linear. Source: get_issue, 37 active users.

List projects. Approved phrasing: "Littlebird can list the projects in your Linear workspace." User benefit: see all active projects and their status without opening Linear. Source: list_projects, 31 active users.

Read issue statuses. Approved phrasing: "Littlebird can read your team's workflow statuses in Linear." User benefit: understand the states your team uses without opening Linear. Source: list_issue_statuses, 22 active users.

List workspace members. Approved phrasing: "Littlebird can list the members of your Linear workspace." User benefit: see who is on your team without switching to Linear. Source: list_users, 20 active users.

Read issue comments. Approved phrasing: "Littlebird can read the comments on any Linear issue." User benefit: follow the discussion on any issue without opening it in Linear. Source: list_comments, 17 active users.

Read issue labels. Approved phrasing: "Littlebird can read the issue labels in your Linear workspace." User benefit: see what labels your team uses to categorize work without opening Linear. Source: list_issue_labels, 14 active users.

WRITE / ACTION capabilities (approved phrasing, ordered by adoption):

Create or update an issue. Approved phrasing: "Littlebird can create or update an issue in Linear." User benefit: capture a new issue or change an existing one from Chat without switching to Linear. Source: save_issue, 33 active users, 2,076 calls (~63 calls/user -- automation-intensity outlier, likely agentic issue-management loops; include as approved but note the pattern). Eng sign-off recommended before using in high-volume page copy given the outlier ratio.

User benefit (summary): read across your Linear workspace from Chat -- issues, teams, projects, comments, and statuses -- and create or update issues without leaving your current work.

Approved phrasing (template, still valid): "Littlebird connects with Linear for deeper context and actions."

Do not claim: list_cycles (10 users -- below threshold), list_milestones (5 users -- too low), save_project (11 users -- below threshold), save_comment (7 users -- too low), save_milestone (7 users -- too low), create_issue_label (7 users -- too low), save_document (2 users -- too low). Do not claim any Linear behavior not listed above.

9.10 All other integrations (list only, mechanics NEEDS-VERIFICATION)
For every integration below, writers may use approved phrasing of the form "Littlebird connects with [tool] for deeper context and actions" plus a plain user benefit. The specific mechanics (what Littlebird reads, writes, or automates) are NEEDS-VERIFICATION (eng or Viktor spec) and must not be invented or published. Do not build a dedicated page until the mechanics are documented and signed off.

Project management: monday.com, Atlassian Rovo (Jira and Confluence), apple reminders
Messaging - Imessage, whatsapp, messenger, Slack (DOCS-VERIFIED status, 2026-07-27: native Slack integration is "coming soon" per the support site; a Slack MCP server is available today. Native-integration mechanics are NEEDS-VERIFICATION -- do not describe them as shipped; the MCP path may be described as available.) Why it is slow (FOUNDER-STATED, Alex on Discord #product, 2026-07-17): "slack is slow rolling EVERYONE here, we're still waiting on them," with Alex escalating inside Slack; the interim workaround he named is Pipedream ("You can use Pipe Dream"). Support context only; do not put the vendor's approval delay or the workaround on a page. Earlier status: "in progress" (Tushar, #feature-requests, 2026-05-27).
Design and collaboration: Canva, Miro, Lucid, 
Developer tools: Axiom, Cloudflare Developer Platform, PlanetScale, Honeycomb
CRM and sales: Intercom, Outreach, Close, Clarify, Day AI, Attio, Zoho CRM (availability DOCS-VERIFIED (docs.littlebird.ai/changelog, 2026-08-21): "Zoho CRM is in Add integrations."; mechanics NEEDS-VERIFICATION like the rest of this list) Category confirmed live (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17): "we already integrate with CRMs! our customer success lead uses it all the time to update our CRM"; which CRM is not stated, and per-tool mechanics stay NEEDS-VERIFICATION.
Finance: Mercury, Ramp, PayPal, Stripe
Meetings: Calendly, Fireflies, Granola, Krisp, Circleback
Marketing: Klaviyo, MailerLite, Bitly, Ahrefs, AirOps, Hubspot
Analytics: Mixpanel, Omni Analytics, PostHog, Mixpanel
Knowledge and docs: Guru, Mem, Craft, Egnyte, Google Drive
Email and calendar: Apple Calendar, Apple Reminders (Outlook has been promoted to a documented integration -- see 9.12). Apple Calendar and Apple Reminders appear as "common connections" on the support site (availability DOCS-VERIFIED, 2026-07-27) but their mechanics remain NEEDS-VERIFICATION.

NEEDS-VERIFICATION (V3): GitLab and other user-requested integrations are not confirmed and must not be claimed as supported.
Obsidian (FOUNDER-STATED, Tushar on Discord #feature-requests, 2026-09-16; support-doc guidance only; the export truncates the user's question at "When will full / proper integration with"): Tushar first asked "what's missing in the current one?" and then answered "oh yeah obsidian is a local on device app. it'll work even from ios as long as your main laptop is up." Workaround, hedged ("should"): "do you sync the underlying markdown files to github? in which case github integration should do the job" -- this composes with the GitHub read capabilities in 9.5. What "the current one" is, meaning the connection path an Obsidian user has today, is not stated, so Obsidian mechanics are NEEDS-VERIFICATION: do not write "Obsidian integration" on a page.

9.11 TickTick
PRODUCT-VERIFIED - all 12 capabilities (7 read + 5 write) personally app-tested by Nikhil, 2026-06-28. 12/12 PASS against a live TickTick account. Read, write, and action behavior is first-hand verified. The page may publish once the standard editorial review is complete. No eng sign-off gate remains on this section.

Note: TickTick calls its organizational containers "lists" -- this is the approved vocabulary for this integration. Do not use "projects" for TickTick containers. Writers must use "lists" wherever the Todoist equivalent would say "projects."

What Littlebird does with it: finds and surfaces tasks and lists, reads full task details, and can add tasks, update tasks, complete tasks, create lists, and reschedule tasks.

How it works: connect TickTick. Littlebird reads your tasks and lists for recall and surface, and can take action on your TickTick workspace.

READ capabilities (approved phrasing, ordered by test sequence 2026-06-28):

Find tasks. Approved phrasing: "Littlebird can find your tasks across TickTick." User benefit: ask in Chat and surface the tasks you need without opening TickTick to search. Source: app-tested 2026-06-28.

Find lists. Approved phrasing: "Littlebird can find your TickTick lists." User benefit: see which lists exist and what is in them without switching to TickTick. Source: app-tested 2026-06-28.

Find tasks by date. Approved phrasing: "Littlebird can find your tasks by due date." User benefit: see what is due today, this week, or on a specific date without opening TickTick. Source: app-tested 2026-06-28.

Get an overview. Approved phrasing: "Littlebird can get an overview of your tasks and lists." User benefit: see the full picture of what is on your plate, across every list, without switching to TickTick. Source: app-tested 2026-06-28.

Search across TickTick. Approved phrasing: "Littlebird can search across your TickTick." User benefit: find anything in TickTick by asking. Source: app-tested 2026-06-28.

Find completed tasks. Approved phrasing: "Littlebird can find your completed tasks." User benefit: look back at what you have finished, useful for weekly reviews or tracking what you have shipped. Source: app-tested 2026-06-28.

Read full task details. Approved phrasing: "Littlebird can read the full details of any task in TickTick." User benefit: get the description, due date, priority, and notes for any task -- pulled into context without opening TickTick. Source: app-tested 2026-06-28.

WRITE / ACTION capabilities (approved phrasing, ordered by test sequence 2026-06-28):

Capture a task. Approved phrasing: "Littlebird can add a new task to TickTick, including from a chat message, a meeting, or a passing thought." User benefit: capture tasks without breaking your flow or switching to TickTick. Source: app-tested 2026-06-28.

Update a task. Approved phrasing: "Littlebird can update an existing task in TickTick." User benefit: edit a task's details without switching to TickTick. Source: app-tested 2026-06-28.

Mark a task complete. Approved phrasing: "Littlebird can mark a task as complete in TickTick." User benefit: check off tasks without opening TickTick. Source: app-tested 2026-06-28.

Create a list. Approved phrasing: "Littlebird can create a new list in TickTick." User benefit: spin up a list from a chat request without switching to TickTick. Source: app-tested 2026-06-28.

Reschedule a task. Approved phrasing: "Littlebird can reschedule a task to a new due date in TickTick." User benefit: move a task to a different date without opening your task list. Source: app-tested 2026-06-28.

User benefit (summary): find what is on your plate, read task details in context, capture tasks in the moment, and keep your TickTick lists current -- all without switching to TickTick.

Approved phrasing (template): "Littlebird connects with TickTick for deeper context and actions."

Do not claim: any read, write, or automation capability not in the verified list above. Do not claim habit tracking, calendar view features, Pomo timer, or smart date parsing as Littlebird capabilities -- these are TickTick features not in the verified Littlebird integration set. Do not use "projects" for TickTick containers.

9.12 Outlook
DOCS-VERIFIED - mechanics documented on support.littlebird.ai/docs/outlook (2026-07-27). Not yet first-hand product-tested; treat as one tier below PRODUCT-VERIFIED. Backed by Microsoft Graph via delegated permissions only (see 9.13). One Outlook account can be connected. Works even when Outlook is not open.

What Littlebird does with it: reads your Outlook calendar and mail, manages calendar events, and drafts/organizes email. It does NOT send Outlook email.

How it works: connect Outlook in Settings > Integrations and sign in with your Microsoft account. The integration activates when Littlebird needs data beyond what is visible on screen.

CALENDAR capabilities (read + write): view schedule and upcoming events; create, edit, and delete events; cancel events and notify attendees; find available meeting times; check coworker availability.

EMAIL read capabilities: search by keyword, sender, or date across all folders or a specific folder; read full message content; view attachment info (file names, sizes, and types).

EMAIL write / organize capabilities: draft new emails, replies, and forwards (they land in your Drafts folder); move messages between folders; mark messages read or unread; flag and categorize messages.

Not supported (do not claim): sending email (drafts only -- sending stays on the user's side); downloading or adding attachments; inbox / mail-flow rules; deleting email.

Platform note: on macOS, Outlook actions are also available through Hover Quick Access (not on Windows).

User benefit: your Microsoft calendar and inbox are usable from Chat even when Outlook is closed -- read the schedule, create and move events, search the inbox, and draft replies in context.

Approved phrasing: "Connect Outlook and Littlebird works with your calendar and mail even when Outlook is closed -- read your schedule, create and edit events, search your inbox, and draft replies in context." Contrast note (DOCS-VERIFIED): unlike the Gmail + Google Calendar pairing, Outlook can move, flag, and categorize mail but cannot send; Gmail can send.

Do not claim: any behavior not listed above, or any data handling that contradicts section 10.

9.13 Microsoft 365 (admin setup)
DOCS-VERIFIED - support.littlebird.ai/docs/microsoft-365 (2026-07-27). Outlook (9.12) connects through Microsoft Graph. For organizations, a Global Administrator can grant org-wide admin consent. Littlebird requests 16 delegated Graph permissions (calendar read/write incl. shared, contacts read incl. shared, mail read/read-shared/read-basic, Mail.Send, mailbox settings, offline_access, and basic profile/email/User.Read) and uses ZERO application permissions -- the app acts only on behalf of the signed-in user. The Microsoft Store listing was "in progress" as of the docs snapshot. Writer note: this is IT/setup detail, not consumer-marketing copy -- use only on docs-adjacent or enterprise pages. Product-confirm items (not Bible facts, routed separately): the admin-consent redirect uses the domain app.lilbird.co; and Mail.Send is requested at the Graph layer even though the Outlook surface exposes no send.


10. Privacy and security (one canonical block)
State these plainly and never spin. This is the trust lever.

10.1 The accurate one-line frame (R2). "The app runs on your computer. The memory it builds is encrypted and stored in the AWS cloud."

10.2 Encryption. AES-256 at rest and in transit. Every connection uses TLS 1.3. AWS KMS for key management.

10.3 Storage. Cloud, hosted on AWS (US East). The data Littlebird captures is encrypted and stored in the cloud. Detail (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17): everything not excluded for privacy reasons goes into a vector database (Alex named turbopuffer, "the same one that cursor and notion use") on a hardened AWS server, under enterprise contracts with Amazon, in AWS East. Stated reasons for cloud rather than on-device: your data is available to you across devices, and "it's actually easier to keep your data secure on a hardened enterprise-grade server than it is on device." The AWS East fact is confirmed; naming the vector-database vendor on a page is a product and legal call, so keep it to support-doc context until confirmed.

10.4 Standards (R1). SOC 2 certified (independently audited). GDPR-aligned and CCPA-aligned data handling (DOCS-VERIFIED wording, 2026-07-27: the support site says "GDPR-aligned" / "CCPA-aligned," which supersedes the older "compliant" phrasing for pipeline copy). HIPAA is CONDITIONAL (DOCS-VERIFIED): Littlebird can support HIPAA only when the customer accepts a Business Associate Agreement (BAA) in-app (Settings > Data Controls) and enables HIPAA; a paid plan alone does not activate it, and protected health information must not be entered until the BAA is in effect. Do not state an unconditional "HIPAA compliant." A Cloud Security Alliance badge also appears on the site. Never write "HIPAA certified" or "GDPR certified." Only SOC 2 is "certified." (Live-site divergence flagged 2026-07-27: existing spoke Privacy sections still say "compliant" -- see the changelog copy-pass note.) Founder confirmation (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17): "SOC II Type II" (so the certification may be described as SOC 2 Type II), and HIPAA involves "architectural changes behind the hood," which is why the HIPAA option must be enabled in the app ("it's important to check that box in the app"); that matches the in-app BAA mechanic above. Alex's shorthand "HIPAA certified" in the same answer is NOT adopted: the docs-verified conditional wording is newer and more precise, and the Hard Don't stands.

10.5 Data use. Littlebird never sells your data and never trains models on your data. Neither Littlebird nor its underlying LLM providers use your data to train models (DOCS-VERIFIED, 2026-07-27: the support Privacy, FAQ, and Slack pages all state this; this upgrades the former NEEDS-VERIFICATION item at 10.9 for the no-train OUTCOME -- the contractual-mechanism wording stays soft, see 10.9). Data is used only in ways you explicitly approve. Contractual mechanism (FOUNDER-STATED, Tushar on Reddit, 2026-07-24 and 2026-08-04): Littlebird has ZDR (zero data retention) and no-training agreements with its model providers; requests do transit through those providers to be processed. Approved phrasing: "zero-data-retention agreements with our model providers." Do not invent contract specifics beyond that sentence. See 10.9.

10.6 User control. Pause context collection, exclude apps, delete data (all of it, or the last hour or day), and delete your account at any time. Observes only with your consent. Exclusion granularity (DOCS-VERIFIED, 2026-07-27): exclude specific apps, specific website domains, and whole content categories (Banking, Social Media, Shopping, Entertainment, Health; Adult content is always excluded by default). Automatic protections (DOCS-VERIFIED): password managers (1Password, Bitwarden, LastPass, and similar) are auto-detected and excluded by default; credit-card numbers and API keys are auto-redacted before storage; password fields are always ignored (see 4.4, 4.8). Data export (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17, stated three times in the thread): you can download all of your data at any time and take it with you ("You will be able to download it (you can now!!) and we'll delete it"). Approved phrasing: "download or delete all of your data at any time." See 10.11.

10.7 Independent audits. Infrastructure and controls are regularly audited and tested by third-party security firms. Trust Center at trust.littlebird.ai. Incident history (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17): "we have had zero security incidents thus far," and "If we had any security incidents, we would notify all of our users." Support-reply material with the date attached; NOT for page copy: an incident count decays the moment it is published and reads as a legal representation, so it needs founder or legal confirmation at publish time under the FOUNDER-STATED exception.

10.8 Local processing stance. For individual and consumer users, Littlebird is cloud-based. The site says the team is working to bring more processing local and that, for those who require local-only systems, Littlebird may not be the right fit today. Self-hosted deployments are available at the Enterprise tier. Honest answer to "can I keep this local": not on individual plans yet; self-hosting is available at Enterprise. Founder reasoning (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17): local models are "not there yet, unless you have a crazy powerful computer," and local-only has not been prioritized because relatively few users could run it; the stated belief is that data is more secure on hardened enterprise-grade servers than on device (see 10.3). Usable to explain the stance; do not turn it into a promise of a future local mode. Enterprise on-prem timing is flagged in Appendix A.

10.9 Resolved in v3.3 (was NEEDS-VERIFICATION V1, then partially resolved). The no-train OUTCOME is DOCS-VERIFIED (2026-07-27): the support site states neither Littlebird nor its LLM providers train on your data (see 10.5). The contractual MECHANISM is FOUNDER-STATED (Tushar on Reddit, publicly, twice: 2026-07-24 "We have ZDR (zero data retention) agreements with the vendors" and 2026-08-04 "We've ZDR (zero data retention) and no training agreements with the model providers, but the data does transit through them"). Ruling adopted in v3.3: the former do-not-publish gate lifts to the extent of the founder's own words -- "zero-data-retention agreements with model providers" is publishable with that provenance; anything more specific about contract terms stays unconfirmed. Note for writers: the provenance rule that contractual claims need founder or legal confirmation is SATISFIED here, by the founder's own dated public statements quoted above. It is not a further sign-off still outstanding.

10.10 Integration boundary (FOUNDER-STATED, Tushar on Reddit, 2026-08-04 -- an honest-tradeoff fact, state it plainly when relevant). Once data passes to a connected third-party integration, it is outside Littlebird's control: for example, if a user asks Littlebird to post content containing an API key to a public GitHub repo, that key becomes public even though Littlebird did what was asked. Tushar states Littlebird "would certainly warn you before going through with this" -- treat the warning behavior as founder-stated, not docs-verified; do not write it as a guaranteed product mechanic without product confirmation. Related mitigations that ARE established: key auto-redaction during capture (4.8, 10.6).

10.11 Ownership, portability, and wind-down (FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17). The data is yours: "this data is shared with you, it's still yours, it's not ours! we're just stewards of your data and you can delete or download it all any time and take it with you." You can download it at any time (10.6) and Littlebird deletes it on request. Alex also stated that if the company shut down, "we would delete all of your data." The download and delete-on-request facts are publishable with attribution. The wind-down promise is a legal-adjacent commitment: keep it to support context until founder or legal confirms it for page copy (FOUNDER-STATED exception, section 1 provenance note). Export path, flagged 2026-09-12 (FOUNDER-STATED, Tushar on Discord #feature-requests, 2026-09-04): asked whether there is "a way to download all the" [something; the export truncates the question], Tushar answered "we don't have a UI way but you can work with Littlebird to do it and sync them to notion or sth." Read against Alex's "you can now" download line above, this means the export of at least one content type has no one-click UI and goes through asking Littlebird. Keep the approved phrasing ("download or delete all of your data at any time") but do not describe an export button or a file format until product confirms the mechanism (Appendix A). Per-chat export is Cmd+K then copy as markdown (6.6).

Writer rule. Never hide the AWS and cloud fact. Acknowledge it, then point to the mitigations: encryption, SOC 2, deletion controls, no training, no selling, consent-based capture, Enterprise self-hosting. Founder framing for the privacy objection (FOUNDER-STATED, Alex on Reddit): "Local vs cloud matters less than whether the vendor trains on your data, how long they retain it, and whether deletion actually deletes" (r/ArtificialInteligence, 2026-08-28); trusting an assistant "really means trusting the company holding your data, and that trust burden sits on the company, not on you" (r/artificial, 2026-08-12); and the AMA comparison (2026-07-17) that screen-derived text is stored in the same kind of place as Gmail or Google Meet transcription, on a hardened server, and that there is "nothing uniquely risky about Littlebird versus, say, your Gmail getting hacked." Use these to answer the objection head-on, then point to the mitigations; never use them to imply the cloud fact does not matter.


11. Approved FAQ answers (verbatim-usable)
How does it understand my work? It pays attention to the active window (the doc, the site), listens during meetings, and can optionally connect email, calendar, and apps.
Do I need to connect all my apps? No. It works automatically by paying attention to your screen. Integrations are optional, for deeper access. Example: connect Google Calendar to help schedule meetings.
Why not just use ChatGPT? General assistants have no context. You copy and paste to catch them up, which is slow and raises privacy concerns. Littlebird already understands the work behind your request.
Is my data secure? Yes. Encrypted at rest and in transit, SOC 2 certified, GDPR-aligned and CCPA-aligned data handling, delete anytime.
Where is my data stored? Cloud, on AWS (US East), encrypted. The app runs on your computer and you control what it sees.
Do you train models or sell data? No and no. Our customers are our users, not advertisers.
What platforms? Mac and Windows, plus iOS and Android companion apps. (Windows "beta" qualifier dropped 2026-07-27, DOCS-VERIFIED.)
Student discount? Yes. Plus is $15 per month for enrolled students, first two months free, .edu email.
Can I take my data with me? Yes. Download all of it at any time, and delete it whenever you want. (FOUNDER-STATED, Alex on Reddit, 2026-07-17; see 10.6, 10.11.)
Which AI model does Littlebird use? Several. Littlebird routes each request to the third-party model its evals show performs best for the cost, and the mix changes as models improve. (FOUNDER-STATED, Alex on Reddit, 2026-07-17 and 2026-07-23; see 4.9. Do not name a model.)
Can I use Littlebird in my language? Yes for chat and meeting notes; the app's interface is English. (FOUNDER-STATED, Tushar on Discord, 2026-05-28; see 6.1, and B3 for the Meeting Notes language count.)
Can I connect a tool you don't list? If it has a public MCP server, add it as a custom integration in Settings > Integrations. (FOUNDER-STATED, Tushar on Discord, 2026-05-17 to 2026-08-24; see 6.6. Do not state a plan tier.)
Does Littlebird have its own task manager? No, by design. Connect the list you already use (Todoist, TickTick, and others) and ask Littlebird to use it. (FOUNDER-STATED, Tushar on Discord, 2026-07-22; section 9.)


12. Competitor positioning
Global rules. ChatGPT, Claude, and Microsoft Copilot are "do not aggressively market against." Win on memory, zero setup, and proactive Routines; stay respectful. Always include an honest "use the competitor when" angle. Every competitor claim needs a date and a source, because these facts decay. A comparison page header must name the correct competitor (R9). Never claim privacy superiority over a genuinely local competitor (R2).

12.1 ChatGPT (do not aggressively market against).

Approved framing: ChatGPT is a powerful general assistant with no context about your work; you supply it each time by copy and paste. Littlebird already has the context, captures meetings automatically, and is proactive through Routines.
Use ChatGPT when: you need a capable AI for general tasks, research, or a one-off creative project.
Do not say: that Littlebird beats ChatGPT at general reasoning or writing.
Context, dated (2026-08-14): a Discord user linked ChatGPT documentation for a "computer history" customization feature, and others speculated Littlebird was behind it. Alex's public responses (FOUNDER-STATED, Discord #lounge and #product, 2026-08-14): "Eh rumors of it being Littlebird are exaggerated," "Uh.. No its not?" and "Imitation is sincerest form of flattery!" Usable with attribution. Any factual claim about the ChatGPT feature itself needs its own dated source (the user's link is not one); the section 12 global rules apply.

12.2 Claude (do not aggressively market against).

Approved framing: Claude is powerful when you give it the right context (uploads, projects, prompts). Littlebird builds that context for you automatically from your screen and meetings, and is proactive.
Use Claude when: research, writing, complex reasoning, deep document analysis, coding or math.
Do not say: that Littlebird is a better model or better at reasoning.

12.3 Granola.

Approved framing: Granola is a focused, bot-free meeting notetaker. Littlebird is also bot-free, and it connects meetings to a running memory of everything else you see and do, then lets you act (draft follow-ups, recall past calls).
Use Granola when: you want a focused meeting tool with customizable templates and notes shaped by what you jot.
Context: Granola raised $125M Series C at a $1.5B valuation (March 2026); positions as privacy-first and local-first. Do not contrast on privacy superiority.

12.4 Cluely.

Approved framing: Cluely is a real-time, in-meeting assistant. Littlebird helps during meetings (Hover while transcribing) and everywhere else, with context from your whole workday, not just the call.
Use Cluely when: you want live coaching during sales calls or a tool built specifically for in-meeting performance.
Context (date and source required): the CEO admitted in March 2026 that a previously claimed $7M ARR figure was fabricated; a mid-2025 security incident was reported. Use sparingly and factually, not as an attack.

12.5 Otter.

Approved framing: Otter is a focused meeting and transcription tool that joins your call as a visible participant. Littlebird is bot-free, connects meetings to the rest of your work, and helps beyond meetings.
Use Otter when: you want a focused meeting tool with team and collaboration features.

12.6 Fathom (active; live page exists, R7).

Approved framing: Fathom is a meeting tool with a generous free plan and CRM sync, and it uses a meeting bot by default. Littlebird is bot-free, connects meetings to a running memory, and helps across your whole day.
Use Fathom when: you want fast summaries with CRM sync for sales, or team features like shared libraries and coaching scorecards.

12.7 Other competitors (context only, not yet dedicated pages).

Rewind / Limitless: acquired by Meta and shut down the Mac app on December 19, 2025. Do not frame as a current head-to-head. Target displaced users with "alternative to" framing.
Screenpipe, OpenClaw, Talat: genuinely local or open-source. Contrast on zero setup, proactive help, and managed experience, never on privacy superiority.
Microsoft Copilot (do not aggressively market against), Notion AI, Read AI, Mem, TwinMind, Fireflies: approved targets or watch items. TODO R7: confirm the November 2025 deprioritization of Fathom and Fireflies is superseded; Fireflies has no page yet.
Obsidian (context only, FOUNDER-STATED, Alex on Reddit, AMA, 2026-07-17): the founder's contrast is upkeep, not features: "Obsidian requires you to manually manage things, as far as I understand. The goal for Littlebird is to have a full second mind that you don't have to manage!" Contrast on no-manual-upkeep and passive capture. Apply the section 12 global rules: date and source on any factual claim about Obsidian, and no privacy-superiority framing.


13. Citable stats (two-class rule, R6)
Never publish an unsourced number. Internal numbers must be framed as a Littlebird user survey. Third-party numbers must be cited to the named organization. Never present an internal survey stat as an independent finding.

13.1 Littlebird user survey (frame as "in a Littlebird user survey, X% of subscribers ..."). Source: Littlebird, 2026.

1 in 2 subscribers estimate a 25% or greater boost to their daily productivity.
43% of subscribers estimate saving 3 or more hours per week.
84% estimate Littlebird made them at least 10% more productive in their daily work.
77% describe Littlebird as a human-like partner.
80% agree Littlebird reduced their anxiety about forgetting details or dropping the ball.
89% of heavy Meeting Notes users say Littlebird reduced their anxiety about dropping the ball.
Half of users say their top superpower is connecting information across different apps and conversations.

13.2 Third-party research (cite the named org). NEEDS-VERIFICATION (V2): confirm exact URL, wording, and year before publishing each.

Stanford University: 30% of remote meetings involve multitasking (2021).
Cornell University: 43% of people spend too much time jumping between apps (2021).
Cornell University: in a typical day, people spend 59 minutes looking for information trapped within tools and apps (2021).
Microsoft: 48% of employees say their work feels chaotic and fragmented (2025).
MIT: AI makes creation 37% faster (2023).
UC Irvine: every interruption costs about 23 minutes of focus (year NEEDS-VERIFICATION).
Harvard Business Review: the average professional switches between apps about 1,200 times every day (2022).
Harvard Business Review: toggling between apps costs about 4 hours every week (2022).
Asana: knowledge workers spend about 60% of their time on "work about work" (2026).


14. Customer proof
Usage rule (R8). Use only quotes explicitly marked approved. Attribute name, title, and company exactly as listed. Do not edit wording. All unmarked quotes are NEEDS-APPROVAL and must not be used.

14.1 Approved for marketing use (Michelle Dailey, VP Marketing, Checksum). Use any of these verbatim with attribution.

"All the content I produce starts with Littlebird. It sits in the background, capturing the conversations that matter, so nothing gets lost in the details of a meeting or the bottom of my inbox."
"Littlebird lets me be fully present in conversations instead of looking down at my notes."
"When you're multitasking in a meeting, things get lost. Littlebird keeps track of everything I need to do (and everything I've done), so nothing gets missed."
"Littlebird makes me twice as effective."
"ChatGPT and Claude are only as powerful as the context you give them. Littlebird already has that context."

14.2 NEEDS-APPROVAL (do not use until confirmed). Quotes attributed to Luis Amezcua (AlphaSense), Amanda Nelson (Pythoness Programmer), Matt O'Donnell (Randall Reilly), Sarah Meaney (Kitchen OS), John Girard (company uncertain), Ben Morton (Planoly), Russ Heddleston (Distill). Note: Amanda Nelson's quote uses the word "snapshots"; even once approved, do not generalize "snapshots" into a capture-mechanism claim (see 4.4, 15).

14.3 Social proof points. Real switching signal: users moving from Granola to Littlebird (Discord, June 2026). Active, engaged Discord community with founder participation. Founders also answer users publicly on Reddit: the r/littlebird founder AMA (posted 2026-07-14; Alex answered most of the thread on 2026-07-17 from the company account and his personal account, Tushar answered the rest) plus ongoing founder replies in privacy, transcription, and roadmap threads (observed June to September 2026), and answers from the company account in productivity and AI subreddits through September 2026 (on 2026-09-25 it restated the positioning against ChatGPT and Claude, see 7.5, and pointed readers to the free tier, section 5). Beta tester program (FOUNDER-STATED, Alex, AMA, 2026-07-17): "We do have a beta tester program. If you comment on Discord, we'll add you to it!" Discord (littlebird.ai/discord) is also where the team shares updates and keeps a changelog channel (Tushar, AMA, 2026-07-17). Public weekly changelog (FOUNDER-STATED, Tushar on Discord #product, 2026-08-03): support.littlebird.ai/changelog as he linked it (this bible reads docs.littlebird.ai/changelog, section 2), "it's hard to do it per version, but we've now setup a weekly changelog" (announced as coming on 2026-07-24). Citable as a trust point ("a public weekly changelog"). Beta program mechanics (Tushar on Discord #integrations): apply through the form pinned in Discord, "note that you'll have to be on a paid plan" (2026-06-16; again 2026-07-28, "if you're a paying user"); beta "lets you have early access to things" (2026-06-03). Founder participation on Discord is daily (Magpie's scrape, May to September 2026): Tushar answers most product questions and bug reports himself, Alex answers feature requests; no counts on a page without section 13 sourcing.

14.4 TODO: the Product Hunt source was referenced but not provided. Add approved Product Hunt proof points once received. Do not fabricate ratings, counts, or testimonials.


15. Hard don'ts (editor rejection criteria)
Reject a draft if it does any of the following.

Uses any banned word (section 3) or any em or en dash, or non-ASCII punctuation.
Claims Littlebird beats ChatGPT or Claude at general reasoning or writing.
States a price not in section 5, or states Pro as a flat price rather than "from $100 per month," or invents, renames, or reorders tiers away from the section 5 ladder (Basic, Plus, Power, Pro, Team, Enterprise, plus Student).
Hides or spins the AWS and cloud-storage fact, or rigs the privacy story.
Claims Littlebird stores or processes data locally, on-device, or offline, or that data "never leaves your machine." (The app runs locally; the memory is stored in the AWS cloud. R2.)
Claims privacy superiority over a genuinely local competitor (Screenpipe, OpenClaw, Talat).
Uses a STILL-GATED capture claim (section 4.4): "not pixels," "never sees incognito or private windows," or "if you can't see it, Littlebird can't either." These remain unconfirmed. (The docs-verified phrasings -- "not a screen recorder," "no video or screenshots," "not a keylogger," "designed to ignore password fields," password-manager auto-exclusion, credit-card/API-key auto-redaction -- are now APPROVED per 4.4; use those, and never the absolute "never sees your passwords.")
Writes "HIPAA certified" or "GDPR certified." Only SOC 2 is certified; the rest are compliant data handling.
Uses "reads your mind" or "digital twin," or any AVOID metaphor (section 7.7).
Presents an internal Littlebird survey stat as an independent or third-party finding, or publishes any number without its source (section 13).
Publishes a third-party stat still marked NEEDS-VERIFICATION (V2) without confirming URL, wording, and year.
Uses a customer quote that is not marked approved, or edits an approved quote, or invents attribution (section 14).
Describes how an integration works beyond what its section 9 block documents (the documented-mechanics set is Gmail, Google Calendar, Notion, Outlook, Todoist, TickTick, and the Tier-2 telemetry integrations 9.5-9.9); invents mechanics for a NEEDS-VERIFICATION integration; claims an unconfirmed integration such as GitLab; or describes the native Slack integration as shipped (it is "coming soon"; only the Slack MCP path is live). (Section 9.)
Publishes a page for the three Phase 1 integrations before eng sign-off, or builds a page for any NEEDS-VERIFICATION integration.
Names a competitor product without a date and source on any factual claim about it, or aggressively attacks ChatGPT, Claude, or Microsoft Copilot.
Publishes a comparison page whose header or table title names the wrong competitor (R9).
Promotes a supporting surface (Glance, Projects, Assistant Notes, Command Bar, MCP server, image generation) or an example use (Daily Journal) to a fifth marketing pillar, or headlines a spoke/hero as if one were a fifth feature (section 6, D3). (Meeting Prep and Quick Access are RESOLVED per 6.5 -- Meeting Prep is a Meeting Notes capability, Quick Access is Hover's invocation; describe them as such, not as standalone pillars.)
Claims accurate speaker attribution or interactive task management (current known limitations; NEEDS-VERIFICATION).
Names a specific third-party AI model as "the" Littlebird model, promises a model on a plan, or publishes routing or usage economics (margins, break-even, cost per user) (4.9, 5.1).
Publishes an incident count, a wind-down promise, or the vector-database vendor name in page copy without founder or legal confirmation (10.3, 10.7, 10.11); or writes "never captures a key" (4.4).
Lists "web" as a platform or describes web-app capabilities (4.5); claims a voice conversation mode capability beyond "reported live, product-confirm," or spoken output as available below Pro (6.1); writes that a Routine can use a local MCP server or any on-device integration (6.3); describes a native task manager (section 9); states a plan tier for custom MCP connections (6.6); describes an export button or file format (10.11); or claims local MCP servers, Canvas, or Android on-phone capture as shipped (Appendix A).
Opens with a feature instead of a user pain (section 3).
Sounds generic or templated, or could describe any AI tool. It must be specifically Littlebird, traceable to a section here.


Appendix A. Open items register
TODOs (founder, eng, or product confirmation needed):

D2 / 4.4: PARTIALLY RESOLVED 2026-07-27 (DOCS-VERIFIED). Approved: not-a-screen-recorder, no video/screenshots, not-a-keylogger, ignores-password-fields, password-manager auto-exclusion, card/API-key redaction. Still gated (unconfirmed on docs): "not pixels," incognito/private-window exclusion, "if you can't see it, Littlebird can't either."
6.5: RESOLVED 2026-07-27 (DOCS-VERIFIED). Meeting Prep = a Meeting Notes capability (button on event cards); Quick Access = Hover's invocation (same surface; Hover was named Hummingbird until the 2026-08-28 rename). See 6.5.
9.1 Gmail: CLOSED - product-verified by Nikhil, 2026-06-27. No remaining gate.
9.2 Google Calendar: CLOSED - product-verified by Nikhil, 2026-06-27. No remaining gate.
9.3 Notion: CLOSED - product-verified by Nikhil, 2026-06-25. No remaining gate.
9.4 Todoist: CLOSED - product-verified by Nikhil, 2026-06-28. All 11 capabilities (6 read + 5 write) personally app-tested 11/11 PASS against a live account. Telemetry citations remain as original evidence basis. No remaining gate.
9.11 TickTick: CLOSED - product-verified by Nikhil, 2026-06-28. All 12 capabilities (7 read + 5 write) personally app-tested 12/12 PASS against a live account. No remaining gate. Promoted from Section 9.10 catch-all list.
R4 / 3: confirm no live littlebird.com.
R7 / 12.7: confirm Fathom and Fireflies November 2025 deprioritization is superseded.
14.4: obtain and add approved Product Hunt proof points.
2: assign per-section owners and monthly re-check dates.

FOUNDER-STATED roadmap (from public Reddit and Discord answers; not publishable as shipped, usable only as "planned, per the team" with the date):

- A browser extension that can automatically announce/send a message in Google Meet when transcribing (Tushar, Reddit, 2026-08-04).
- Speaker diarization / speaker separation in active development ("speaker separation within the next few weeks," Alex on Discord, 2026-07-17; "we're working on diarization now," Tushar, Reddit, 2026-08-04; see 6.2 -- still do-not-claim).
- A significantly larger global Assistant Notes space ("it's being increased," Tushar on Discord, 2026-06-03; "with an upcoming update," Tushar, Reddit, 2026-07-18); automatic writing-style learning ("we're working on doing this automatically too," Tushar on Discord, 2026-05-15).
- On-prem deployments for large enterprise customers "later this year" (Alex, 2026-07-17). FLAG, not integrated: the live pricing page already lists "self-hosted deployments" under Enterprise (section 5, 10.8). Either the pricing page describes an offer not yet delivered or Alex meant something narrower; confirm with the team before an enterprise page says "available now" or "coming." Sections 5 and 10.8 left as they were.
- Personal world model: research into keeping stale facts out of answers, "especially for power and pro users, soon" (Alex, 2026-07-17; see 4.10).
- File system access "in the next few weeks" (Alex, 2026-07-17).
- Local (stdio) MCP servers: "within the next 2 weeks" (Alex on Discord, 2026-06-08), "that support will come this month" (Tushar on Discord, 2026-06-08), "in the next week or so" (Alex, Reddit AMA, 2026-07-17), "in beta rn, should be released soon" (Tushar on Discord, 2026-08-03; see 6.6). Latest status: beta.
- Taking actions on the internet (browser actions): in work, gated on prompt-injection security testing before launch (Alex, 2026-07-17).
- Inbox / notification center: planned (Alex, 2026-07-17); monitoring your inbox or texts and alerting you when action is needed, "Coming soon!" (Alex on Discord, 2026-08-14).
- Team features: "we're working on it now" (Alex, 2026-07-17); an experimental feature the team can enable for team-plan users (Tushar on Discord, 2026-06-17); the Team tier in section 5 is what is sold today. Since then, Shared Projects (2026-08-28) and team analytics (2026-07-24 and 2026-07-31) are DOCS-VERIFIED in 6.6; this entry is history.
- Voice output: "next week or two" (Alex, 2026-07-17); a voice conversation mode was reported live by Alex on Discord on 2026-09-03 ("this is live!"), see 6.1; product-confirm before page copy. Voice INPUT (dictation) is already DOCS-VERIFIED in 6.1. Text-to-speech "already available for pro users" (u/Littlebird_Alex, Littlebird company account, r/littlebird, 2026-09-23; see 6.1): spoken output is founder-stated live on Pro; the surfaces are unconfirmed.
- AppleScript support: "we absolutely want to support, and we will soon" (Alex, 2026-07-17).
- Hover on Windows: no ETA, "within a month or two max" (Alex, 2026-07-17, when Hover was still named Hummingbird; see 6.4).
- Android on-phone capture: shipped June 2026, removed after Google app-review problems, "We will reintroduce it at some point" (Alex on Discord, 2026-09-09; see 4.5).
- Chat with Littlebird from messaging platforms: a Telegram bot, "yes. it's coming!" and "idk when though... hopefully in the next month or so" (Alex on Discord, 2026-05-29); reading WhatsApp data, "no eta unfortunately rn, but it's in the roadmap" (Tushar on Discord, 2026-06-08).
- Integrations named as in progress on Discord: Apple Mail, "it's being worked on though" (Tushar, 2026-05-27); Dropbox, "in progress" (Tushar, 2026-06-09); write access to Google Docs, "yes" to "will LB have write access to docs?" (Tushar, 2026-05-28), while a Routine "can't write to sheets" as of 2026-07-03; native Slack, waiting on Slack (Alex, 2026-07-17; 9.10). Apple Reminders, promised for June 2026 on Discord, is DOCS-VERIFIED as available (9.10).
- Automations through Zapier, Make, n8n, or webhooks: "we are working on this!" (Alex on Discord, 2026-07-17).
- An email address you can forward mail to in order to start a project: "not yet" (Tushar on Discord, 2026-08-26), "No but it's planned" (Alex on Discord, 2026-09-03).
- Routines: running more than once a day or with multiple schedules, "in the works" (Alex on Discord, 2026-06-08); duplicating a Routine and "more flexibility over the schedule soon" (Tushar, 2026-08-01); more triggers, so a prep could run before a matching meeting (Tushar, 2026-09-09); Routines UI improvements (Tushar, 2026-07-27); a mode beyond Max or a customizable Max, under discussion (Tushar, 2026-07-08).
- Tasks: a view in Glance or the sidebar showing synced todos from your integrations, "in works" (Tushar on Discord, 2026-07-22); a way to push meeting action items to your task app or check them off in one place, "we'll do sth around this" (2026-07-22). No native task manager is planned (section 9).
- Canvas: dashboards and visualizations in chat or Routines, "not fully rolled out yet" (Tushar on Discord, 2026-08-07; 6.6).
- Chat import (bringing conversations from other tools in as chats or memory): "we'll likely build sth," no promise (Tushar on Discord, 2026-06-16); meeting-note import already exists (6.2).
- Mobile lock-screen and home-screen widgets, "coming very soon!!!" (Alex on Discord, 2026-05-28).
- Health integrations, HIPAA-conscious: "yes. planning on health integration" (Alex on Discord, 2026-05-28); pair with 10.4 if it ever ships.
- Always-on, proactive behavior: "we're working on a few building blocks towards this right now" (Tushar on Discord, 2026-06-03).
- SKILLS.md support: "yes" to "is it on the backlog?" (Tushar on Discord, 2026-07-25).
- Interface localization: no interface-language setting as of 2026-05-28 (Tushar on Discord; 6.1). Not promised; logged so no page claims a localized UI.
- A Settings toggle for the collapsed sidebar: SHIPPED per Tushar on Discord, 2026-09-24 ("released now" in the #feature-requests thread where he had promised it "in the next release" on 2026-09-17; see 6.1). Kept here for history; not in the changelog yet, so the Settings label is unconfirmed.
- Routines using on-device integrations: "routines don't yet support on device integrations, we're working on it" (Tushar on Discord #integrations, 2026-09-24; see 6.3).
- Public APIs: "we do have APIs on the roadmap too" (Tushar on Discord #lounge, 2026-09-13); no timing given. Later in the same thread, after the user described the delivery form they wanted (the form itself is not in the export): "makes sense thanks, I'll try to prfioritize this and let you know" (Tushar, 2026-09-13). Until then the founder-named paths are the MCP server and email delivery, with n8n or Zapier reading that email as the user's own workaround (see 6.6). Do not write "API" as a capability.
Timing note: the Reddit items were dated in weeks from 2026-07-17 and the Discord items run from May 2026. As of 2026-09-27 any of them may have shipped; a roadmap entry here never becomes a shipped claim without docs or product confirmation. Precedents: per-project file uploads ("very soon," Tushar on Discord, 2026-06-18; "coming," Alex, 2026-07-17) were DOCS-VERIFIED live by 2026-07-27 (6.6); Apple Reminders, promised for June on Discord, is on the support site's connections list (9.10); Glance, described as "a home with quick access to different things" on 2026-06-03, is DOCS-VERIFIED (6.6); the mid-tier plan Alex said was "coming" on 2026-06-08 is the Power tier (section 5, v3.2). The sidebar toggle promised on 2026-09-17 was reported released on 2026-09-24 (6.1).

NEEDS-VERIFICATION (external facts):

V1 / 10.9: RESOLVED 2026-08-30 (FOUNDER-STATED, v3.3). No-train outcome was DOCS-VERIFIED 2026-07-27; the contractual mechanism (ZDR agreements with model providers) is publicly founder-stated twice on Reddit (2026-07-24, 2026-08-04). See 10.5, 10.9 for the adopted ruling.
V2 / 13.2: third-party stat URLs, wording, and years.
V3 / 9.4: GitLab and other unconfirmed integrations.
6.2 / 15.18: current state of speaker diarization and action-item interactivity. (Docs 2026-07-27 do NOT resolve speaker attribution -- still do-not-claim.)
B4 / 5.1: RESOLVED 2026-07-30 (pricing-page confirmed, live littlebird.ai/pricing fetch). Power is a real tier between Plus and Pro and is now in the section 5 block; MCP access is stated as a Power-and-above capability (5.1, 6.6). No remaining gate.
B6 / 4.5, 11 (NEW 2026-07-30): Windows "beta" -- surfaces diverge. The live pricing page's download CTA still labels Windows "BETA" (fetched 2026-07-30), while the support docs site and Bible 4.5 dropped the qualifier on 2026-07-27. Confirm the actual status with the team before anyone writes "beta" or argues about it. Until then 4.5 stands as written (no beta label); do not add "beta" to copy on the strength of the pricing-page CTA alone.
B3 / 6.2, 5: languages divergence -- docs say Meeting Notes supports "25+ languages," pricing page says "10+." Kept at 10+; reconcile before publishing 25+.
9.10 / 9.12: Apple Calendar and Apple Reminders availability is DOCS-VERIFIED but mechanics are NEEDS-VERIFICATION; native Slack integration mechanics are NEEDS-VERIFICATION (only the Slack MCP path is live).
4.5 / Android context collection (NEW 2026-09-20, CONTRADICTION FLAGGED, not integrated): the changelog entry of 2026-07-24 says "[Android] Context collection setup now explains what the Accessibility Service reads and why, with one control to start or pause collection." 4.5 says the mobile apps do not capture activity from your phone screen (DOCS-VERIFIED, support docs, 2026-07-27, three days after that entry). The newest statement on record is Alex on Discord #mobile, 2026-09-09: "On Android we had to remove it because Google was giving us problems on app reviews. We will reintroduce it at some point". A changelog entry is a floor on what shipped on its date, not proof it is still live, so 4.5 stands as written. Confirm the current Android state with the team before writing about phone capture in either direction.
6.6 / Artifacts plan gate (NEW 2026-09-20): the changelog documents Artifacts in its entries of 2026-07-24 to 2026-08-28 without naming a plan. The only gate on record is Tushar on Reddit, 2026-07-30 (Pro plans). Confirm the current gate before any plan-specific copy.
6.1 / Ultra mode (NEW 2026-09-20): named in the 2026-08-28 changelog entry "for pro users" with no description of what it does. Confirm the behavior and the gate before page copy.
9 / 9.12 multiple accounts (NEW 2026-09-20): the 2026-08-21 changelog entry names Gmail, calendars, Slack, Notion, and Linear as multi-account examples and does not name Outlook; 9.12 still says one Outlook account can be connected. Confirm whether Outlook takes a second account.
6.1 / 6.4: RESOLVED 2026-09-12 in favor of Max. Founders use "max" on Discord (Alex 2026-05-28, Tushar 2026-07-08 and 2026-07-10) and the docs say "Max mode" (2026-07-27); "research mode" is Alex's informal name for the same mode (2026-07-17, 2026-07-26). Write Quick, Default, Max, plus Ultra for Pro users (DOCS-VERIFIED, 2026-08-28). One product confirm of the full mode list before a page explains the modes.
4.5: RESOLVED 2026-09-12 (FOUNDER-STATED, Discord). The 2026-07-17 AMA answer "on android yes, on IOS it's tricky! apple doesn't really allow it" was about on-phone capture: Alex on Discord #mobile, 2026-06-09, "android is coming this week! it's not possible to do this on IOS bc of apple's policies," and 2026-09-09, "On Android we had to remove it because Google was giving us problems on app reviews. We will reintroduce it at some point." 4.5 stands as written (mobile apps do not capture phone activity today); Android capture is a roadmap item above.
4.5 (NEW 2026-09-12): the web app at app.littlebird.ai exists (Tushar on Discord, June to August 2026) and shows your chats; its feature set is undocumented. Do not list "web" as a platform until the docs do.
6.1 (NEW 2026-09-12): voice conversation mode, reported live by Alex on Discord on 2026-09-03 ("this is live!" to a request for briefings read aloud with spoken replies, on iOS). Confirm what shipped (read-aloud, hands-free back-and-forth, platforms) before page copy. Added 2026-09-27: text-to-speech "already available for pro users" (u/Littlebird_Alex, Littlebird company account, r/littlebird, 2026-09-23). Confirm which surfaces (mobile Read aloud, desktop, voice conversation) carry the Pro gate before any plan-specific copy.
6.2 (NEW 2026-09-12): per-meeting-type structure instructions in Settings > Meetings (Tushar on Discord, 2026-09-10). Confirm the UI before describing it as a template feature.
6.6 (NEW 2026-09-12): plan gate for custom MCP connections (Littlebird as MCP client). A 2026-08-24 Discord answer to a Plus user suggests Add custom is on Plus; the question is truncated. Confirm before any tier claim; the pricing page's "access to MCP" line is the Littlebird MCP server.
6.6 / 8.5 (NEW 2026-09-12): a sensitive-information guardrail blocked medical corrections to Assistant Notes (user report, acknowledged by Alex on Discord on 2026-09-03 as something to fix). Confirm the intended behavior before health-persona copy mentions Assistant Notes.
10.11 (NEW 2026-09-12): the export mechanism. "download all of your data at any time" (Alex, 2026-07-17) against "we don't have a UI way" for at least one content type (Tushar on Discord, 2026-09-04, question truncated). Confirm the actual export path before describing it.
6.3 / 6.6 (NEW 2026-09-27): an unrecovered rename. In the r/littlebird thread "Daily Journal removed, artifacts removed, no changelog since August", the company account replied "yes we just changed the name!" (2026-09-23) to a comment the export does not carry. If a surface this bible names (Artifacts, the Daily Journal example, or another) has been renamed, the changelog will carry the new name and this bible follows it (section 2); until then keep the names as written and confirm with the team before copy leans on either.
6.3 (NEW 2026-09-27): Routines and on-device integrations. Tushar: "routines don't yet support on device integrations, we're working on it" (Discord #integrations, 2026-09-24). Which integrations are on-device (local MCP servers, Apple apps, anything else) is not stated; confirm before a Routines page names an integration a Routine can use.
6.1 (NEW 2026-10-05): the font option in Settings > Appearance. Tushar: "there should be an option in settings -> appearance" (Discord #feature-requests, 2026-10-04), answering a request the export truncates at "one font". Confirm what the Appearance section controls (font size, typeface, or something else) before any page names the control.
Live-site copy pass (B5, 2026-07-27; extended 2026-07-30): spoke Privacy sections say "compliant"; Bible 10.4 now uses "aligned" (GDPR/CCPA) and HIPAA-conditional-on-BAA. Existing pages diverge and need a copy pass. Added 2026-07-30: the live pricing page's own FAQ says "GDPR and CCPA compliant" -- the same B5 divergence, one more surface for the copy pass.

Production bugs to fix on the live site (report, not a bible fact):

The live Littlebird vs Otter and Littlebird vs Fathom pages both title their feature table "Littlebird vs. Cluely." Fix the headers.
The live Littlebird vs Fathom page duplicates the bullet "High-quality meeting notes that become part of a bigger memory." Remove the duplicate.
