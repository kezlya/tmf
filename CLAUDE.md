# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repo Is

TMF (Time Management Framework) is a **product business**, not just a codebase. This repo manages everything: website source code, product packages, marketing strategy, sales, research, content, and all knowledge about the product.

TMF is a productized AI-powered time management setup service for non-technical individuals, built on OpenClaw. It sells in three tiers: $50 DIY, $150 Guided, $400 Done-For-You.

## Repository Structure

```
tmf/
├── docs/                  # Product definition, business rules, features, audience
├── research/              # Market research and analysis
│   ├── competitors/       # Competitive landscape
│   ├── market/            # Market sizing, trends, OpenClaw ecosystem
│   └── features/          # Feature-specific research
├── marketing/             # Channel strategies
│   ├── linkedin/          # LinkedIn posts, strategy
│   ├── youtube/           # Video concepts, scripts
│   └── skool/             # Community strategy
├── sales/                 # Sales strategy and package definitions
│   └── packages/          # Detailed package specs
├── website/               # Website source code (TBD)
├── content/               # Content pipeline
│   ├── ideas/             # Raw content ideas
│   └── drafts/            # Work-in-progress content
├── features/              # Feature specs and ideas
├── backlog/               # Parked ideas and future plans
└── stats/                 # Analytics and performance tracking
```

## Key Context

- **Owner**: Vitaly Kezlya — runs Remote Dev Team (staffing), Tavarka AI (startup), Combat Sport (passion project), and personal brand
- **Target audience**: Non-technical individuals who want OpenClaw but can't set it up
- **Business model**: One-time purchase (NOT subscription) — this is a key differentiator
- **Market timing**: OpenClaw hype is at peak (Feb 2026, 157K+ GitHub stars). Speed to market matters.
- **Content flywheel**: Client work → content → new clients. Every interaction generates LinkedIn/YouTube/Skool material

## Product Concepts to Know

- **Fire Mode**: Execution coaching — one step at a time, time-boxed, no choices
- **Compass Mode**: Strategic brainstorming — questions, options, pros/cons
- **The Board**: 10-column Trello pipeline (Inbox → Backlogs → This Week → Next Up → In Progress → Review → Done → Archive)
- **Rituals**: Daily planning (9 AM), weekly planning (Sunday 10 PM), monthly grooming (last day)
- **Task Processing**: OpenClaw as input driver — brain dumps become structured Trello tickets

## Working in This Repo

This is a mixed repo — code AND documentation. When asked to:
- **Research**: Save findings as markdown in `research/` with appropriate subfolder
- **Brainstorm marketing**: Save in `marketing/<channel>/`
- **Draft content**: Save in `content/drafts/`
- **Define features**: Save in `features/` or update `docs/features.md`
- **Track what works**: Save in `stats/`
- **Park ideas**: Save in `backlog/`

All documentation is Markdown. Keep files focused and scannable. Use the existing docs as reference for product details, business rules, and audience definition.

## Key Documents

- `README.md` — Product overview and origin story
- `docs/product-definition.md` — Detailed product spec (modes, board, fields, rituals)
- `docs/business-rules.md` — Pricing model, market rules, timing constraints
- `docs/audience.md` — Target personas, pain points, adoption funnel
- `docs/features.md` — Core and planned features
- `sales/packages/packages.md` — Package definitions and competitive positioning
- `research/competitors/competitive-landscape.md` — Full competitor analysis
- `research/market/openclaw-market-analysis.md` — OpenClaw market and demand data
