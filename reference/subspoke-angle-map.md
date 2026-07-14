# Sub-spoke angle map
# Status: DRAFT -- for review and approval before any page generation
# Date: 2026-06-29
# Integrations covered: Notion, GitHub, ClickUp, Asana, Todoist, TickTick, Linear
# Total candidates surviving the cut: 50
# Total cut as thin or duplicative: 18 (listed in the cut log at the end)

---

## Anti-duplication principles applied

Before the tables, these are the four tests every candidate had to pass:

1. **Different pain trigger.** The page must address a problem that the main integration page does not foreground. "You already have the problem, but this page names your specific version of it."
2. **Different capability hero.** At least one capability must be the featured focus that is not the lead on any other sub-spoke for the same integration.
3. **Different searcher.** The person who would type this query is meaningfully different from the person who would type a different sub-spoke query -- different role, workflow moment, or job-to-be-done.
4. **Different primary content.** The intro, pain frame, and capability emphasis would be substantively different -- not a word swap from another page.

Cross-integration parallels (e.g., "meeting-task-capture" for Todoist, TickTick, Asana, and ClickUp) are acceptable because they target users already committed to a specific tool. "Capture tasks from meetings to Todoist" and "capture tasks from meetings to Asana" are different queries from different people. The pages are not duplicates of each other.

---

## Priority scoring

Each sub-spoke is scored on three dimensions:
- **S (Search value, 1--4):** Is there real, specific search intent for this query? 4 = high commercial intent, well-defined query phrase.
- **D (Distinctness, 1--3):** How genuinely different is this from other sub-spokes for the same integration? 3 = substantively different capability hero and pain frame.
- **C (Capability depth, 1--3):** How many distinct capabilities from the Bible support this angle in a first-class way? 3 = three or more.
- **Total (max 10):** S + D + C

---

## NOTION (8 sub-spokes)

Verified capability set:
READ: Search across your workspace | Fetch any page's full content | Query your databases
WRITE: Create new pages | Update existing pages | Create new databases | Update a database's data source | Move pages and reorganize

| Slug | Search intent / keyword | Distinct angle | Key capabilities (Bible-verified) | Anti-duplication note | Priority |
|---|---|---|---|---|---|
| `notion/meeting-notes` | "notion meeting notes AI", "save meeting notes to notion automatically" | Meeting outputs land in Notion without a tab switch: Littlebird transcribes the meeting and creates a Notion page from the summary. Hero capability is Create new pages -- writing back, not searching forward. | Create new pages (hero), Update existing pages, Fetch any page's full content (pre-meeting context) | Different from `for-product-managers` (which is about searching + querying during spec work, not capturing meeting output) and `knowledge-recall` (read-focused, not write-focused). | **S:4 D:3 C:3 = 10** |
| `notion/for-product-managers` | "notion AI for product managers", "AI assistant for product specs notion" | PMs use Notion as the canonical source for PRDs, specs, and decisions. The pain is context-switching during writing: checking a prior spec, querying a database of feature requests, updating a page. Hero: Search across your workspace + Query your databases as live context while drafting. | Search across your workspace (hero), Query your databases (hero), Update existing pages, Fetch any page's full content | Different from `meeting-notes` (capture vs retrieve) and `knowledge-recall` (general search vs PM-specific artifact types and workflow moments). | **S:4 D:3 C:3 = 10** |
| `notion/knowledge-recall` | "find things in notion with AI", "notion AI search", "recall notion pages" | The general-audience "I know it's in Notion but I can't find it" problem. Broad ICP appeal (anyone with a large Notion workspace). Hero: Search across your workspace + Fetch any page's full content as the primary pain-resolvers. No write angle. | Search across your workspace (hero), Fetch any page's full content (hero), Query your databases | Different from `for-product-managers` (PM workflow angle) and `meeting-notes` (write-back). This is the read-only lookup page for non-role-specific users. | **S:4 D:2 C:3 = 9** |
| `notion/for-founders` | "notion AI for founders", "AI investor update notion", "notion AI for startup" | Founders use Notion as team knowledge base and often draft investor updates from it. Pain: reconstructing the week from pages and databases for investor updates and team alignment. Hero: Fetch any page's full content + Create new pages (draft investor update from real activity). | Fetch any page's full content (hero), Search across your workspace, Create new pages | Different from `for-product-managers` (investor + team alignment angle vs PM spec workflow) and `meeting-notes` (founder uses case spans multiple use moments, not just meeting capture). | **S:3 D:3 C:3 = 9** |
| `notion/database-queries` | "AI query notion database", "ask questions notion database", "notion as CRM AI" | Teams using Notion databases as lightweight CRMs, project trackers, or content inventories. Pain: finding a record or running a filter requires navigating to the right database view. Hero: Query your databases in a fully distinct use case from page-level search. | Query your databases (hero -- this is the ONLY sub-spoke where it is the hero), Fetch any page's full content, Search across your workspace | Different from every other Notion sub-spoke because this is the only angle where Query your databases is the primary use case. PM and knowledge-recall pages mention it but do not foreground it. | **S:3 D:3 C:3 = 9** |
| `notion/for-consultants` | "notion AI consultant", "AI for consulting firm notion", "client notes notion AI" | Consultants maintain separate Notion workspaces or spaces per client. Pain: searching across multiple client contexts and creating deliverable drafts from meeting notes. Hero: Search across your workspace (cross-client search) + Create new pages (draft deliverables). | Search across your workspace (hero -- cross-client context), Create new pages, Update existing pages | Different from `for-product-managers` (client context vs product context, deliverable-creation angle), `for-founders` (client management vs personal knowledge). | **S:3 D:3 C:3 = 9** |
| `notion/for-marketing-teams` | "notion AI for marketing", "marketing content calendar notion AI" | Marketing teams use Notion for campaign briefs, brand docs, and content calendars. Pain: looking up brand guidelines or prior campaign notes during a creative session, then writing a brief back to Notion. Hero: Fetch any page's full content (brand/campaign recall) + Create new pages (brief creation). | Fetch any page's full content (hero), Create new pages, Query your databases (content calendar queries) | Different from `for-product-managers` (brand/campaign artifacts vs product specs, creative workflow vs product development workflow). Different from `meeting-notes` (briefs are not meeting outputs -- they are independent creation artifacts). | **S:3 D:2 C:3 = 8** |
| `notion/for-engineers` | "notion AI engineer", "runbook search notion AI", "architecture decisions notion" | Engineers use Notion for runbooks, ADRs (architecture decision records), and incident post-mortems. Pain: finding the correct runbook under pressure or the decision rationale buried in an old ADR. Hero: Search across your workspace (fast retrieval under pressure) + Fetch any page's full content (full runbook or ADR text). | Search across your workspace (hero), Fetch any page's full content (hero), Update existing pages (post-incident updates) | Different from `knowledge-recall` (engineering artifact types and urgency framing -- runbooks in an incident vs casual search) and `for-product-managers` (technical operational docs vs product specs). | **S:3 D:2 C:2 = 7** |

