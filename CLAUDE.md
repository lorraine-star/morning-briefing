# RISE Morning Briefing — Operational Rules for Claude

Read this before every run. These rules override anything in the prompt that's ambiguous.

## Calendar Rules

### Focus blocks (Lorraine's work tasks)
- Create on **primary calendar**: `lorraine@lorraineklee.com`
- Color: blueberry (9) for high priority, graphite (8) for low
- Must be placed INSIDE existing "✅ ASANA / HEADS DOWN" recurring blocks **on the task's due date**
- If no HEADS DOWN block exists on the due date, check the full day calendar for that date and pick the best open slot — do NOT skip the task
- If the due date is today and the ASANA block has already passed, place the block in the next available open slot today
- Check the full day schedule before deciding a slot is unavailable — the initial ASANA search only returns events with Asana URLs in their description
- Do NOT place a focus block earlier than the due date (e.g. do not schedule Monday work for a Wednesday task)

### Deadline markers (Meagan & Mahea team tasks)
- Create on **Current Projects calendar**: `c_b03e66f8a2cf3bd2e82725f1791f1bd7f6aa2b07798f3e284d49034f36d55e85@group.calendar.google.com`
- NEVER on `lorraine@lorraineklee.com` (primary) or any other calendar
- Color: tangerine (6)
- Duration: exactly 15 minutes, at 9:00am PT on the due date
- Summary format: `DEADLINE: [PERSON NAME] — [Task name]`

### What NOT to write to calendars
- Do NOT create or modify events on the Current Projects calendar for Asana-synced project data — that's managed automatically
- Do NOT show Current Projects events as time blocks in the schedule — they are due date markers only

## Asana Rules
- When creating subtasks, do NOT add them to the project — only parent tasks go in projects
- Do NOT create tasks unless the trigger prompt explicitly says to
- Skip all tasks in the "Ideas & Explore Later" project (GID: 1213914805812107)
- Kondo checks and newsletter folder reviews are LOW priority

## Inbox From Lorraine (GID: 1213915874399989)
- "For Meagan" section GID: 1213915874399991 → Meagan's dashboard only
- "For Mahea" section GID: 1213915874399994 → Mahea's dashboard only
- Never cross-show tasks between sections

## Team Ownership
- **Meagan** owns: proposals, lead follow-ups, Forbes articles, speaking pipeline, course marketing emails, client communications
- **Mahea** owns: newsletters, social calendar, Instagram, sponsored posts, affiliate links, website content, brand analytics
- Always use the Asana assignee field to confirm ownership — do not infer from email threads

## Dashboard HTML Rules
- Each file must stay under 300 lines
- No blank lines in CSS blocks
- Push to `lorraine-star/morning-briefing` on GitHub after every run

## MCP Connections
- If Asana, Gmail, or Google Calendar tools are missing at session start, surface this clearly in the dashboards rather than silently running with placeholder data
- Do not retry indefinitely — note the failure and proceed with Job 2 (dashboards)
