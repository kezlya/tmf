# TMF Product Definition

## What TMF Is

TMF (Time Management Framework) is a productized, fixed-price AI-powered time management **setup service** for non-technical individuals. It wraps a proven OpenClaw + Trello configuration into sellable packages.

TMF is NOT:
- A SaaS product (no recurring subscription)
- A new tool or platform (it configures existing tools)
- A course about productivity theory
- An enterprise or B2B product

TMF IS:
- A one-time purchase that delivers a working system
- A methodology + technical setup combined
- A bridge between "I heard about AI assistants" and "I use one daily"

## Core Components

### 1. OpenClaw Agent Configuration
A pre-configured SOUL.md that defines the AI assistant's personality and behavior rules, including:
- Fire Mode (execution coaching) and Compass Mode (strategic brainstorming)
- Session detection (standalone message vs. working session)
- Mood check protocol
- Channel-aware communication (work channel vs. personal channel)
- Progress tracking and motivational feedback

### 2. Trello Board Structure
A 10-column pipeline designed for personal task management:

| Column | Purpose |
|--------|---------|
| Inbox/Brain Dump | Raw ideas, voice notes, sticky note captures |
| Backlog (per project area) | Categorized task pools |
| This Week | Selected during weekly Sunday planning |
| Next Up | Today's focused work items |
| In Progress | Currently active |
| Needs Testing/Review | Done but not validated |
| Done (Ready for Archive) | Completed, awaiting monthly archival |

Plus a separate archive board with monthly columns.

### 3. Custom Fields for Data-Driven Analysis
Every ticket is tagged with:
- **Project Area**: Which life/work domain
- **Task Type**: Bug, Feature, Content, Hiring, Sales, Admin, Research
- **Potential Impact**: DirectRevenue, AudienceGrowth, PersonalSatisfaction, OperationalEfficiency, StrategicAdvantage
- **Estimated Time**: 1h, 4h, 1d, 3d
- **Actual Time Spent**: Updated during/after work
- **Frequency Score**: How many times this task was written down (higher = more pressing)
- **Due Date**: Standard deadline

### 4. Scheduled Rituals (Cron Jobs)
- **Daily Planning** (Mon-Fri 9 AM): AI pulls from "This Week" into "Next Up"
- **Weekly Planning** (Sunday 10 PM): Review backlogs, select tasks for the week
- **Monthly Grooming** (last day of month, 10 AM): Archive completed work, plan next month

### 5. AI Task Processing
OpenClaw as the input driver:
- Accepts brain dumps (voice, text, unstructured thoughts)
- Rationalizes and deduplicates
- Creates structured Trello tickets with all custom fields
- Routes to correct backlog
- Serves tasks one-at-a-time during Fire sessions
- Facilitates planning during Compass sessions

## Two Operational Modes

### Fire Mode (Execution)
- Army-coach style: direct, no ambiguity
- ONE step at a time — never a numbered list
- Each step is time-boxed ("Do this. You have 7 minutes.")
- Progress rewards after each step ("3 of 7 done. Crushing it.")
- No decision-making — priorities were set in Compass mode
- Steps are small and manageable to prevent overwhelm

### Compass Mode (Strategy)
- Conversational: asks questions, weighs pros and cons
- Offers options for rationalization and decision-making
- Used for weekly planning, grooming, big decisions
- Facilitates deeper understanding and strategic exploration

### Mode Detection Rules
- A single standalone message → just execute it, no mode question
- 3+ messages within 5 minutes → it's a session, ask "Fire or Compass?"
- If user doesn't answer mode question → reset count, try again later

## Prioritization Frameworks (Planned)
- **MoSCoW**: Must have / Should have / Could have / Won't have
- **Eisenhower Matrix**: Urgent+Important / Important+Not Urgent / Urgent+Not Important / Neither
