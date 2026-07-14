# Sub-spoke proposals v4 -- intent-first audit -- for Shahzad's approval

Date: 2026-07-10. Supersedes output/subspoke-titles-v3.md.

**Shahzad's filter applied:** every page concept must START from a real search intent / human problem and merely be POWERED by a capability. Pages that only describe the API capability ("see your workspace structure", "read a page", "list your recordings") were reframed around the real intent or cut. "Create tasks from meetings" passes; "list your recordings" fails.

**Honest final count: 38 rows** (was 50). We are NOT padding to 50 -- only 38 rows clear the intent bar. Breakdown: **31 KEEP, 5 REFRAMED, 2 REPLACED, 12 CUT.**

**H1 formula unchanged (v3.1):** `How to [verb phrase] with Littlebird's [Tool] Integration` / variant `How to [X] in [Tool] with Littlebird`. Title Case; tool + plain verb-object + "Littlebird". Body voice stays v3; the clever two-beat line is each page's intro hook. Meta-title `[H1] | Littlebird` (H1 alone if that runs long).

**code-search (row 3) is LIVE** and already on the new H1; unchanged here. Its slug is linked from the spoke MAP -- do not touch.

---

## Live rows (38)

| # | Tool | Capability anchor (hero displayed row) | Proposed H1 (v4, intent-first) | Target search query | Slug | Links from (tool :: exact displayed row) | v3 disposition |
|---|---|---|---|---|---|---|---|
| 1 | GitHub | Read pull request details | How to Review Pull Requests with Littlebird's GitHub Integration | ai pull request review github | github/pr-review | GitHub :: Read pull request details | KEEP (v3 #1) |
| 2 | GitHub | List commits | How to Prep Your Standup from GitHub Commits with Littlebird | github standup what did i commit | github/standup-prep | GitHub :: List commits | KEEP (v3 #2) [stretch] |
| 3 | GitHub | Search code | How to Search a Codebase with Littlebird's GitHub Integration | search github codebase with ai | github/code-search | GitHub :: Search code | KEEP (v3 #3, LIVE) |
| 4 | GitHub | Get commit details | How to Trace a Bug to a Commit in GitHub with Littlebird | who changed this code github ai | github/debugging-context | GitHub :: Get commit details | KEEP (v3 #4) |
| 5 | GitHub | Read file contents | How to Understand a New Codebase in GitHub with Littlebird | understand a new codebase github ai | github/onboarding | GitHub :: Read file contents | KEEP (v3 #5) |
| 6 | GitHub | List pull requests | How to See What Shipped This Sprint in GitHub with Littlebird | what shipped this sprint github ai | github/whats-shipped | GitHub :: List pull requests | REFRAMED (v3 #6: was "See Merged Pull Requests") [stretch] |
| 7 | GitHub | Create a pull request | How to Write a Pull Request Description with Littlebird's GitHub Integration | ai pull request description generator | github/pr-description | GitHub :: Create a pull request | REFRAMED (v3 #7: was "Create a Pull Request") |
| 8 | Asana | Read project details | How to Check Project Status in Asana with Littlebird | asana ai project status | asana/project-status | Asana :: Read project details | KEEP (v3 #8) |
| 9 | Asana | Create a task | How to Create Asana Tasks from Meetings with Littlebird | create asana tasks from meetings | asana/tasks-from-meetings | Asana :: Create a task | KEEP (v3 #9) |
| 10 | Asana | Get my tasks | How to Pull Your Asana Tasks for Standup with Littlebird | asana standup ai | asana/standup-prep | Asana :: Get my tasks | KEEP (v3 #10) [stretch] |
| 11 | Asana | Search objects | How to Find Anything in Asana with Littlebird | search asana with ai | asana/search | Asana :: Search objects | REPLACED (v3 #11 was Read task details -> cut; genuine search intent added) |
| 12 | ClickUp | Read your workspace structure | How to Get a Status Update from ClickUp with Littlebird | clickup project status ai | clickup/status-update | ClickUp :: Read your workspace structure | REFRAMED (v3 #14: was "See Your Workspace Structure") |
| 13 | ClickUp | Filter tasks | How to Check Sprint Status in ClickUp with Littlebird | clickup sprint status ai | clickup/sprint-status | ClickUp :: Filter tasks | KEEP (v3 #15) |
| 14 | ClickUp | Search ClickUp | How to Search ClickUp with Littlebird | search clickup with ai | clickup/search | ClickUp :: Search ClickUp | KEEP (v3 #16) |
| 15 | ClickUp | Create a task | How to Create ClickUp Tasks from Meetings with Littlebird | create clickup tasks from meetings | clickup/tasks-from-meetings | ClickUp :: Create a task | KEEP (v3 #17) |
| 16 | Notion | Search across your workspace | How to Find Anything in Notion with Littlebird | find things in notion with ai | notion/knowledge-recall | Notion :: Search across your workspace | KEEP (v3 #20) |
| 17 | Notion | Create new pages | How to Save Meeting Notes to Notion with Littlebird | save meeting notes to notion automatically | notion/meeting-notes | Notion :: Create new pages | KEEP (v3 #21) |
| 18 | Notion | Query your databases | How to Query a Notion Database with Littlebird | query notion database with ai | notion/database-queries | Notion :: Query your databases | KEEP (v3 #22) [stretch] |
| 19 | Notion | Fetch any page's full content | How to Summarize a Notion Page with Littlebird | summarize notion page ai | notion/summarize-page | Notion :: Fetch any page's full content | REFRAMED (v3 #23: was "Read a Notion Page") |
| 20 | Linear | List issues across your workspace | How to Review Linear Issues Before Standup with Littlebird | linear standup ai | linear/standup-prep | Linear :: List issues across your workspace | KEEP (v3 #26) [stretch] |
| 21 | Linear | Read issue comments | How to Get Caught Up on a Linear Issue with Littlebird | linear issue summary ai | linear/issue-context | Linear :: Read issue comments | REFRAMED (v3 #28: was "Get the Context Behind a Linear Issue") [stretch] |
| 22 | Linear | Read issue labels | How to Triage Your Linear Backlog with Littlebird | linear issue triage ai | linear/issue-triage | Linear :: Read issue labels | KEEP (v3 #29) |
| 23 | Linear | Create or update an issue | How to Create Linear Issues from Meetings with Littlebird | create linear issues from meetings | linear/issues-from-meetings | Linear :: Create or update an issue | KEEP (v3 #31) |
| 24 | Todoist | Find tasks by date | How to Plan Your Day in Todoist with Littlebird | todoist daily planning ai | todoist/daily-planning | Todoist :: Find tasks by date | KEEP (v3 #32) |
| 25 | Todoist | Capture tasks without stopping | How to Capture Meeting Tasks in Todoist with Littlebird | capture tasks from meetings todoist | todoist/meeting-task-capture | Todoist :: Capture tasks without stopping | KEEP (v3 #33) |
| 26 | Todoist | Find what you have finished | How to See Your Completed Tasks in Todoist with Littlebird | todoist see completed tasks ai | todoist/completed-work | Todoist :: Find what you have finished | KEEP (v3 #34) |
| 27 | Todoist | Roll forward what slipped | How to Reschedule Overdue Tasks in Todoist with Littlebird | reschedule tasks todoist ai | todoist/reschedule | Todoist :: Roll forward what slipped | KEEP (v3 #36) |
| 28 | Todoist | Search across everything | How to Search Todoist with Littlebird | search todoist with ai | todoist/search | Todoist :: Search across everything | KEEP (v3 #37) |
| 29 | TickTick | Find tasks by date | How to See What's Due This Week in TickTick with Littlebird | ticktick what is due this week ai | ticktick/whats-due-this-week | TickTick :: Find tasks by date | KEEP (v3 #38) |
| 30 | TickTick | Capture tasks without stopping | How to Capture Meeting Tasks in TickTick with Littlebird | capture tasks from meetings ticktick | ticktick/meeting-task-capture | TickTick :: Capture tasks without stopping | KEEP (v3 #39) |
| 31 | TickTick | Get an overview of your plate | How to Plan Your Day in TickTick with Littlebird | ticktick daily planning ai | ticktick/daily-planning | TickTick :: Get an overview of your plate | KEEP (v3 #40) |
| 32 | TickTick | Find what you have finished | How to Run a Weekly Review in TickTick with Littlebird | ticktick weekly review ai | ticktick/weekly-review | TickTick :: Find what you have finished | KEEP (v3 #42) [stretch] |
| 33 | TickTick | Search across TickTick | How to Search TickTick with Littlebird | search ticktick with ai | ticktick/search | TickTick :: Search across TickTick | REPLACED (v3 #41 was Read full task details -> cut; genuine search intent added) |
| 34 | Gmail | Surface open loops | How to Track Emails Waiting for a Reply in Gmail with Littlebird | gmail ai track emails waiting for reply | gmail/open-loops | Gmail :: Surface open loops | KEEP (v3 #43) |
| 35 | Gmail | Draft replies in your voice | How to Draft Gmail Replies in Context with Littlebird | ai draft gmail replies | gmail/draft-replies | Gmail :: Draft replies in your voice | KEEP (v3 #44); H1/query finalized to "in Context" 2026-07-10 (Bible 9.1 verifies "in context", not voice-cloning) |
| 36 | Google Calendar | Meeting prep, before you need to ask | How to Prep for Meetings with Littlebird's Google Calendar Integration | ai meeting prep google calendar | google-calendar/meeting-prep | Google Calendar :: Meeting prep, before you need to ask | KEEP (v3 #46) |
| 37 | Google Calendar | Create and edit events | How to Schedule Meetings in Google Calendar with Littlebird | ai schedule meetings google calendar | google-calendar/scheduling | Google Calendar :: Create and edit events | KEEP (v3 #47) |
| 38 | Plaud | Read full transcripts | How to Search Your Plaud Recordings with Littlebird | search plaud recordings ai | plaud/recording-search | Plaud :: Read full transcripts | KEEP (v3 #48) [stretch] |

---

## Cut rows (12) -- with reasons

| v3 # | Tool | Anchor row | v3 H1 | Why cut |
|---|---|---|---|---|
| 12 | Asana | Get projects | See All Your Asana Projects | Capability-shaped; no one searches "see all my projects." Overlaps project-status (#8). |
| 13 | Asana | Create a project | Create an Asana Project | Thin AI-search demand; creation intent is carried by tasks-from-meetings (#9). |
| 18 | ClickUp | Read task comments | Catch Up on ClickUp Task Comments | "Task comments summary" isn't searched; thin standalone intent. |
| 19 | ClickUp | Create a reminder | Set ClickUp Reminders | Reminders aren't a ClickUp search driver; thin demand. |
| 24 | Notion | Update existing pages | Update Notion Pages | "Update notion with ai" is thin; create/meeting-notes (#17) carries the write intent. |
| 25 | Notion | Move pages and reorganize | Reorganize Notion Pages | No search demand -- pure capability description (Shahzad-style fail). |
| 27 | Linear | List projects | List Your Linear Projects | Capability-shaped; no plausible search. |
| 30 | Linear | Read the full details of any issue | Read a Linear Issue | Capability-shaped; overlaps issue-context (#21). |
| 35 | Todoist | Get an overview of your plate | Get an Overview of Your Todoist Tasks | Cannibalizes daily-planning (#24); same searcher, same answer. |
| 45 | Gmail | Send on your behalf | Send Gmail Emails on Your Behalf | Overlaps draft-replies (#35); thin as a standalone search. Defensible to restore if we want an email-automation angle. |
| 49 | Plaud | Read AI-generated notes | Recall Plaud Meeting Notes | Overlaps recording-search (#38); folds in. |
| 50 | Plaud | List your recordings | List Your Plaud Recordings | Shahzad's explicit fail -- nobody searches this. |

---

## Reframe rationale (5)

- **#6 List pull requests:** "See Merged Pull Requests" is capability-shaped. Real intent = the sprint/release review ("what actually shipped"). Reframed to `what shipped this sprint`. (Single capability: filter merged PRs + summarize.)
- **#7 Create a pull request:** the searched value isn't "create a PR", it's the AI writing the PR description from the diff. Reframed to `ai pull request description generator` -- a genuinely high-demand query. (Drafting the description is part of the create-PR capability; no second capability, and it no longer collides with debugging-context.)
- **#12 Read your workspace structure:** "see your workspace structure" is pure API. Real intent = a status update / catch-up without opening ClickUp. Reframed to Shahzad's own example, `clickup project status ai`.
- **#19 Fetch a page's content:** "read a Notion page" describes the call. Real intent = summarizing / pulling a specific doc into your work. Reframed to `summarize notion page ai`.
- **#21 Read issue comments:** "context behind an issue" was vague. Real intent = catching up on an issue's discussion/decision. Reframed to `linear issue summary ai`.

## Replacements (2)

- **#11 (Asana):** dropped "Read task details" (no demand); added **Asana search** ("Find Anything in Asana", anchor Search objects) -- a genuine, high-intent page matching the search pages already present for Notion/ClickUp/Todoist.
- **#33 (TickTick):** dropped "Read full task details" (no demand); added **TickTick search** ("Search TickTick", anchor Search across TickTick) -- same genuine search intent, and TickTick lacked a search page.

## Stretch flags (step 4) -- honest-but-thin queries to watch

These clear the bar but have modest/uncertain volume; validate against a keyword tool before committing writer effort, and consider consolidating if two underperform:
- #2 `github standup what did i commit`, #10 `asana standup ai`, #20 `linear standup ai` -- three tool-specific "standup prep" pages; distinct tools, but standup-prep search volume is soft. If one tool wins, it validates the pattern; if all three are thin, keep the strongest one or two.
- #6 `what shipped this sprint github ai` -- manager/lead intent, modest volume.
- #18 `query notion database with ai` -- Notion-power-user niche.
- #21 `linear issue summary ai` -- modest.
- #32 `ticktick weekly review ai` -- ritual page, soft volume.
- #38 `search plaud recordings ai` -- small install base; Plaud's one honest page.

---

## Validation

- **38 live rows.** Tool distribution: GitHub 7, Asana 4, ClickUp 4, Notion 4, Linear 4, Todoist 5, TickTick 5, Gmail 2, Google Calendar 2, Plaud 1.
- **Unique slugs (38/38) and unique target queries (38/38).** New slugs (github/whats-shipped, github/pr-description, asana/search, clickup/status-update, notion/summarize-page, ticktick/search) collide with nothing.
- **One displayed capability row per sub-spoke, no collisions.** New anchors (Asana Search objects, TickTick Search across TickTick) were previously unused; all reframe anchors are unchanged from v3.
- **code-search (#3) unchanged** (live; slug linked from the spoke MAP).
- **Every H1** contains tool + plain verb-object + "Littlebird" and starts from a human problem, not a capability description.
- **12 rows cut**, documented above with reasons. 50 (v3) - 12 = 38.

## Summary of what changed

- Applied Shahzad's intent-first filter to all 50 v3 rows.
- **Cut 12** capability-shaped or cannibalizing rows with no plausible search demand (incl. his examples: "list your recordings", "reorganize Notion", "read a page"/"workspace structure" -> the last two reframed instead).
- **Reframed 5** where a real intent hid behind a capability-shaped title (release/sprint review, PR-description generator, ClickUp status update, Notion summarize, Linear issue catch-up).
- **Replaced 2** dead rows with genuine search pages (Asana search, TickTick search).
- **Kept 31** that already started from real intent.
- **Honest total: 38**, not a padded 50. If we later validate demand for a few flagged/cut rows (e.g., Gmail send-automation, an Asana portfolio view), they can be added back deliberately -- but only on evidence, not to hit a round number.

---

## Full-coverage expansion 2026-07-14, per Nikhil

New direction (supersedes the "38, not 50" cap for coverage purposes): EVERY capability h3 on every spoke page gets a sub-spoke, spoke by spoke. These are added on top of the 38 above. GitHub first (all 9 previously-uncovered capability h3s):

| # | Tool | Anchor h3 (exact) | H1 | target-keyword | path |
|---|---|---|---|---|---|
| G1 | GitHub | Search repositories | How to Find the Right Repo in GitHub with Littlebird | find github repository ai | github/find-repo |
| G2 | GitHub | Search pull requests | How to Find a Pull Request in GitHub with Littlebird | search pull requests github ai | github/find-pr |
| G3 | GitHub | List branches | How to See What Branches Are in Progress in GitHub with Littlebird | list github branches ai | github/branch-overview |
| G4 | GitHub | Search commits | How to Find Who Changed a Line in GitHub with Littlebird | find who changed code github ai | github/who-changed |
| G5 | GitHub | Search issues | How to Find a Bug Report in GitHub with Littlebird | search github issues ai | github/find-issue |
| G6 | GitHub | List issues | How to Review Your Open Issues in GitHub with Littlebird | list github issues ai | github/issue-queue |
| G7 | GitHub | Create, update, or push files | How to Commit a Change from Chat with Littlebird's GitHub Integration | commit to github from chat ai | github/commit-from-chat |
| G8 | GitHub | Create a repository | How to Spin Up a New Repo in GitHub with Littlebird | create github repository ai | github/new-repo |
| G9 | GitHub | Create a branch | How to Start a New Branch in GitHub with Littlebird | create github branch ai | github/create-branch |

GitHub coverage after this batch: **16/16 capability h3s linked** (7 prior + 9 new). All Bible §9.5-grounded, Tier 2 (flag for app verification). Remaining spokes to full-cover in later batches.

### ClickUp (7 previously-uncovered h3s), full-coverage expansion 2026-07-14

| # | Tool | Anchor h3 (exact) | H1 | target-keyword | path |
|---|---|---|---|---|---|
| C1 | ClickUp | Read task details | How to Get the Full Details of a ClickUp Task with Littlebird | clickup task details ai | clickup/task-details |
| C2 | ClickUp | Read a list | How to See Everything in a ClickUp List with Littlebird | clickup list contents ai | clickup/list-contents |
| C3 | ClickUp | Read workspace members | How to See Who's in Your ClickUp Workspace with Littlebird | clickup workspace members ai | clickup/workspace-members |
| C4 | ClickUp | Read task comments | How to Catch Up on a ClickUp Task's Comments with Littlebird | clickup task comments ai | clickup/task-comments |
| C5 | ClickUp | Update a task | How to Update a ClickUp Task from Chat with Littlebird | update clickup task ai | clickup/update-task |
| C6 | ClickUp | Create a list | How to Create a ClickUp List from Chat with Littlebird | create clickup list ai | clickup/create-list |
| C7 | ClickUp | Create a reminder | How to Set a ClickUp Reminder from Chat with Littlebird | set clickup reminder ai | clickup/reminders |

ClickUp coverage after this batch: **11/11 capability h3s linked** (4 prior + 7 new). All Bible §9.6-grounded, Tier 2. Note: C4 (Read task comments) and C7 (Create a reminder) were v4-cut rows #18/#19 -- now covered per the full-coverage directive.

### TickTick (7 previously-uncovered h3s), full-coverage expansion 2026-07-14

| # | Tool | Anchor h3 (exact) | H1 | target-keyword | path |
|---|---|---|---|---|---|
| T1 | TickTick | Find your tasks | How to Find a Task in TickTick with Littlebird | find ticktick task ai | ticktick/find-task |
| T2 | TickTick | Find your lists | How to Find Your TickTick Lists with Littlebird | ticktick lists ai | ticktick/find-lists |
| T3 | TickTick | Read full task details | How to Get the Full Details of a TickTick Task with Littlebird | ticktick task details ai | ticktick/task-details |
| T4 | TickTick | Update existing tasks | How to Update a TickTick Task from Chat with Littlebird | update ticktick task ai | ticktick/update-task |
| T5 | TickTick | Mark a task complete | How to Check Off a TickTick Task from Chat with Littlebird | mark ticktick task complete ai | ticktick/complete-task |
| T6 | TickTick | Create a new list | How to Create a TickTick List from Chat with Littlebird | create ticktick list ai | ticktick/create-list |
| T7 | TickTick | Roll forward what slipped | How to Reschedule Overdue Tasks in TickTick with Littlebird | reschedule ticktick tasks ai | ticktick/reschedule |

TickTick coverage after this batch: **12/12 capability h3s linked** (5 prior + 7 new). All Bible §9.11-grounded, PRODUCT-VERIFIED (no Tier-2 flag). "lists" vocab throughout; no smart-date-parsing claim.

### Todoist (6 previously-uncovered h3s), full-coverage expansion 2026-07-14

| # | Tool | Anchor h3 (exact) | H1 | target-keyword | path |
|---|---|---|---|---|---|
| D1 | Todoist | Find your tasks | How to Pull Up Your Todoist Tasks with Littlebird | find todoist tasks ai | todoist/find-tasks |
| D2 | Todoist | Find your projects | How to Find Your Todoist Projects with Littlebird | todoist projects ai | todoist/find-projects |
| D3 | Todoist | Get an overview of your plate | How to See Everything on Your Plate in Todoist with Littlebird | todoist overview ai | todoist/overview |
| D4 | Todoist | Update existing tasks | How to Update a Todoist Task from Chat with Littlebird | update todoist task ai | todoist/update-task |
| D5 | Todoist | Check off tasks | How to Check Off a Todoist Task from Chat with Littlebird | mark todoist task complete ai | todoist/complete-task |
| D6 | Todoist | Create a new project | How to Create a Todoist Project from Chat with Littlebird | create todoist project ai | todoist/create-project |

Todoist coverage after this batch: **11/11 capability h3s linked** (5 prior + 6 new). All Bible §9.4-grounded, PRODUCT-VERIFIED. "projects" vocab. Cannibalization note: D3 (Get an overview) is v4-cut row #35 -- restored with a DISTINCT angle (point-in-time workload/capacity snapshot, cross-linked to daily-planning) rather than duplicating the morning-planning ritual; D1 (Find your tasks) angled as surfacing your task list vs the keyword-hunt framing of the existing todoist-search page.

### Asana (6 previously-uncovered h3s), full-coverage expansion 2026-07-14

| # | Tool | Anchor h3 (exact) | H1 | target-keyword | path |
|---|---|---|---|---|---|
| A1 | Asana | Search tasks | How to Find a Task in Asana with Littlebird | search asana tasks ai | asana/find-task |
| A2 | Asana | Get projects | How to Find Your Asana Projects with Littlebird | asana projects ai | asana/find-projects |
| A3 | Asana | Get tasks from any project or section | How to See Every Task in an Asana Project with Littlebird | asana project task list ai | asana/project-tasks |
| A4 | Asana | Read task details | How to Get the Full Details of an Asana Task with Littlebird | asana task details ai | asana/task-details |
| A5 | Asana | Update a task | How to Update an Asana Task from Chat with Littlebird | update asana task ai | asana/update-task |
| A6 | Asana | Create a project | How to Create an Asana Project from Chat with Littlebird | create asana project ai | asana/create-project |

Asana coverage after this batch: **10/10 capability h3s linked** (4 prior + 6 new). All Bible §9.7-grounded, Tier 2 (flag for app verification). Cannibalization: A1 (Search tasks) angled task-specific vs asana-search's all-objects "find anything"; A2 (Get projects) is v4-cut #12 -- restored as discover/list-which-projects vs asana-project-status's single-project status read; A3 (Get tasks) is a project's full task list vs asana-standup-prep's "my tasks"; A6 (Create a project) is v4-cut #13, restored.

### Linear (5 previously-uncovered h3s), full-coverage expansion 2026-07-14

| # | Tool | Anchor h3 (exact) | H1 | target-keyword | path |
|---|---|---|---|---|---|
| L1 | Linear | Read the full details of any issue | How to Pull Up a Linear Issue's Details with Littlebird | linear issue details ai | linear/issue-details |
| L2 | Linear | List teams | How to See Your Linear Teams with Littlebird | linear teams ai | linear/teams |
| L3 | Linear | List projects | How to See Your Linear Projects with Littlebird | linear projects ai | linear/projects |
| L4 | Linear | Read workflow statuses | How to See Your Team's Linear Workflow Statuses with Littlebird | linear workflow statuses ai | linear/workflow-statuses |
| L5 | Linear | List workspace members | How to See Who's in Your Linear Workspace with Littlebird | linear workspace members ai | linear/workspace-members |

Linear coverage after this batch: **9/9 capability h3s linked** (4 prior + 5 new). All Bible §9.9-grounded, Tier 2 (flag for app verification). All 5 are READ-only -- no save_issue used, so the eng-sign-off flag does NOT apply this batch. Cannibalization: L1 (Read issue details) angled as the issue's fields/specs vs linear-issue-context's discussion catch-up; L3 (List projects) is v4-cut #27 -- restored with an orient/what's-active-and-status angle. L2/L4/L5 are thin capabilities, kept honest and composed with adjacent verified reads.

### Notion (4 previously-uncovered h3s), full-coverage expansion 2026-07-14

| # | Tool | Anchor h3 (exact) | H1 | target-keyword | path |
|---|---|---|---|---|---|
| N1 | Notion | Update existing pages | How to Keep a Notion Page Up to Date with Littlebird | update notion page ai | notion/update-page |
| N2 | Notion | Create new databases | How to Create a Notion Database from Chat with Littlebird | create notion database ai | notion/create-database |
| N3 | Notion | Update a database's data source | How to Keep a Notion Database Current with Littlebird | update notion database ai | notion/update-database |
| N4 | Notion | Move pages and reorganize | How to Reorganize Your Notion Workspace with Littlebird | reorganize notion ai | notion/reorganize |

Notion coverage after this batch: **8/8 capability h3s linked** (4 prior + 4 new). All Bible §9.3-grounded, PRODUCT-VERIFIED (no Tier-2 flag). All 4 uncovered are write capabilities. Cannibalization/cut-list notes: N1 (Update existing pages) is cut-list #24 -- reframed as "keeping docs current," distinct from notion-meeting-notes (creating new pages); N3 (Update data source) is write/update the data, distinct from notion-database-queries (read/query); N4 (Move pages) is v4-cut #25 (rated no search demand) -- restored per full-coverage directive, kept honest and thin.

### Plaud (3) + Gmail (1), full-coverage expansion 2026-07-14, per Nikhil -- COMPLETES FULL COVERAGE

| # | Tool | Anchor h3 (exact) | H1 | target-keyword | path |
|---|---|---|---|---|---|
| P1 | Plaud | List your recordings | How to See All Your Plaud Recordings with Littlebird | list plaud recordings ai | plaud/list-recordings |
| P2 | Plaud | Read AI-generated notes | How to Get the Summary of a Plaud Recording with Littlebird | plaud recording summary ai | plaud/recording-summary |
| P3 | Plaud | Read recording metadata | How to Find the Right Plaud Recording with Littlebird | find plaud recording ai | plaud/find-recording |
| GM1 | Gmail | Send on your behalf | How to Send an Email on Your Behalf in Gmail with Littlebird | ai send email on your behalf gmail | gmail/send |

Plaud coverage: **4/4** (1 prior + 3 new; §9.8 Tier 2, READ-only, no write claims -- flag for app verification). P1 (List) is v4-cut #50, kept honest/thin; P2 (Notes) is cut #49, reframed to gist/summary distinct from plaud-recording-search (exact words); P3 (Metadata) places/identifies a specific recording.
Gmail coverage: **3/3** (2 prior + 1 new; §9.1 PRODUCT-VERIFIED). GM1 (Send on your behalf) is v4-cut #45 (ranked #1 for demand), send-from-Chat reframe, distinct from gmail-draft-replies (draft only); no autonomous-sending overclaim (you stay in control).

## FULL COVERAGE ACHIEVED 2026-07-14

Every capability h3 on every one of the 10 spoke pages now links to a dedicated sub-spoke. **86 sub-spokes live** across GitHub 16, TickTick 12, ClickUp 11, Todoist 11, Asana 10, Linear 9, Notion 8, Plaud 4, Gmail 3, Google Calendar 2. MAP objects exist for all 10 spokes (footer script on the Integrations Template). 0 uncovered h3s remaining.
