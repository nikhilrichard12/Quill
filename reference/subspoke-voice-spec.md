# Sub-Spoke Voice Spec \+ Exemplars

Generated: 2026-07-02 · Author: Fable (planning/writing lane) Purpose: (1) the writing standard for all 50 sub-spokes, (2) few-shot exemplars for the Kimi bulk run, (3) the rubric for the punch-up pass. Companion files: output/subspoke-angle-map.md (angles), output/subspoke-load-mapping.md (IDs), output/webflow-option-ids.md (options). Destination: save as lb-content-engine/output/subspoke-voice-spec.md

---

## 1\. Diagnosis — what good looks like, what the disease is

**The exemplar (Todoist spoke, on-voice 10/10)** works because of three moves:

1. **Pain first, in the user's world.** The H1 is a loss the reader has felt ("The task you meant to capture is already gone."). The intro names three concrete places tasks die: the meeting, the Slack thread, the passing thought.  
2. **Rhythm.** Short declaratives. Deliberate fragments in parallel. A cost stated as a mechanism, not an adjective: "Every query is a context switch you did not budget for."  
3. **The promise arrives late and plain.** Only after the pain is real does the connect line land, and it lands without hype.

**The disease (Linear spoke, "functional but slightly formulaic")** is one repeated sentence machine:

*Littlebird can \[verb\] your Linear \[noun\]. \[Restatement\] without opening Linear. Useful when \[generic situation\].*

Run nine times in a row. Each instance is fine; the accumulation is robotic. The tells: "without opening/switching to Linear" as a crutch (\~9 uses), every section opening with "Littlebird can," benefit clauses that describe categories of usefulness instead of a moment.

**The sub-spoke advantage:** these pages are workflow narratives, not capability inventories. The list format that produced Linear's disease does not exist here. Do not reimport it.

---

## 2\. Voice rules (binding)

1. **Pain first, scene first.** Every intro opens inside the reader's actual moment — the 8:45am scan, the standup, the Sunday-night class-deadline check. Name real artifacts (the Slack thread, the client folder, the biology list), never categories ("your workflows," "your tools").  
2. **Second person throughout.** The reader is "you." Littlebird is the actor only after the pain is established.  
3. **House style: contractions ARE the register.** Use them where they read naturally: "what's due," "you're," "it's gone," "don't," "can't." Match the shipped v3 copy (contractions on every page); do NOT force the older formal "what is / you are / it is" register. Avoid a contraction only where it would blur a load-bearing negation. (This corrects the earlier "no contractions" rule; the shipped v3 spoke copy is the standard, per Bible section 3.1.)  
4. **Short declaratives; fragments allowed for rhythm.** Vary sentence openings. If three consecutive sentences start with the same word, rewrite one.  
5. **Mechanisms, not adjectives.** Never assert value ("powerful," "seamless") — show the cost of the old way or the shape of the new one. "You make the plan in your head, and by the second meeting it is gone" beats any adjective.  
6. **The promise is plain.** One connect line, verb-forward, no exclamation, no hype.  
7. **Scenes describe the user's world; claims describe only verified capabilities.** You may invent the reader's situation (a task surfacing mid-standup). You may NOT invent product behavior: no fabricated Littlebird answer text, no capabilities outside the tool's verified set, no output formats we have not shipped. Every action attributed to Littlebird must trace 1:1 to the verified capability list in the angle map header for that tool.  
8. **Tool-native vocabulary.** Todoist \= projects. TickTick \= lists (students: each class is a list). Linear \= issues/teams. Use the tool's own nouns; a power user should feel the page was written by someone who uses their tool.  
9. **Stay in lane.** Each page honors its anti-duplication note from the angle map. If a sentence would fit equally well on a sibling page, it is too generic — sharpen it toward this page's angle.  
10. **No pricing or plan claims in copy.** The template's plan callout renders the tier from CMS. Do not restate it, do not say "free," do not mention Plus.  
11. **No survey stat, no customer quotes** in sub-spokes. (The 43% stat and the Dailey quotes live on spokes; repeating them across 50 pages dilutes both.)  
12. **End with a landing line, not a CTA.** One forward-looking closing sentence ("Tomorrow morning, ask. The plan is already there."). The template CTA owns conversion language.

### Banned / rationed phrases

