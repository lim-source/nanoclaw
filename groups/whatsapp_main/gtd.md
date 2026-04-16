# GTD — Getting Things Done (Limor's System)

This is Shaul's reference for helping Limor manage herself using GTD.

---

## The GTD Philosophy

Your brain is for having ideas, not holding them. Everything that has your attention needs to live in a trusted external system. When it does, your mind is clear.

---

## Limor's Asana Setup

Everything lives in the *"Lim"* project (workspace: "Lims Projects").
- Project GID: `1208483063862075`
- Workspace GID: `793442947194`
- ALL tasks are Limor's — regardless of who they are assigned to.

### Sections (in order)

| Section | GID | GTD Role |
|---------|-----|----------|
| InTray | `1208483063862076` | **Capture inbox** — all un-triaged tasks go here |
| must | `1212225994376200` | High priority, non-negotiable |
| SUV what to do when there | `1213992415533770` | Context: in the car (SUV) |
| Today | `1208483636362643` | Tasks for today |
| backlog long | `1208483077103964` | Long-horizon backlog |
| backlog short | `1208483077103965` | Short-horizon backlog |
| today short | `1208483077103967` | Short tasks to do today |
| Wait today | `1213014327291134` | Waiting items relevant today |
| weekend | `1208483077103966` | Weekend tasks |
| waiting for | `1208483077103972` | GTD Waiting For list |
| moran | `1212090486836867` | Agenda for Moran |
| Eyal | `1208483077103968` | Agenda for Eyal |
| סתם דברים ששמרתי | `1208483146377821` | Random saved items / reference |
| קריאה לפני המיטה או בבוקר | `1208483077103973` | Reading before bed or morning |
| ברכבת קריאה | `1208483077103974` | Reading on the train |
| פרויקטים | `1208483077103975` | Projects list |
| listening while walking or cooking | `1208483077103976` | Context: audio while moving |
| call from the car | `1208483636362646` | Context: phone calls from the car |
| things I found that might be helpful for wisdom | `1208483077103977` | Reference for Wisdom product |
| enrichment Read | `1208483077103978` | Enrichment reading list |
| enrichment Read - history | `1208483077103979` | History reading list |
| Someday Maybe Far | `1213387691703671` | GTD Someday/Maybe |
| accessima | `1208483077103981` | Accessima-related |
| new asis | `1213387691703683` | New asis items |

---

## Shaul's GTD Rules

### Capture
- When Limor mentions anything on her mind → add it to **InTray** immediately
- No triage at capture time — just get it in
- Use `mcp__asana__asana_create_task` with `projects: ["1208483063862075"]` and section `1208483063862076`

### Clarify & Organize
After capture (or when Limor asks to process her inbox):
- Is it actionable? → which section does it belong in?
- Is it a project? → add to `פרויקטים` section
- Is it waiting on someone? → `waiting for` section
- Someday, not now? → `Someday Maybe Far`
- Needs to happen today? → `Today` or `today short`
- Context-based: in the car? → `SUV what to do when there` or `call from the car`

### The 2-minute rule
If it takes under 2 minutes → tell Limor to do it now, don't add to Asana.

### Evening Prep (10pm every night)
Run the night before to set Limor up for the next morning.

1. **Clean Today** — the Today section must be empty before sleep:
   - Completed tasks → mark done
   - Unfinished tasks → move to `backlog short`, `backlog long`, or `waiting for` as appropriate
   - Nothing lingers in Today overnight
2. **Load must for tomorrow** — put 1-2 tasks in `must` that Limor should work on first thing in the morning
   - These should be meaningful, not urgent noise
   - 1-2 max — the morning is for deep work, not a long list

### Morning Triage (11am every day)
Limor's mornings are for deep work and family — no interruptions before 11am.

Goal: the **must** section contains ONLY tasks that truly must be done by end of today.

Steps:
1. Look at everything in **must**
2. For each task — ask: "Does this genuinely have to be done today?"
   - Yes → stays in `must`
   - Important but not today-critical → move to `Today`, `backlog short`, or `backlog long`
   - Waiting on someone → move to `waiting for`
   - No longer relevant → complete or delete
3. Result: `must` is a short, honest list. If everything is "must", nothing is.

### Weekly Review (remind Sundays)
1. Clear InTray to zero — triage everything
2. Check every section for stale tasks
3. Review `waiting for` — anything overdue?
4. Review `פרויקטים` — does each project have a next action?
5. Review `Someday Maybe Far` — anything to activate now?

### Creating tasks
Always add to the "Lim" project: `"projects": ["1208483063862075"]`
Specify the section with the `insert_before` or use `asana_set_parent_for_task` as needed.

---

## The 5 Steps (quick ref)

1. **Capture** → InTray
2. **Clarify** → what is it? is it actionable?
3. **Organize** → right section
4. **Reflect** → weekly review (Sundays)
5. **Engage** → pick what to do based on context + energy + time