---

## GITHUB (10 sub-spokes)

Verified capability set:
READ: Search repositories | Read file contents | List commits | Search code | Read pull request details | Search pull requests | List branches | Search commits | List pull requests | Search issues | Get commit details | List issues
WRITE: Create, update, or push files | Create a repository | Create a pull request | Create a branch

| Slug | Search intent / keyword | Distinct angle | Key capabilities (Bible-verified) | Anti-duplication note | Priority |
|---|---|---|---|---|---|
| `github/pr-review` | "AI GitHub pull request review", "PR context AI", "understand PR changes AI" | Engineers reviewing a PR need the full context behind the change: who wrote it, what issue it closes, what changed in the diff. Hero: Read pull request details + Get commit details. The page answers "I am looking at a PR and need context fast." | Read pull request details (hero), Get commit details (hero), Search commits, List pull requests | Different from `standup-prep` (PR review is a specific synchronous task, not a daily ritual) and `code-search` (understanding a specific change vs finding code by pattern). | **S:4 D:3 C:3 = 10** |
| `github/standup-prep` | "AI standup GitHub", "what did I commit yesterday GitHub", "daily standup developer AI" | Engineers need to report on yesterday's work in standup. Pain: reconstructing commits and PRs from memory while on the call. Hero: List commits + Search commits (by author + date) + List pull requests (my open PRs). Daily ritual, personal scope. | List commits (hero), Search commits (hero), List pull requests, Search pull requests | Different from `pr-review` (whole-team PR archaeology vs personal daily output) and `for-engineering-managers` (individual IC scope vs management visibility). | **S:4 D:3 C:3 = 10** |
| `github/code-search` | "search GitHub codebase AI", "AI find code GitHub", "ask questions about my codebase" | Developers hunting for a function, pattern, or implementation across a large codebase. Pain: GitHub's native search is powerful but requires knowing what to type. Hero: Search code + Read file contents (see the full file once located). | Search code (hero), Read file contents (hero), Search repositories | Different from `debugging-context` (finding WHERE code is vs understanding WHY it is the way it is). Different from `pr-review` (codebase-wide search vs single-PR context). | **S:4 D:3 C:3 = 10** |
| `github/for-product-managers` | "GitHub AI for product managers", "AI track features GitHub", "what shipped GitHub AI" | PMs need visibility into engineering output without reading diffs. Pain: "what shipped this sprint?" requires opening GitHub and interpreting commits. Hero: List pull requests (merged = shipped) + Search issues (feature requests and bugs) + List issues. | List pull requests (hero), Search issues (hero), List issues, Get commit details | The only sub-spoke where the user is NON-TECHNICAL -- emphasizes plain-language summaries of engineering output, not code-level context. Different from all other GitHub sub-spokes which assume a technical audience. | **S:4 D:3 C:3 = 10** |
| `github/for-engineering-managers` | "GitHub AI engineering manager", "team velocity GitHub AI", "engineering team PR queue AI" | EMs need cross-team visibility: what is the PR queue, who is blocked, what did each engineer ship this week. Hero: List pull requests (team-wide, not just mine) + Search issues (team backlog health) + List commits (team velocity). | List pull requests (hero), Search issues (hero), List commits, List issues, Read pull request details | Different from `standup-prep` (management altitude vs IC daily ritual -- EM tracks team output, not personal output) and `for-founders-and-ctos` (team-level operational detail vs org-level architecture concerns). | **S:4 D:3 C:3 = 10** |
| `github/onboarding` | "understand new codebase AI", "AI onboarding GitHub", "learn codebase fast GitHub AI" | New engineers joining a team need to understand an unfamiliar codebase quickly. Pain: reading code without context -- what does this do, who wrote it, what pattern does the team use here. Hero: Search code + Read file contents + Search commits (learn the history). | Read file contents (hero), Search code (hero), Search commits, List branches, Search repositories | The ONLY sub-spoke with an onboarding frame. Every other sub-spoke assumes the user knows their codebase. Different cap emphasis: List branches (understand active work) matters here, not in standup-prep. | **S:3 D:3 C:3 = 9** |
| `github/release-notes` | "draft release notes from GitHub", "AI generate changelog GitHub", "release notes from pull requests AI" | Engineering teams drafting release notes or changelogs from merged PRs. Pain: manually reading merged PRs from the last sprint and summarizing what shipped. Hero: List pull requests (merged) + Get commit details + Create, update, or push files (write the release notes back). | List pull requests (hero), Get commit details (hero), Create, update, or push files | The ONLY write-focused GitHub sub-spoke with a content-creation angle. Hero write capability: Create, update, or push files. No other GitHub sub-spoke uses a write capability as its hero. | **S:3 D:3 C:3 = 9** |
| `github/issue-triage` | "GitHub issue triage AI", "backlog management GitHub AI", "AI prioritize GitHub issues" | Teams with growing issue backlogs need to triage: find duplicates, assign labels, identify stale issues. Hero: Search issues + List issues + Read pull request details (is this issue already being addressed?). | Search issues (hero), List issues (hero), Read pull request details | Different from `for-engineering-managers` (triage is a specific task with structured output, not general visibility) and `for-product-managers` (issue management workflow vs reading what shipped). | **S:3 D:3 C:3 = 9** |
| `github/debugging-context` | "understand code history AI", "who changed this function GitHub AI", "git blame AI assistant" | Engineers debugging a subtle issue who need to understand why code is the way it is. Pain: `git blame` shows who changed it but not why; PR descriptions are often missing. Hero: Get commit details + Search commits (by file/line range) + Read pull request details (find the PR that introduced this). | Get commit details (hero), Search commits (hero), Read pull request details | Different from `code-search` (finding WHERE code is vs understanding WHY it changed). Different from `pr-review` (debugging a live issue vs reviewing a proposed change). | **S:3 D:3 C:3 = 9** |
| `github/for-founders-and-ctos` | "GitHub AI for CTO", "AI codebase health startup CTO", "technical due diligence AI GitHub" | CTOs and technical founders need high-altitude visibility: what is the codebase health, what are engineers shipping, are there obvious tech debt signals. Hero: Search repositories + List commits (output signal) + List pull requests (team cadence). | Search repositories (hero), List commits, List pull requests, Search issues | Different from `for-engineering-managers` (architecture and org health angle vs day-to-day team operations). Different from `pr-review` (30,000-foot view vs ground-level code review). | **S:3 D:2 C:3 = 8** |

