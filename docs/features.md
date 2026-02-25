# TMF Features

## Core Features (Included in All Packages)

### Fire Mode
- One-step-at-a-time execution coaching
- Time-boxed steps with countdown awareness
- Progress rewards after each completed step
- No decision fatigue — priorities are pre-set

### Compass Mode
- Strategic brainstorming and planning facilitation
- Pros/cons analysis for decisions
- Weekly and monthly planning sessions
- Goal alignment and reflection

### Structured Trello Pipeline
- 10-column workflow (Inbox → Backlogs → This Week → Next Up → In Progress → Review → Done → Archive)
- Multiple backlogs by project area
- Monthly archiving with year-over-year visibility

### AI Task Processing
- Brain dump → structured tickets (automatic)
- Custom field population (project area, type, impact, time estimate)
- Deduplication and rationalization
- Correct backlog routing

### Scheduled Rituals
- Daily planning (weekday mornings)
- Weekly planning (Sunday evenings)
- Monthly grooming (end of month)

### Custom Ticket Fields
- Project Area, Task Type, Potential Impact
- Estimated vs. Actual Time (for analysis)
- Frequency Score (tracks mental urgency)

### Session Detection
- Distinguishes one-off messages from working sessions
- Automatically asks for mode selection when session detected

## Planned Features (Backlog)

### Prioritization Frameworks
- MoSCoW integration (Must/Should/Could/Won't)
- Eisenhower Matrix overlay (Urgent × Important)

### Analytics Dashboard
- Time distribution across project areas
- Estimated vs. actual time comparison
- Task completion velocity
- Focus pattern identification

### Admin Call Blocking
- Group phone tasks (insurance, doctors, utilities) into dedicated time blocks
- Prevents postponement of low-energy but necessary tasks

### Level-Up System
- Track collaboration quality improvements over time
- Milestone recognition when communication efficiency improves 20%+
- Version-controlled snapshots of system configuration at each level

### Multi-Channel Awareness
- Different messaging channels for different contexts (work vs. personal)
- AI nudges if message tone doesn't match channel context

### Brain Dump Pattern Scanning
- Periodic analysis of brain dump archive
- Identify recurring themes and "loops" (tasks that keep getting rewritten)
- Surface subconscious priorities

### Heartbeat System
- Background agent pings every 30 minutes
- Reads HEARTBEAT.md for standing daily tasks (e.g., relational nudges)
- Tracks state via heartbeat-state.json (last-run timestamps)
- Respects quiet hours (no pings during sleep)
- Self-cleaning reminders (deleteAfterRun: true)

### Voice-to-Schedule Pipeline
- End-of-day voice dictation via Telegram (raw, unstructured)
- AI parses multiple tasks from a single chaotic message
- Creates individual timed reminders spread across next day
- No confirmation needed — high-trust handoff before sleep

### Bulk Reminder Scheduling
- One voice dump → multiple cron jobs with sensible time slots
- AI assigns morning-to-afternoon arc automatically
- Each reminder fires once and self-deletes
