The Littlebird Bible (v3)
Single source of truth for the SEO and AEO content pipeline. Writer subagents draft pages from this. The editor subagent enforces voice and rejects hallucinations using this. A human approves from a queue. Treat every fact here as the only authoritative version. If a claim is not in this bible, it cannot go on a page.

Status: v3, built June 23, 2026, from Bible v2 plus the ingested source library (Content Style Guide, Brand Guidelines, Positioning and Messaging, Marketing Personas, Day-in-the-life Use Cases, Stats and Metrics, Launch Tiers, Competitive Tracker, the six live comparison pages, Customer Quotes, Discord). Founder and Viktor confirmations noted inline. Open items are marked TODO or NEEDS-VERIFICATION.


1. How to use this bible (read first, subagents)
Cite by section. Every factual sentence you write must trace to a numbered section here. If you cannot point to the section, do not write the claim.
Atomic facts only. Use the short declarative statements in this bible. Do not embellish a fact into something stronger than written.
Approved phrasing shows the REGISTER and the verified capability, not a word ceiling. Where a section gives "approved phrasing," you may reframe and compose the verified capabilities in the v3 voice (section 3): lead with a concrete moment and the ambient-capture thesis. You may never invent a capability, assert a stronger absolute than is written, or describe a mechanic not documented here. In short: reframe the wording freely, never inflate the claim.
Composed claims. A claim that combines two VERIFIED capabilities (for example, read a Plaud transcript, then create a Notion page) is allowed. It is not a new mechanic. It is fact-checkable as the conjunction of its parts: PASS only if BOTH underlying capabilities are individually verified in this bible, and never compose with an unverified tool.
Never invent. No invented features, integrations, mechanics, stats, prices, quotes, or customer names. A gap is not an invitation to fill it.
Defer to a human (route to the approval queue with a flag, do not publish) when:
a claim depends on an item marked TODO or NEEDS-VERIFICATION,
you are tempted to state how an integration works beyond Gmail, Google Calendar, or Notion,
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
littlebird.ai/pricing; Viktor
June 17, 2026
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
Capitalize feature names as proper nouns: Chat, Meeting Notes, Routines, Hummingbird. Lowercase when used as a benefit or countable, for example "unlimited meeting notes."
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

4.4 Capture mechanism (GATED, D2). Approved phrasing, writers may use this or weaker: "Littlebird reads the text and elements of your active window via macOS accessibility permissions." Also approved: "screenreading," "reads the text on your screen," "pays attention to the active window."

NOT YET APPROVED, do not publish (PENDING ENG SIGN-OFF): "never takes screenshots," "not pixels," "not a screen recorder," "never sees your passwords," "never sees incognito or private windows," "if you can't see it, Littlebird can't either." These appear in internal marketing docs and a customer quote ("snapshots") but are not eng-confirmed and are not on the live site. See section 15.
TODO (eng, Alex or Tushar): confirm whether there is any visual or pixel capture, and whether the passwords and incognito exclusions can be stated. When signed off, move approved items here and update section 15.

4.5 Platforms. Mac and Windows (Windows in beta). Companion apps on iOS and Android for asking questions away from your desk. The core product is desktop.

4.6 Controls. The app requires user-granted macOS accessibility permissions on Mac. You decide if it runs at startup. You can pause context collection, exclude apps, and delete your data at any time. Nothing is collected without your permission.

4.7 Company facts (citable). Littlebird raised an $11M seed round (March 2026). Littlebird launched on Product Hunt (March 2026). Co-founder: Alex. Lead engineer: Tushar.


5. Pricing (one canonical block, R3)
All figures confirmed against littlebird.ai/pricing and Viktor on June 17, 2026. Safe to publish exactly as written. Never publish a price not in this block.

Basic: $0. Full context from day one. Limited daily chats, limited active routines, limited meeting notes, meeting notes in 10+ languages, web search, mobile chat, connect calendar and email, cross-app search, community support.
Plus: $17 per month billed annually ($204 per year up front), or $20 per month billed monthly. 14-day free trial. Adds advanced intelligence in chat, enhanced memory and personalization, more daily chats and routines, unlimited meeting notes, image generation, max intelligence for complex tasks and deep research, priority support.
Pro: from $100 per month. Choose 5x or 12x more usage than Plus. Auto-detect language in meeting notes, premium image generation, higher max-intelligence limits, early access to new features.
Team: from $17 per month per seat. Team seat management plus Plus-level capabilities.
Enterprise: custom pricing. SSO and centralized user management, self-hosted deployments, custom security and data controls, dedicated account manager, custom contract and invoicing.
Student: $15 per month for actively enrolled students. First two months free. Apply with a .edu email.