---

## CLICKUP (6 sub-spokes)

Verified capability set:
READ: Read your workspace structure | Filter tasks | Search ClickUp | Read task details | Read a list | Read workspace members | Read task comments
WRITE: Create a task | Update a task | Create a list | Create a reminder

| Slug | Search intent / keyword | Distinct angle | Key capabilities (Bible-verified) | Anti-duplication note | Priority |
|---|---|---|---|---|---|
| `clickup/for-project-managers` | "ClickUp AI project manager", "AI status report ClickUp", "ClickUp AI project overview" | PMs managing multiple projects need quick status answers. Pain: "what is the status on the rebrand?" requires navigating the workspace hierarchy. Hero: Read your workspace structure + Filter tasks (by status/assignee) + Read task details. | Read your workspace structure (hero), Filter tasks (hero), Read task details, Read a list | Different from `sprint-status` (PM oversight of ALL projects vs sprint team's single-sprint view) and `standup-prep` (management altitude vs individual standup). | **S:4 D:3 C:3 = 10** |
| `clickup/meeting-task-capture` | "capture tasks from meetings ClickUp", "ClickUp AI task capture", "create ClickUp tasks from meeting" | The cost of missing an action item from a meeting when the team uses ClickUp. Hero write capability: Create a task from a meeting, a Chat message, or a passing thought. | Create a task (hero), Update a task, Create a reminder | Different from `for-project-managers` (create-focused vs read-focused; IC task capture vs PM status monitoring). Different from `sprint-status` (capture is a write operation; sprint-status is a read operation). | **S:4 D:3 C:2 = 9** |
| `clickup/sprint-status` | "ClickUp sprint status AI", "AI sprint progress ClickUp", "what is done in sprint ClickUp" | Engineering and product teams doing a sprint check-in. Pain: "what moved to done this sprint, what is blocked?" requires filtering by status, list, and assignee. Hero: Filter tasks (by status + date range) + Read a list + Read task comments (is this blocked?). | Filter tasks (hero), Read a list (hero), Read task comments, Read task details | Different from `for-project-managers` (single-sprint team view vs multi-project PM overview). Different from `standup-prep` (sprint ceremony view vs personal daily task check). | **S:4 D:3 C:3 = 10** |
| `clickup/standup-prep` | "ClickUp standup AI", "daily standup ClickUp AI assistant", "what did I complete in ClickUp" | Individual contributors preparing for standup: what tasks did I complete yesterday, what is assigned to me today. Hero: Filter tasks (by assignee = me + date = yesterday/today) + Read task details. | Filter tasks (hero -- by assignee + date), Read task details | Different from `sprint-status` (personal IC view vs team sprint board) and `for-project-managers` (individual daily ritual vs PM multi-project management). | **S:3 D:3 C:2 = 8** |
| `clickup/for-marketing-teams` | "ClickUp AI marketing team", "campaign tracking ClickUp AI", "content calendar ClickUp AI assistant" | Marketing teams using ClickUp to manage campaigns, content calendars, and launch checklists. Pain: "where is the Q3 campaign checklist?" or "what content is due this week?" Hero: Filter tasks (by due date + list) + Read a list (content calendar view) + Create a task (capture content ideas). | Filter tasks (hero), Read a list (hero), Create a task, Read task details | Different from `for-project-managers` (marketing-specific artifact types -- campaigns, content calendars, launch checklists -- not generic project management). ICP is marketing manager/director, not project manager. | **S:3 D:2 C:3 = 8** |
| `clickup/for-agencies` | "ClickUp AI agency", "client project tracking ClickUp AI", "agency project management ClickUp AI" | Agencies managing multiple client projects in ClickUp. Pain: "what is the status across all client projects this week?" requires navigating every client space. Hero: Read your workspace structure (cross-client map) + Filter tasks (by client space + assignee) + Read workspace members (who is on each account). | Read your workspace structure (hero), Filter tasks (hero), Read workspace members | Different from `for-project-managers` (multi-client structure angle -- workspace-level navigation vs single project management) and `for-marketing-teams` (agency client deliverables vs internal marketing campaigns). | **S:3 D:3 C:3 = 9** |

---

## ASANA (7 sub-spokes)

Verified capability set:
READ: Search tasks | Get projects | Get my tasks | Get tasks from any project or section | Search objects | Read task details | Read project details
WRITE: Create a task | Update a task | Create a project

| Slug | Search intent / keyword | Distinct angle | Key capabilities (Bible-verified) | Anti-duplication note | Priority |
|---|---|---|---|---|---|
| `asana/for-project-managers` | "Asana AI project manager", "AI project status Asana", "Asana AI manager overview" | PMs need to monitor project health across multiple Asana projects without drilling into each one. Pain: "what is the status on the rebrand project?" requires opening Asana and navigating to the right project. Hero: Get projects + Read project details + Get tasks from any project or section. | Get projects (hero), Read project details (hero), Get tasks from any project or section | Different from `standup-prep` (PM oversight altitude vs IC daily task check) and `meeting-task-capture` (read-heavy monitoring vs write-heavy capture). | **S:4 D:3 C:3 = 10** |
| `asana/standup-prep` | "Asana standup AI", "what are my Asana tasks today AI", "daily standup assistant Asana" | Individual contributors preparing for standup: what tasks did I complete, what is assigned to me, what is blocked. Hero: Get my tasks (personal task list) + Read task details (context on each). | Get my tasks (hero), Read task details, Search tasks | The ONLY sub-spoke where Get my tasks is the hero capability. Different from `for-project-managers` (personal IC view vs management oversight). Different from `weekly-review` (today/this-standup scope vs weekly retrospective scope). | **S:4 D:3 C:2 = 9** |
| `asana/meeting-task-capture` | "create Asana tasks from meetings", "Asana AI task capture meeting", "capture action items Asana" | Teams using Asana whose tasks come out of meetings. Pain: the action item is spoken aloud; capturing it requires switching to Asana before the moment passes. Hero: Create a task from a meeting or Chat message. | Create a task (hero), Update a task | The ONLY write-hero sub-spoke for Asana. Every other Asana sub-spoke leads with read capabilities. Different ICP from `for-project-managers` (ICs and team members, not PMs). | **S:4 D:3 C:1 = 8** |
| `asana/for-marketing-teams` | "Asana AI marketing team", "campaign management Asana AI", "Asana AI launch planning" | Marketing teams managing campaigns and launches in Asana. Pain: tracking launch readiness across sections (design, copy, approvals) without drilling into every task. Hero: Get tasks from any project or section (launch checklist view) + Read project details (launch status). | Get tasks from any project or section (hero), Read project details, Search tasks | Different from `for-project-managers` (launch and campaign artifact types vs generic project management; marketing-specific timeline pressure). Different ICP from `for-consultants` (internal team vs external client work). | **S:3 D:3 C:2 = 8** |
| `asana/for-consultants` | "Asana AI consultant", "client project tracking Asana AI", "Asana AI multiple clients" | Consultants managing multiple client engagements in Asana. Pain: cross-client status checks and deliverable tracking across separate Asana projects. Hero: Get projects (all client projects) + Read project details (per-client status) + Search tasks (find a client deliverable fast). | Get projects (hero -- multi-client), Read project details, Search tasks | Different from `for-project-managers` (external client management vs internal team management; deliverable-and-billing angle vs milestone angle). Different from `for-marketing-teams` (client work context vs internal team context). | **S:3 D:3 C:2 = 8** |
| `asana/weekly-review` | "Asana weekly review AI", "what did I complete in Asana this week", "Asana AI week recap" | The end-of-week retrospective ritual: what did I complete, what is still open, what do I need to carry to next week. Hero: Get my tasks (completed this week) + Search tasks (open + overdue). | Get my tasks (hero -- completed filter), Search tasks, Update a task | Different from `standup-prep` (weekly scope vs daily scope; looking back vs reporting today). Different from `for-project-managers` (IC personal retrospective vs PM multi-project oversight). | **S:3 D:3 C:2 = 8** |
| `asana/sprint-planning` | "Asana sprint planning AI", "AI sprint setup Asana", "plan sprint in Asana AI" | Engineering and product teams using Asana for sprint management. Pain: setting up a new sprint means creating a project or section, adding tasks, assigning them. Hero: Create a project (sprint project) + Create a task (stories/tickets) + Get tasks from any project or section (pull backlog items). | Create a project (hero), Create a task, Get tasks from any project or section | Different from all read-heavy sub-spokes -- two write capabilities are foregrounded. Different ICP from `for-project-managers` (sprint team + scrum master vs ongoing PM oversight). | **S:3 D:3 C:2 = 8** |

---

## TODOIST (7 sub-spokes)

Verified capability set:
READ: Find your tasks | Find your projects | Find tasks by date | Get an overview of your plate | Search across everything | Find what you have finished
WRITE: Capture tasks without stopping | Update existing tasks | Check off tasks | Create a new project | Move a task to a new date

| Slug | Search intent / keyword | Distinct angle | Key capabilities (Bible-verified) | Anti-duplication note | Priority |
|---|---|---|---|---|---|
| `todoist/meeting-task-capture` | "capture tasks from meetings Todoist", "Todoist AI meeting task", "create Todoist tasks from meeting notes" | The most common Todoist-plus-Littlebird use case: a task surfaces in a meeting and capturing it requires stopping, switching apps, and logging it before the moment passes. Hero: Capture tasks without stopping -- the entire page is built around this single write capability. | Capture tasks without stopping (hero), Update existing tasks | Different from `daily-planning` (in-the-moment capture vs morning planning ritual). Different from `weekly-review` (real-time capture vs retrospective). The write capability is the exclusive hero. | **S:4 D:3 C:2 = 9** |
| `todoist/daily-planning` | "Todoist daily planning AI", "morning planning Todoist AI", "AI plan my day Todoist" | The morning ritual: what is due today, what is overdue, what should I prioritize? Pain: opening Todoist, scanning every project, making a plan in your head. Hero: Find tasks by date (today/overdue) + Get an overview of your plate (full picture) + Move a task to a new date (reschedule the ones that will slip). | Find tasks by date (hero), Get an overview of your plate (hero), Move a task to a new date | Different from `meeting-task-capture` (planning ritual vs in-the-moment capture). Different from `weekly-review` (daily scope + forward-looking vs weekly scope + backward-looking). | **S:4 D:3 C:3 = 10** |
| `todoist/weekly-review` | "Todoist weekly review AI", "Todoist AI week recap", "what did I finish in Todoist this week" | The end-of-week retrospective: what did I complete, what is still open, what do I need to reschedule. Hero: Find what you have finished (completed task log) + Get an overview of your plate (open items) + Move a task to a new date (carry forward). | Find what you have finished (hero), Get an overview of your plate, Move a task to a new date | Different from `daily-planning` (weekly retrospective vs daily forward plan). Different from `meeting-task-capture` (backward-looking ritual vs in-the-moment capture). | **S:3 D:3 C:3 = 9** |
| `todoist/for-founders` | "Todoist AI founder", "AI personal task management founder", "founder productivity Todoist AI" | Founders using Todoist as their personal operating system. Pain: tasks come from everywhere (meetings, Slack, investors, thoughts) and Todoist is where it all lands -- but getting it in and staying current requires constant attention. Hero: Capture tasks without stopping (multi-source capture) + Get an overview of your plate (morning brief on personal system). | Capture tasks without stopping (hero), Get an overview of your plate, Find tasks by date | Different from `daily-planning` (founder-specific pain framing: chaos from multiple directions vs routine planning). Different from `for-freelancers` (founder owns a company vs freelancer owns client work; investor/board commitments angle). | **S:3 D:3 C:3 = 9** |
| `todoist/for-freelancers` | "Todoist AI freelancer", "track client work Todoist AI", "freelancer task management AI Todoist" | Freelancers using Todoist to track deliverables across multiple clients. Pain: weekly review means proving what you did (billable hours, completed deliverables) and staying on top of each client's next ask. Hero: Find what you have finished (deliverable log / proof of work) + Find tasks by date (client deadlines). | Find what you have finished (hero), Find tasks by date, Find your projects | Different from `for-founders` (multi-client deliverable tracking vs company operational chaos). Different from `weekly-review` (billing and client accountability angle vs general retrospective). | **S:3 D:3 C:2 = 8** |
| `todoist/for-consultants` | "Todoist AI consultant", "AI task management consulting Todoist", "track client deliverables Todoist AI" | Consultants who use Todoist as their personal task layer (separate from client-facing project management in Asana or ClickUp). Pain: tasks from client meetings pile up; knowing what is due for which client requires cross-project scanning. Hero: Find tasks by date + Find your projects (per-client project overview) + Capture tasks without stopping (from client meetings). | Find tasks by date (hero), Find your projects, Capture tasks without stopping | Different from `for-freelancers` (consulting engagement framing vs billable deliverable framing; also different search query population). Different from `meeting-task-capture` (multi-client workflow context vs moment-of-capture). | **S:3 D:2 C:3 = 8** |
| `todoist/for-personal-productivity` | "Todoist AI personal productivity", "AI task manager Todoist", "reduce anxiety tasks Todoist AI" | Broad appeal: people using Todoist to manage their whole life (work, personal, family, health). The anxiety-reduction angle: "I know it is all in Todoist but I still feel like I am forgetting things." Hero: Get an overview of your plate (complete picture across ALL projects, not just work). | Get an overview of your plate (hero -- full-life view), Find tasks by date, Search across everything | Different from `daily-planning` (the anxiety/overwhelm pain frame vs the planning ritual frame; "feeling on top of it" vs "planning my day"). Different from `for-founders` (whole-life personal system vs founder operational chaos). | **S:3 D:2 C:2 = 7** |

---

## TICKTICK (4 sub-spokes)

Note: TickTick has the same depth as Todoist (12 caps) but a smaller market presence in the Littlebird user base. Four tightly scoped sub-spokes -- prioritize quality over breadth. TickTick's specific differentiators vs Todoist: lists-based organization, strong student user base, Read full task details as an extra read capability.

Verified capability set:
READ: Find your tasks | Find your lists | Find tasks by date | Get an overview of your plate | Search across TickTick | Find what you have finished | Read full task details
WRITE: Capture tasks without stopping | Update existing tasks | Mark a task complete | Create a new list | Move a task to a new date

| Slug | Search intent / keyword | Distinct angle | Key capabilities (Bible-verified) | Anti-duplication note | Priority |
|---|---|---|---|---|---|
| `ticktick/meeting-task-capture` | "capture tasks from meetings TickTick", "TickTick AI meeting tasks", "create TickTick tasks automatically" | Parallel to the Todoist version but targets the committed TickTick user. Pain and hero are the same (Capture tasks without stopping) but the ICP is a TickTick user who would not search "Todoist AI." | Capture tasks without stopping (hero), Update existing tasks, Create a new list | Targets a separate search population from `todoist/meeting-task-capture`. Cross-integration duplication is acceptable -- different tools, different users. Within TickTick: different from `daily-planning` (capture moment vs planning ritual) and `weekly-review` (real-time vs retrospective). | **S:4 D:3 C:2 = 9** |
| `ticktick/daily-planning` | "TickTick AI daily planning", "morning planning TickTick AI", "plan my day TickTick AI" | The morning planning ritual with TickTick's lists-based structure. Hero: Find tasks by date + Get an overview of your plate across all lists. The "lists" vocabulary distinguishes this from Todoist (projects) -- a TickTick power user will recognize "lists" as theirs. | Find tasks by date (hero), Get an overview of your plate (hero), Find your lists | Different from `meeting-task-capture` (planning ritual vs capture moment). Different from `weekly-review` (forward-looking daily vs backward-looking weekly). Within the TickTick sub-spoke set, the daily planning angle anchors the capture page. | **S:3 D:3 C:3 = 9** |
| `ticktick/for-students` | "TickTick AI student", "student task management TickTick AI", "AI study planner TickTick" | TickTick has an unusually strong student user base (common recommendation in student productivity communities). Students use TickTick for assignment tracking across classes, each class as a list. Pain: "what is due this week across all my classes?" Hero: Find tasks by date (assignments by deadline) + Find your lists (each list = a class) + Read full task details (assignment details). | Find tasks by date (hero), Find your lists (hero -- class-as-list angle), Read full task details | The ONLY student-ICP page in the entire sub-spoke map. Distinct ICP, distinct vocabulary (classes as lists), distinct pain frame (academic deadlines vs work tasks). Different from all other TickTick sub-spokes in ICP and artifact type. | **S:3 D:3 C:3 = 9** |
| `ticktick/weekly-review` | "TickTick weekly review AI", "TickTick AI week recap", "what did I finish TickTick this week" | The end-of-week retrospective for TickTick users. Hero: Find what you have finished + Get an overview of your plate. TickTick-specific: reviewing completed tasks ACROSS lists (not just one project), which is a specific TickTick organizational pattern. | Find what you have finished (hero), Get an overview of your plate, Find your lists | Targets the TickTick user doing a weekly review -- different search population from `todoist/weekly-review`. Within TickTick: different from `daily-planning` (weekly scope vs daily scope) and `meeting-task-capture` (retrospective vs capture). | **S:3 D:2 C:2 = 7** |

---

## LINEAR (8 sub-spokes)

Verified capability set:
READ: List issues across your workspace | Read the full details of any issue | List teams | List projects | Read workflow statuses | List workspace members | Read issue comments | Read issue labels
WRITE: Create or update an issue

| Slug | Search intent / keyword | Distinct angle | Key capabilities (Bible-verified) | Anti-duplication note | Priority |
|---|---|---|---|---|---|
| `linear/standup-prep` | "Linear AI standup", "daily standup Linear AI", "AI Linear issue status standup" | The most common engineering team use case for Linear-plus-Littlebird. Pain: "what issues moved status yesterday for my team?" requires opening Linear and scanning the board before a standup. Hero: List issues (filtered by team + date) + Read the full details of any issue. | List issues across your workspace (hero), Read the full details of any issue, Read workflow statuses, List teams | Different from `for-engineering-managers` (individual IC what-did-my-team-do vs EM management visibility). Different from `sprint-planning` (daily report vs sprint setup). | **S:4 D:3 C:3 = 10** |
| `linear/for-engineering-managers` | "Linear AI engineering manager", "team velocity Linear AI", "AI engineering team status Linear" | EMs need a cross-team view: what are all teams working on, where is each project, who is carrying too many issues. Hero: List teams + List projects + List issues (cross-team filter) + List workspace members. | List teams (hero), List projects (hero), List issues across your workspace, List workspace members | Different from `standup-prep` (org-level oversight vs team-level daily report). Different from `for-founders-and-ctos` (team operational visibility vs architecture/health signals). | **S:4 D:3 C:3 = 10** |
| `linear/sprint-planning` | "Linear sprint planning AI", "AI plan sprint Linear", "Linear backlog grooming AI" | Engineering teams setting up a sprint: pulling issues from the backlog, reviewing labels and priorities, assigning. Hero: List issues (backlog view) + Read issue labels (priority/type signals) + Read the full details of any issue (scope assessment) + Create or update an issue (set priority, assign). | List issues across your workspace (hero), Read issue labels (hero -- priority/type filter), Read the full details of any issue, Create or update an issue | Different from `standup-prep` (setup before the sprint vs daily reporting during it). Different from `issue-triage` (sprint scope planning vs backlog health maintenance). | **S:4 D:3 C:3 = 10** |
| `linear/for-product-managers` | "Linear AI product manager", "AI feature tracking Linear", "roadmap visibility Linear AI" | PMs using Linear for feature tracking and roadmap management. Pain: "what is the status on feature X?" requires switching to Linear and filtering by project. Hero: List projects (roadmap view) + List issues (feature-level tracking) + Read issue comments (decision context). | List projects (hero), List issues across your workspace, Read issue comments, Read the full details of any issue | The ONLY sub-spoke where the ICP is non-technical. PMs use Linear but do not file PRs or attend standups the way engineers do. Different pain from `for-engineering-managers` (product roadmap visibility vs engineering team ops). | **S:4 D:3 C:3 = 10** |
| `linear/for-founders-and-ctos` | "Linear AI for CTO", "engineering org health Linear AI", "Linear AI startup CTO technical overview" | Technical founders and CTOs need a high-altitude view: what shipped this sprint, what are the big bets, are there systemic issues. Hero: List projects (org-level roadmap) + List issues (scope of active work) + Read issue comments (where are the hard decisions being made?). | List projects (hero), List issues across your workspace, Read issue comments, List teams | Different from `for-engineering-managers` (architecture and org-health angle vs team-level operational visibility). Different from `for-product-managers` (engineering output and org signals vs product roadmap tracking). | **S:3 D:3 C:3 = 9** |
| `linear/meeting-notes-to-issues` | "convert meeting notes to Linear issues", "create Linear issues from meeting AI", "AI meeting action items Linear" | The write-focused Linear use case: a meeting produces action items that should become Linear issues. Hero: Create or update an issue as the exclusive write capability -- this page demonstrates that Littlebird can write to Linear, not just read it. | Create or update an issue (hero -- ONLY write capability in Linear's set) | The ONLY sub-spoke in the Linear set where a write capability is the hero. Every other Linear sub-spoke is read-dominant. Different from `standup-prep` and all other sub-spokes which are about reading context, not creating issues. | **S:3 D:3 C:2 = 8** |
| `linear/issue-triage` | "Linear issue triage AI", "AI triage Linear backlog", "prioritize Linear issues AI" | Engineering and product teams with a growing backlog who need to triage: identify unlabeled issues, surface stale items, find duplicates. Hero: Read issue labels + List issues (no-label filter) + Read the full details of any issue (assess staleness). | Read issue labels (hero), List issues across your workspace, Read the full details of any issue | The ONLY sub-spoke where Read issue labels is the primary hero. Different from `sprint-planning` (ongoing backlog health vs periodic sprint setup). Different from `standup-prep` (housekeeping task vs reporting task). | **S:3 D:3 C:3 = 9** |
| `linear/for-developers` | "Linear AI developer workflow", "AI Linear issues individual engineer", "what are my Linear issues AI" | Individual engineers who want a personal view of their issue queue without opening Linear. Pain: "what issues are assigned to me and what is in-progress?" Hero: List issues (filtered by assignee = me) + Read the full details of any issue + Read issue comments (find the unresolved decisions blocking my work). | List issues across your workspace (hero -- personal filter), Read the full details of any issue, Read issue comments | Different from `standup-prep` (personal issue queue in isolation vs team standup context). Different from `for-engineering-managers` (IC personal view vs management team view). The "what are MY issues" angle is distinct from team-level views. | **S:3 D:2 C:3 = 8** |

---

## Ranked build queue -- top 50 by priority

Tier 1 (priority 10): Build first this week.

| Rank | Slug | Priority | Integration |
|---|---|---|---|
| 1 | `github/pr-review` | 10 | GitHub |
| 2 | `github/standup-prep` | 10 | GitHub |
| 3 | `github/code-search` | 10 | GitHub |
| 4 | `github/for-product-managers` | 10 | GitHub |
| 5 | `github/for-engineering-managers` | 10 | GitHub |
| 6 | `notion/meeting-notes` | 10 | Notion |
| 7 | `notion/for-product-managers` | 10 | Notion |
| 8 | `clickup/for-project-managers` | 10 | ClickUp |
| 9 | `clickup/sprint-status` | 10 | ClickUp |
| 10 | `asana/for-project-managers` | 10 | Asana |
| 11 | `todoist/daily-planning` | 10 | Todoist |
| 12 | `ticktick/meeting-task-capture` | 9 | TickTick |
| 13 | `linear/standup-prep` | 10 | Linear |
| 14 | `linear/for-engineering-managers` | 10 | Linear |
| 15 | `linear/sprint-planning` | 10 | Linear |
| 16 | `linear/for-product-managers` | 10 | Linear |

Tier 2 (priority 9): Build second.

| Rank | Slug | Priority | Integration |
|---|---|---|---|
| 17 | `notion/knowledge-recall` | 9 | Notion |
| 18 | `notion/for-founders` | 9 | Notion |
| 19 | `notion/database-queries` | 9 | Notion |
| 20 | `notion/for-consultants` | 9 | Notion |
| 21 | `github/onboarding` | 9 | GitHub |
| 22 | `github/release-notes` | 9 | GitHub |
| 23 | `github/issue-triage` | 9 | GitHub |
| 24 | `github/debugging-context` | 9 | GitHub |
| 25 | `clickup/meeting-task-capture` | 9 | ClickUp |
| 26 | `clickup/for-agencies` | 9 | ClickUp |
| 27 | `asana/standup-prep` | 9 | Asana |
| 28 | `todoist/meeting-task-capture` | 9 | Todoist |
| 29 | `todoist/weekly-review` | 9 | Todoist |
| 30 | `todoist/for-founders` | 9 | Todoist |
| 31 | `ticktick/daily-planning` | 9 | TickTick |
| 32 | `ticktick/for-students` | 9 | TickTick |
| 33 | `linear/for-founders-and-ctos` | 9 | Linear |
| 34 | `linear/issue-triage` | 9 | Linear |

Tier 3 (priority 7--8): Build third, if capacity allows this week.

| Rank | Slug | Priority | Integration |
|---|---|---|---|
| 35 | `notion/for-marketing-teams` | 8 | Notion |
| 36 | `notion/for-engineers` | 7 | Notion |
| 37 | `github/for-founders-and-ctos` | 8 | GitHub |
| 38 | `clickup/standup-prep` | 8 | ClickUp |
| 39 | `clickup/for-marketing-teams` | 8 | ClickUp |
| 40 | `asana/meeting-task-capture` | 8 | Asana |
| 41 | `asana/for-marketing-teams` | 8 | Asana |
| 42 | `asana/weekly-review` | 8 | Asana |
| 43 | `asana/for-consultants` | 8 | Asana |
| 44 | `asana/sprint-planning` | 8 | Asana |
| 45 | `todoist/for-freelancers` | 8 | Todoist |
| 46 | `todoist/for-consultants` | 8 | Todoist |
| 47 | `todoist/for-personal-productivity` | 7 | Todoist |
| 48 | `ticktick/weekly-review` | 7 | TickTick |
| 49 | `linear/meeting-notes-to-issues` | 8 | Linear |
| 50 | `linear/for-developers` | 8 | Linear |

---

## Cut log -- candidates eliminated before the final 50

The following angles were considered and cut. Reason codes: T = thin (not enough distinct capabilities to support a substantively different page), D = duplicative (too similar to another sub-spoke for the same integration), N = not a strong search query, ICP = ICP doesn't naturally use this tool for this purpose.

| Cut slug | Reason | Notes |
|---|---|---|
| `notion/for-developers` | D + ICP | Too close to `notion/for-engineers`. Merged into that sub-spoke. |
| `notion/for-sales-teams` | T | No CRM-write capabilities in Notion's verified set. Query databases covers the read angle; no distinct write use case. |
| `github/for-designers` | ICP | Designers rarely use GitHub APIs. The page would be thin and the ICP doesn't search this. |
| `github/for-remote-teams` | T | "Remote teams" is not a capability-grounded angle -- it is a context, not a workflow problem. |
| `github/ci-debugging` | T | CI debugging requires GitHub Actions / CI system data not in the verified cap set. Would require invented claims. |
| `clickup/for-engineering-managers` | ICP | Engineers tend toward Linear or GitHub for issue tracking. ClickUp EM pages would be thin vs the Linear/GitHub equivalents. Collapsed into `clickup/sprint-status`. |
| `clickup/task-management` | D | Too close to the main ClickUp integration page. No distinct angle. |
| `clickup/for-founders` | ICP | Founders tend toward Notion or Todoist. ClickUp is a team/PM tool; founder use case is thin. |
| `asana/for-developers` | ICP | Developers prefer Linear for issue tracking. Asana dev use case would compete with `linear/for-developers` but with weaker capability support. |
| `asana/for-founders` | ICP | Founders primarily use Notion or Todoist. Asana is a team project tool; founder use case is thin. |
| `asana/for-engineering-teams` | D | Merged into `asana/sprint-planning`. The IC engineer-in-Asana angle is covered by `standup-prep`. |
| `todoist/team-collaboration` | T | Todoist is a personal task tool. Team collaboration angle requires team-specific capabilities not in the verified set. |
| `todoist/for-project-managers` | ICP | PMs use Asana, ClickUp, or Linear -- not Todoist -- as their primary project management tool. Personal Todoist + PM role is thin. |
| `todoist/inbox-zero-for-tasks` | T | Too close to `daily-planning`. No distinct capability hero. |
| `ticktick/for-personal-productivity` | D | Duplicate of `daily-planning` with a different label. No distinct capability hero or pain frame. |
| `ticktick/for-adhd` | T + sensitivity | TickTick's capabilities do not uniquely support an ADHD-specific angle beyond what `meeting-task-capture` and `daily-planning` already cover. ADHD framing adds sensitivity risk without a distinct capability anchor. Consider as a future use-case page (not integration sub-spoke) once the user persona content is developed. |
| `linear/daily-standup` | D | Duplicate of `linear/standup-prep`. Same capabilities, same pain, same ICP. |
| `linear/for-scrum-masters` | T | Scrum master use case is covered by `sprint-planning` and `standup-prep`. No distinct capability set. |

---

## Distribution summary

| Integration | Sub-spoke count | Priority tier (avg) | Notes |
|---|---|---|---|
| Notion | 8 | Strong -- 2 at P10, 4 at P9 | Deepest knowledge-tool angle coverage |
| GitHub | 10 | Strongest -- 5 at P10, 4 at P9 | Most capability-rich integration; widest ICP range |
| ClickUp | 6 | Good -- 2 at P10, 2 at P9 | Team tool; ICP is project managers and team leads |
| Asana | 7 | Good -- 1 at P10, 2 at P9 | Strong marketing-team and consultant angles |
| Todoist | 7 | Good -- 1 at P10, 3 at P9 | Best for personal productivity ICPs |
| TickTick | 4 | Solid -- 0 at P10, 3 at P9 | Kept tight; student angle is a genuine differentiator |
| Linear | 8 | Strongest -- 4 at P10, 3 at P9 | Dev/PM toolset; cleanest capability-to-angle mapping |
| **Total** | **50** | | |

---

## What to validate before generating

1. **Confirm Yash's two-fact requirement is resolved first** -- every sub-spoke will need to carry the "requires Littlebird Plus" message and the third-party paid tier note. If those facts are not in the data model when we generate, all 50 pages will need a retroactive pass. Recommend finalizing the data model changes before generating any sub-spoke.

2. **Slug format** -- proposed format is `/integrations/[integration-slug]/[sub-spoke-slug]`, e.g., `/integrations/notion/meeting-notes`. Confirm this matches the planned URL structure before generating.

3. **TickTick free-tier question (LOW confidence, flagged)** -- `ticktick/for-students` assumes a free TickTick account can connect. This is unverified. Flag for confirmation before that page goes live (other TickTick sub-spokes are less affected since they don't foreground the plan requirement).

4. **GitHub/for-product-managers tone** -- this page's ICP is non-technical. The copy must avoid engineering vocabulary (diffs, SHA, branch names). Flag for the writer: treat this as a "visibility into engineering output" page, not a code-understanding page.
