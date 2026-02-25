# TMF — Time Management Framework

An AI-powered time management system for non-technical individuals, built on [OpenClaw](https://github.com/openclaw/openclaw).

## What is TMF?

TMF is a **productized setup service** that turns OpenClaw into a personal time management assistant. It combines a structured Trello workflow, AI-driven task processing, and two operational modes — all configured and ready to use.

The core problem: OpenClaw is free, powerful, and viral — but setting it up requires CLI, Docker, API keys, and VPS knowledge. Non-technical people hear about it from technical friends but can't get past the installation screen. TMF bridges that gap.

## Origin Story

TMF was born from Vitaly Kezlya's own chaos. Running multiple businesses (Remote Dev Team, Tavarka AI), a passion project (Combat Sport), and building a personal brand — all while raising four kids — he was drowning in sticky notes, duplicating tasks across desks, and had no factual picture of where his time actually went.

He built a system for himself: an OpenClaw agent ("Nova") connected to Trello, with scheduled planning rituals, mood-based interaction modes, and AI-powered task processing. It worked. Then he realized the same system could work for anyone — if someone set it up for them.

## How It Works

### Two Modes

**Fire Mode** — Execution coaching. The AI delivers one small, time-boxed step at a time. No choices, no lists — just "do this, you have 7 minutes." After each step: "3 of 7 done. Crushing it." Priorities were already set; now you execute.

**Compass Mode** — Strategic thinking. The AI asks questions, considers pros and cons, offers options. Used for weekly planning, grooming sessions, and big decisions. This is where you think — Fire is where you act.

### The Board

A Trello board structured as a pipeline:

```
Inbox/Brain Dump → Backlogs (by project area) → This Week → Next Up → In Progress → Needs Review → Done → Archive
```

OpenClaw processes brain dumps into structured tickets with custom fields: project area, task type, estimated time, actual time, potential impact, and due date.

### The Rituals

- **Daily** (Mon–Fri 9 AM): AI pulls from "This Week" into "Next Up" for today's focus
- **Weekly** (Sunday 10 PM): Plan next week, move items from backlogs to "This Week"
- **Monthly** (last day): Grooming session — archive completed work, plan the month ahead

### Task Processing

OpenClaw acts as the input driver. When you dump tasks (voice, text, brain dump), it:
1. Rationalizes and deduplicates
2. Creates structured Trello tickets with all custom fields populated
3. Places them in the correct backlog
4. During Fire sessions, serves them one action at a time

## Packages

### Package 1: DIY Setup — $50
Downloadable assets you drag-and-drop into your OpenClaw. Includes SOUL.md template, Trello board template, cron configurations, and prompt library. Requires some technical ability to connect the pieces.

### Package 2: Guided Setup — $150
Everything in Package 1, plus a guided webinar/video walking you through setup step by step. You do it yourself, but with a clear path to follow.

### Package 3: Done-For-You (VIP) — $400
A 90-minute one-on-one session. Vitaly connects with you, sets up the full TMF system, reviews your current OpenClaw configuration, fixes existing bugs, hardens security, and gives personalized recommendations. You walk away with a working system.

## Target Audience

**Non-technical individuals** who:
- Have heard about OpenClaw but can't set it up
- Want an AI personal assistant for real productivity (not just chat)
- Are individuals, not businesses (B2C)
- Are willing to pay a one-time fee rather than a monthly subscription

## Market Context (Feb 2026)

- OpenClaw: 157K+ GitHub stars, the most viral open-source AI project
- Someone made $100K in 3 days selling generic OpenClaw setups at $119
- Global agentic AI market: $9.89B in 2026, growing at 43.8% CAGR
- Personal assistant segment: ~$2.8B (28.2% of market)
- IEEE predicts agentic AI reaches consumer mass market in 2026
- **No one is selling a productized, fixed-price AI time management setup for individuals**

## Repository Structure

```
tmf/
├── docs/              # Product definition, business rules, architecture
├── research/          # Market research, competitor analysis, feature research
│   ├── competitors/
│   ├── market/
│   └── features/
├── marketing/         # Strategy and content for each channel
│   ├── linkedin/
│   ├── youtube/
│   └── skool/
├── sales/             # Sales strategy, pricing, package definitions
│   └── packages/
├── website/           # Website source code
├── content/           # Content ideas and drafts
│   ├── ideas/
│   └── drafts/
├── features/          # Feature ideas and specifications
├── backlog/           # Parked ideas and future plans
└── stats/             # Analytics, what's working, what's not
```

## Content Flywheel

Build product → Serve clients → Collect stories → Create LinkedIn/YouTube/Skool content → Attract new clients → Repeat.

Every client interaction generates content. Every bug fix becomes a tutorial. Every setup challenge becomes a LinkedIn post.