Writer rules. Pro is always "from $100 per month," never a flat $100. For Plus, show both the annual ($17) and monthly ($20) figures, or use the annual rate with the "billed annually" qualifier. There is no mid-tier between Plus and Pro; do not imply one exists even though users have requested it.


6. The four features
Exactly four canonical features. Do not invent a fifth (D3).

6.1 Chat.

What it is: your AI with the full picture.
What it does: ask questions and create content without catching it up, because it already knows your work.
Approved one-liner: "Chat with everything you have seen."
Do not claim: that it beats ChatGPT or Claude at general reasoning or writing (see 12, 15).

6.2 Meeting Notes.

What it is: notes that write themselves.
What it does: transcribes and summarizes your meetings so you stay present. No bot joins the call. Works for any audio or video playing on your computer, not only live calls.
Approved one-liner: "Focus on the conversation. The notes take care of themselves."
Do not claim: accurate speaker attribution or speaker diarization (users report this is imperfect; NEEDS-VERIFICATION on current state).

6.3 Routines.

What it is: insights from your real work.
What it does: delivers proactive, personalized updates on your schedule, for example a morning briefing or a weekly project recap. Auto-pause is a real setting.
Example use case: Littlebird can function as a daily journal through a Routine. "Daily journal" is an example use of Routines, not a separate feature (D3).
Approved one-liner: "Proactive insights, on your schedule."

6.4 Hummingbird.

What it is: Littlebird wherever you are working.
What it does: open Littlebird over whatever you are doing (double-tap Option), ask, and keep going without breaking flow.
Platform note: currently Mac-only.
Approved one-liner: "Get answers without breaking your flow."

6.5 Candidate features, pending product confirmation (do not promote to canonical, do not publish as features).

Meeting Prep ("Prep for meeting"): appears as a named action across use-case material, likely under Meeting Notes. NEEDS-VERIFICATION (product): is it a named feature or a capability of Meeting Notes?
Quick Access: appears on the Cluely comparison page for the double-tap-Option behavior that this bible attributes to Hummingbird. NEEDS-VERIFICATION (product): is Quick Access the same surface as Hummingbird, or distinct? Until resolved, writers use "Hummingbird" and do not use "Quick Access."


7. Positioning and messaging
7.1 Positioning statement (canonical). For busy professionals who constantly context-switch across meetings, docs, and messages, Littlebird is a personal AI assistant that already understands your work without you having to explain it. Unlike generic AI chatbots and single-purpose AI tools, Littlebird pays attention to your screen and meetings to build a private memory of your work, so every answer, draft, and plan is grounded in what you are actually doing.

7.2 Canonical hero lines (D4). "Remember everything." "AI that remembers every doc, meeting, and decision." "Littlebird pays attention."

7.3 Value props.

No cold start. It already has the context, so you skip the explaining.
Zero setup. Works the moment you install it. No integrations required.
Cross-app memory. Connects your apps, meetings, and conversations into one searchable memory.
Proactive, not just reactive. Routines surface what matters before you ask.

7.4 Messaging pillars (need, benefit).

Effortless recall: never lose track of anything you have seen.
Instant creation: go from a blank page to a strong first draft in seconds, grounded in your real work.
Complete clarity: Littlebird connects the dots across your work so insights do not slip through the cracks.
Stay present: be in the meeting, not buried in notes.

7.5 Signature differentiator (use often). A general AI is a brilliant stranger you must re-brief every time. Littlebird is the colleague who was already in the room. Strongest proof point: meetings. ChatGPT can only summarize a transcript if you paste one in. Littlebird captured it automatically and it is already in your memory.

7.6 Allowed metaphors (D4): "second brain," "the colleague who was already in the room," "already knows your work." 7.7 AVOID metaphors (D4): "reads your mind" (overclaim and privacy tension). "digital twin" (competitors own this term; see 12).


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
Littlebird supports hundreds of integrations. They are optional. Littlebird works automatically by paying attention to your screen; connecting an app gives deeper access and lets Littlebird take actions. Users browse the full list in Settings > Integrations.

Phase 1 build rule. Build integration pages only for the three fully documented integrations below, and only after eng signs off on their read plus write behavior. Do not build pages for any integration whose mechanics are still NEEDS-VERIFICATION. Do not invent mechanics for any integration (V3).

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
Messaging - Imessage, whatsapp, messenger, 
Design and collaboration: Canva, Miro, Lucid, 
Developer tools: Axiom, Cloudflare Developer Platform, PlanetScale, Honeycomb
CRM and sales: Intercom, Outreach, Close, Clarify, Day AI, Attio
Finance: Mercury, Ramp, PayPal, Stripe
Meetings: Calendly, Fireflies, Granola, Krisp, Circleback
Marketing: Klaviyo, MailerLite, Bitly, Ahrefs, AirOps, Hubspot
Analytics: Mixpanel, Omni Analytics, PostHog, Mixpanel
Knowledge and docs: Guru, Mem, Craft, Egnyte, Google Drive
Email and calendar: Outlook, Apple Calendar, Apple Reminders