- **Max once per page:** "without opening \[Tool\]," "without switching to \[Tool\]," "in seconds."  
- **Max twice per page as a sentence opener:** "Littlebird can…" (this is Linear's disease; weave capabilities into prose instead).  
- **Banned outright:** seamless(ly), effortless(ly), supercharge, game-changer, unlock, leverage (as a verb), streamline, revolutionize, "take your X to the next level," "say goodbye to," "imagine a world."

---

## 3\. Page structure (maps 1:1 to CMS fields)

> **SUB-SPOKE H1 RULE (v3.1 update, Shahzad):** sub-spoke H1s are plain, instructional, SEO-literal, Title Case -- `How to [verb phrase] with Littlebird's [Tool] Integration` (variant: `How to [X] in [Tool] with Littlebird`) -- NOT the two-beat spoke formula. The clever two-beat line becomes the intro's FIRST line. Top-level spoke H1s and sub-spoke BODY voice are unchanged (still v3). Applies to the `h1`, `intro`, and `meta-title` rows below and the exemplars in section 5.

| Field | Spec |
| :---- | :---- |
| `h1` | 6–14 words, Title Case, instructional and SEO-literal -- NOT the two-beat spoke formula. Pattern: `How to [verb phrase] with Littlebird's [Tool] Integration` (variant where the verb-object reads better: `How to [X] in [Tool] with Littlebird`). MUST contain the tool name + the capability's plain verb-object + the word Littlebird (these pages ARE the keyword play). The clever two-beat line moves to the intro's FIRST line (see intro row). No terminal period. |
| `intro` (RichText) | 50–90 words, 1–2 paragraphs. Scene → cost mechanism → one plain connect line. No headings inside. |
| `body` (RichText) | 250–400 words. Opens with an **H2 phrased as the natural-language question** the page answers (mirror the search intent from the angle map), and the first sentence under it is a direct answer (AEO answer-first pattern). Then 2–4 **H3 sections**, each anchored to ONE hero capability from the angle-map row, each opening with a moment, not a feature. One closing landing line as a plain paragraph. |
| `meta-title` | Pattern: `[H1] \| Littlebird` (aim ~60 chars). The v3 H1 already contains the tool name + capability + Littlebird, so if `[H1] \| Littlebird` runs long, use the H1 alone as the meta-title -- do not double Littlebird or mangle the H1. |
| `meta-description` | 130–155 chars. Pain clause \+ promise clause \+ tool name. No ellipses, no exclamation. |

**Allowed HTML in RichText fields:** `<h2>`, `<h3>`, `<p>`, `<strong>`, `<em>`, `<ul>`, `<li>`. **No `<a>` tags** — the parent link (eyebrow) and sibling links (collection list) are template-owned. **No `<h1>`** (the h1 field owns it).

**Not generated by the writer/Kimi (derived mechanically at load time):** slug (`notion/meeting-notes` → `notion-meeting-notes`), canonical-path (`/integrations/notion/meeting-notes`), use-case-type, target-icp, lb-plan-required, parent-integration, status. All from output/subspoke-load-mapping.md.

---

## 4\. Kimi output contract

One JSON object per row, one file per tool (or JSONL). Content fields only:

```json
{
  "row": 33,
  "slug_source": "todoist/daily-planning",
  "h1": "…",
  "intro_html": "<p>…</p>",
  "body_html": "<h2>…</h2><p>…</p><h3>…</h3><p>…</p>",
  "meta_title": "…",
  "meta_description": "…"
}
```

Kimi's prompt \= this spec (sections 2–3) \+ the four exemplars below \+ the tool's angle-map section (header with verified capability set \+ the row) . Generate per-tool batches so the capability set in context always matches the rows being written.

---

## 5\. Exemplars

Four pages covering the three sub-spoke archetypes: the **ritual** page (daily-planning), the **single-hero-capability** page (meeting-task-capture), the **professional-ICP** page (for-freelancers), and the **distinct-ICP** page (for-students). Between them they also cover both verified tools (Todoist, TickTick). These are written in the v3 register -- copy the voice, not just the structure.

---

### Exemplar 1 -- `todoist/daily-planning` (ritual archetype, priority 10)

**h1:** How to Plan Your Day in Todoist with Littlebird

**intro:**

Skip the project-by-project scan. Plan your Todoist day in one question.

Every morning starts the same way. You open Todoist, click into the first project, then the next, then the one you forgot about. You tally what's due, what slipped, what can wait. You build the plan in your head -- and by the second meeting, it's gone.

Littlebird's already been paying attention across your Todoist. Ask, and it builds the picture for you: what's due today, what's overdue, what should move.

**body:**

## How do I plan my day with Todoist and AI?

Ask Littlebird what's on your plate and it reads across your Todoist -- every project at once -- and answers with today's real shape: due, overdue, and everything in flight. The morning scan becomes a single question.

### Start with what's due

The plan begins with the deadline layer. Littlebird can find your tasks by date, so ask what's due today and it surfaces them -- including the ones that slipped past yesterday and are quietly overdue. No project-by-project audit. The day's non-negotiables come first, so you build around what's actually fixed.

### See the whole plate, not one project

A day plan made from one project is a guess. Littlebird can get an overview of your tasks and projects together, so the client work, the internal work, and the thing you promised your cofounder all show up in the same answer. You set priorities with the full picture in front of you, not the corner you happened to open.

### Move what won't happen today

Every honest morning plan ends with rescheduling. Littlebird can reschedule a task to a new date, so when something clearly won't fit, you tell it to move -- the task lands on its new date in Todoist while you stay in the plan. The list you start the day with is one you actually believe.

Tomorrow at 8:45, ask. The plan's already there.

**meta-title:** How to Plan Your Day in Todoist with Littlebird

**meta-description:** The morning Todoist scan, replaced by one question. Littlebird surfaces what's due, what slipped, and what should move -- across every project at once.

---

### Exemplar 2 -- `todoist/meeting-task-capture` (single-hero archetype, priority 9)

**h1:** How to Capture Meeting Tasks in Todoist with Littlebird

**intro:**

Capture meeting tasks in Todoist, without stopping the meeting.

A task surfaces mid-meeting. You've got two options and both are bad: stop listening while you switch to Todoist and type it in, or trust you'll remember it later. You won't remember it later.

Littlebird's already listening along and transcribing the call, so it hears the task when it lands. It captures the task the moment it appears -- from the meeting, a chat message, or a passing thought -- while you stay in the conversation.

**body:**

## How do I capture tasks from meetings into Todoist?

Littlebird listens along to your meetings and can add a new task to Todoist when one comes up -- you keep your attention on the room, and the task lands in your list. The capture happens at the moment of commitment, which is the only moment it reliably happens at all.

### The moment it appears, not after

"Can you own that?" is a task. So is "let's revisit Thursday" and the idea you had while someone else was talking. These arrive at inconvenient times by definition. Littlebird can add the task as the moment happens, so nothing depends on your memory surviving to the end of the meeting.

### It lands where your system lives

Captured tasks go into Todoist -- the same projects, the same place your day already runs from. There's no second inbox to reconcile, no export step. Your after-meeting review is just reading tasks that are already home.

### Fix the details once the room empties

Capture in the moment is fast, not perfect. Afterward, Littlebird can update an existing task -- sharpen the wording, set the due date the discussion implied -- so you're not rebuilding it from memory.

The next meeting will produce tasks. This time they'll all survive it.

**meta-title:** How to Capture Meeting Tasks in Todoist with Littlebird

**meta-description:** Tasks surface mid-meeting and die there. Littlebird captures them into Todoist the moment they appear -- while you stay in the conversation.

---

### Exemplar 3 -- `todoist/for-freelancers` (professional-ICP archetype, priority 8)

**h1:** How to Use Todoist for Freelancers with Littlebird

**intro:**

Todoist for freelancers: prove the week, plan the next.

Freelance work has a second job attached: accounting for the first one. Each client wants to know what got done, the invoice needs the same answer with dates on it, and Friday afternoon disappears into scrolling completed tasks, trying to reconstruct the week.

Littlebird's been watching the week happen. Connect Todoist and it turns that reconstruction into a question.

**body:**

## How do freelancers use Todoist with AI?

Ask Littlebird what you finished this week and it finds your completed tasks in Todoist -- the deliverable log's already written, because you wrote it all week by checking things off. Billing, client updates, and the Friday reckoning all start from that answer instead of from scrolling.

### The proof-of-work question

Invoices and status emails need the same raw material: what shipped, and when. Littlebird can find what you've finished, filtered to the stretch you care about, so the billable summary is a lookup, not an archaeology dig. The work you did stops being work you also have to remember.

### Deadlines across every client at once

Each client lives in their own project, and each project hides its own deadlines. Littlebird can find your tasks by date across all of them, so ask what's due this week and the Tuesday deliverable for one client can't ambush you while you're heads-down for another.

### Know each client's next ask

Before a check-in call, ask what's open in that client's project. Littlebird can find your projects and surface what's on one, so you walk in current without a pre-call audit.

Friday afternoon, ask for the week. Then invoice it and close the laptop.

**meta-title:** How to Use Todoist for Freelancers with Littlebird

**meta-description:** Prove the week without scrolling for it. Littlebird reads your Todoist -- completed work, client deadlines, open asks -- so billing starts from an answer.

---

### Exemplar 4 -- `ticktick/for-students` (distinct-ICP archetype, priority 9)

**h1:** How to Use TickTick for Students with Littlebird

**intro:**

TickTick for students: every class, every deadline, one question.

Your semester lives in TickTick -- a list for each class, an entry for each assignment, due dates for all of it. The system's good. The overhead isn't: knowing what's due this week still means opening every list, one class at a time, and hoping you didn't skip one.

Connect TickTick and Littlebird reads across all your lists at once.

**body:**

## How do students use TickTick with AI?

Ask Littlebird what's due this week and it finds your TickTick tasks by date across every list -- every class -- in one answer. The Sunday-night deadline sweep becomes a single question instead of a list-by-list patrol.

### One question across every class

Deadlines don't coordinate with each other. The biology lab report and the history essay land in the same week without warning, each hiding in its own list. Littlebird can find your tasks by date across your whole TickTick, so the collision shows up in the answer -- before it shows up in your week.

### Each list is a class; ask about the class

Littlebird can find your lists, so ask what's left in one course and it surfaces that list and what's on it. Before a lecture, before office hours, before deciding what tonight is for -- you know where the course stands without paging through it.

### The full assignment, not just the title

"Essay 2" as a task title hides everything that matters: the length, the sources, the actual prompt you pasted in when it was assigned. Littlebird can read the full details of a task, so the requirements you filed away in October are one question away in November.

Sunday night, ask what the week looks like. Then start it already knowing.

**meta-title:** How to Use TickTick for Students with Littlebird

**meta-description:** Assignments across every class, one question. Littlebird reads your TickTick lists -- deadlines, courses, full assignment details -- so nothing ambushes you.

## 6\. Punch-up rubric (for reviewing Kimi output)

Score each page pass/fail on six checks; any failure \= rewrite that section, not the whole page:

1. Intro opens inside a concrete moment (not a category of pain).  
2. H2 is the natural-language question; first sentence under it answers directly.  
3. Every H3 opens with a scene; every Littlebird action traces to the verified capability set.  
4. Crutch-phrase counts within ration (§2); no banned words; ≤2 "Littlebird can" openers.  
5. Tool-native vocabulary correct (projects/lists/issues); page stays inside its anti-duplication lane.  
6. Landing line present; no CTA language, no pricing, no stats, no quotes.

Priority order for the punch-up pass: Todoist rows (32–38) and TickTick rows (39–42) first (product-verified, ship first), then by angle-map priority score descending.

---

## 7\. Open flags (confirm before the Kimi run)

1. **Bible check on scenarios:** the spoke grader noted "no concrete scenario in body — Bible constraint." Sub-spokes are scenario-driven by design (the angle map is built from scenarios). Rule 7 draws the line at user-world scenes \= allowed, invented product behavior \= banned. Confirm this matches the Bible's intent, or the exemplars need a claims re-read.  
2. **H2 rendering:** Prompt B includes the `.int-richtext h2` CSS check. If H2 inside rich text cannot be styled acceptably, the body pattern falls back to H3-question openers and this spec gets a one-line amendment.  
3. **Capability phrasing:** spoke pages restate capabilities verbatim ("Littlebird can find your tasks across Todoist"). These exemplars weave the same verified capabilities into prose. Confirm verbatim restatement is a spoke convention, not a Bible requirement.

---

## 8\. Claims wording rules (binding)

Any statement about subscriptions, plans, pricing, or costs MUST name whose subscription/plan it is. Never "no subscription needed" — always "no [Tool] subscription needed." Littlebird tier claims live only in the plan field, never in body copy or notes. Third-party requirements (device, paid tier of the tool, OAuth) live only in the third-party note field and always name the tool.

**Why this rule exists:** On the Plaud spoke, "No separate subscription needed" directly above "Requires Littlebird Plus" read as contradictory — the reader didn't know whose subscription was not needed. Every cost/plan claim must be unambiguous in isolation.

**Applies to:** `third-party-plan-note` CMS field, any FAQ answers that touch pricing, and any body copy sentence that mentions cost, tiers, or subscriptions.