NEEDS-VERIFICATION (V3): GitLab and other user-requested integrations are not confirmed and must not be claimed as supported.

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


10. Privacy and security (one canonical block)
State these plainly and never spin. This is the trust lever.

10.1 The accurate one-line frame (R2). "The app runs on your computer. The memory it builds is encrypted and stored in the AWS cloud."

10.2 Encryption. AES-256 at rest and in transit. Every connection uses TLS 1.3. AWS KMS for key management.

10.3 Storage. Cloud, hosted on AWS (US East). The data Littlebird captures is encrypted and stored in the cloud.

10.4 Standards (R1). SOC 2 certified (independently audited). GDPR, CCPA, and HIPAA: compliant data handling policies. A Cloud Security Alliance badge also appears on the site. Never write "HIPAA certified" or "GDPR certified." Only SOC 2 is "certified."

10.5 Data use. Littlebird never sells your data and never trains models on your data. Data is used only in ways you explicitly approve.

10.6 User control. Pause context collection, exclude apps, delete data (all of it, or the last hour or day), and delete your account at any time. Observes only with your consent.

10.7 Independent audits. Infrastructure and controls are regularly audited and tested by third-party security firms. Trust Center at trust.littlebird.ai.

10.8 Local processing stance. For individual and consumer users, Littlebird is cloud-based. The site says the team is working to bring more processing local and that, for those who require local-only systems, Littlebird may not be the right fit today. Self-hosted deployments are available at the Enterprise tier. Honest answer to "can I keep this local": not on individual plans yet; self-hosting is available at Enterprise.

10.9 NEEDS-VERIFICATION (V1): the claim that Littlebird has enterprise agreements with LLM providers so they do not retain or train on user data is not yet confirmed. Do not publish until verified.

Writer rule. Never hide the AWS and cloud fact. Acknowledge it, then point to the mitigations: encryption, SOC 2, deletion controls, no training, no selling, consent-based capture, Enterprise self-hosting.


11. Approved FAQ answers (verbatim-usable)
How does it understand my work? It pays attention to the active window (the doc, the site), listens during meetings, and can optionally connect email, calendar, and apps.
Do I need to connect all my apps? No. It works automatically by paying attention to your screen. Integrations are optional, for deeper access. Example: connect Google Calendar to help schedule meetings.
Why not just use ChatGPT? General assistants have no context. You copy and paste to catch them up, which is slow and raises privacy concerns. Littlebird already understands the work behind your request.
Is my data secure? Yes. Encrypted at rest and in transit, SOC 2 certified, GDPR and CCPA compliant, delete anytime.
Where is my data stored? Cloud, on AWS (US East), encrypted. The app runs on your computer and you control what it sees.
Do you train models or sell data? No and no. Our customers are our users, not advertisers.
What platforms? Mac and Windows (Windows beta), plus iOS and Android companion apps.
Student discount? Yes. Plus is $15 per month for enrolled students, first two months free, .edu email.


12. Competitor positioning
Global rules. ChatGPT, Claude, and Microsoft Copilot are "do not aggressively market against." Win on memory, zero setup, and proactive Routines; stay respectful. Always include an honest "use the competitor when" angle. Every competitor claim needs a date and a source, because these facts decay. A comparison page header must name the correct competitor (R9). Never claim privacy superiority over a genuinely local competitor (R2).

12.1 ChatGPT (do not aggressively market against).

Approved framing: ChatGPT is a powerful general assistant with no context about your work; you supply it each time by copy and paste. Littlebird already has the context, captures meetings automatically, and is proactive through Routines.
Use ChatGPT when: you need a capable AI for general tasks, research, or a one-off creative project.
Do not say: that Littlebird beats ChatGPT at general reasoning or writing.

12.2 Claude (do not aggressively market against).

Approved framing: Claude is powerful when you give it the right context (uploads, projects, prompts). Littlebird builds that context for you automatically from your screen and meetings, and is proactive.
Use Claude when: research, writing, complex reasoning, deep document analysis, coding or math.
Do not say: that Littlebird is a better model or better at reasoning.

12.3 Granola.

Approved framing: Granola is a focused, bot-free meeting notetaker. Littlebird is also bot-free, and it connects meetings to a running memory of everything else you see and do, then lets you act (draft follow-ups, recall past calls).
Use Granola when: you want a focused meeting tool with customizable templates and notes shaped by what you jot.
Context: Granola raised $125M Series C at a $1.5B valuation (March 2026); positions as privacy-first and local-first. Do not contrast on privacy superiority.

12.4 Cluely.

Approved framing: Cluely is a real-time, in-meeting assistant. Littlebird helps during meetings (Hummingbird while transcribing) and everywhere else, with context from your whole workday, not just the call.
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

14.3 Social proof points. Real switching signal: users moving from Granola to Littlebird (Discord, June 2026). Active, engaged Discord community with founder participation.

14.4 TODO: the Product Hunt source was referenced but not provided. Add approved Product Hunt proof points once received. Do not fabricate ratings, counts, or testimonials.


15. Hard don'ts (editor rejection criteria)
Reject a draft if it does any of the following.

Uses any banned word (section 3) or any em or en dash, or non-ASCII punctuation.
Claims Littlebird beats ChatGPT or Claude at general reasoning or writing.
States a price not in section 5, or states Pro as a flat price rather than "from $100 per month," or implies a mid-tier between Plus and Pro.
Hides or spins the AWS and cloud-storage fact, or rigs the privacy story.
Claims Littlebird stores or processes data locally, on-device, or offline, or that data "never leaves your machine." (The app runs locally; the memory is stored in the AWS cloud. R2.)
Claims privacy superiority over a genuinely local competitor (Screenpipe, OpenClaw, Talat).
Uses any NOT-YET-APPROVED capture claim (section 4.4): "never takes screenshots," "not pixels," "not a screen recorder," "never sees passwords," "never sees incognito." PENDING ENG SIGN-OFF.
Writes "HIPAA certified" or "GDPR certified." Only SOC 2 is certified; the rest are compliant data handling.
Uses "reads your mind" or "digital twin," or any AVOID metaphor (section 7.7).
Presents an internal Littlebird survey stat as an independent or third-party finding, or publishes any number without its source (section 13).
Publishes a third-party stat still marked NEEDS-VERIFICATION (V2) without confirming URL, wording, and year.
Uses a customer quote that is not marked approved, or edits an approved quote, or invents attribution (section 14).
Describes how any integration works beyond Gmail, Google Calendar, and Notion, or claims an unconfirmed integration such as GitLab (section 9).
Publishes a page for the three Phase 1 integrations before eng sign-off, or builds a page for any NEEDS-VERIFICATION integration.
Names a competitor product without a date and source on any factual claim about it, or aggressively attacks ChatGPT, Claude, or Microsoft Copilot.
Publishes a comparison page whose header or table title names the wrong competitor (R9).
Names a fifth feature, or treats Daily Journal, Meeting Prep, or Quick Access as a confirmed feature (section 6).
Claims accurate speaker attribution or interactive task management (current known limitations; NEEDS-VERIFICATION).
Opens with a feature instead of a user pain (section 3).
Sounds generic or templated, or could describe any AI tool. It must be specifically Littlebird, traceable to a section here.


Appendix A. Open items register
TODOs (founder, eng, or product confirmation needed):

D2 / 4.4: eng sign-off on capture-mechanism absolute claims (screenshots, pixels, passwords, incognito).
6.5: product confirmation on Meeting Prep and Quick Access.
9.1 Gmail: CLOSED - product-verified by Nikhil, 2026-06-27. No remaining gate.
9.2 Google Calendar: CLOSED - product-verified by Nikhil, 2026-06-27. No remaining gate.
9.3 Notion: CLOSED - product-verified by Nikhil, 2026-06-25. No remaining gate.
9.4 Todoist: CLOSED - product-verified by Nikhil, 2026-06-28. All 11 capabilities (6 read + 5 write) personally app-tested 11/11 PASS against a live account. Telemetry citations remain as original evidence basis. No remaining gate.
9.11 TickTick: CLOSED - product-verified by Nikhil, 2026-06-28. All 12 capabilities (7 read + 5 write) personally app-tested 12/12 PASS against a live account. No remaining gate. Promoted from Section 9.10 catch-all list.
R4 / 3: confirm no live littlebird.com.
R7 / 12.7: confirm Fathom and Fireflies November 2025 deprioritization is superseded.
14.4: obtain and add approved Product Hunt proof points.
2: assign per-section owners and monthly re-check dates.

NEEDS-VERIFICATION (external facts):

V1 / 10.9: LLM-provider data agreements.
V2 / 13.2: third-party stat URLs, wording, and years.
V3 / 9.4: GitLab and other unconfirmed integrations.
6.2 / 15.18: current state of speaker diarization and action-item interactivity.

Production bugs to fix on the live site (report, not a bible fact):

The live Littlebird vs Otter and Littlebird vs Fathom pages both title their feature table "Littlebird vs. Cluely." Fix the headers.
The live Littlebird vs Fathom page duplicates the bullet "High-quality meeting notes that become part of a bigger memory." Remove the duplicate.
