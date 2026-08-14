# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, customer-first approach to project management that moves work from idea to production through clear stages: initiation, planning, execution, release, and retrospective. Initiation focuses on validating business need and defining success metrics with a concise Project One-pager. Planning breaks approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done, and a risk register so the team can plan shippable increments. Execution uses a PR-driven workflow and project board to manage day-to-day delivery, while retrospectives capture learnings and feed continuous improvement.

Roles are explicitly defined so responsibilities are clear: Product Managers own outcomes and success metrics; Project Managers coordinate schedules, risks, and stakeholder communications; Developers implement and test features; and QA validates acceptance. These personas guide who does what at each lifecycle stage and help with onboarding by providing predictable expectations for collaboration and handoffs. Key artifacts—Project One-pagers, backlog items with acceptance criteria, the risk register, release notes, and retrospective action items—serve as the single source of truth and should be kept up to date in this docs/ folder and project board.

Communication follows a regular cadence to keep work visible and risks managed: short daily standups for progress and blockers, weekly delivery syncs to show progress and surface flagged risks, demo/review sessions at the end of sprints or milestones, and periodic stakeholder updates. Templates (for weekly status and incident summaries) and clear escalation paths (team → PM → Product Lead → Sponsor, plus a separate path for security incidents) standardize what gets communicated and when.

Quality assurance and risk control are integrated into the process: CI runs automated tests and security scans before reviews, with expectations for unit tests, integration tests where needed, and end-to-end smoke tests for critical flows prior to release. Manual QA is used for feature acceptance when required. Release checklists (staging smoke tests, rollback plan, post-deploy verifications) and the retrospective practice ensure the team reduces risk over time and improves delivery based on measured outcomes.

## Quick Links to Process Guides

### Fundamentals
- [Project Management Overview](./octoacme-project-management-overview.md) — Core principles, roles, artifacts, and high-level lifecycle
- [Roles and Personas](./octoacme-roles-and-personas.md) — Definitions of Project Manager, Product Manager, Developer, and QA responsibilities

### Project Phases
1. [Project Initiation](./octoacme-project-initiation.md) — Validate business need, align stakeholders, and create a lightweight plan
2. [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, identify dependencies, and align timelines
3. [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution, track progress, and escalate blockers
4. [Release & Deployment](./octoacme-release-and-deployment.md) — Standardize how features reach production with reduced risk
5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements

### Cross-Cutting
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks, dependencies, and stakeholder updates

## How to Use These Docs

- Start with the Project Management Overview for orientation.
- Follow the lifecycle phases in sequence for new projects.
- Use templates and checklists during execution and releases.
- Keep the project charter, risk register, and release notes updated in this folder.
- For Copilot Spaces, consider copying or referencing these docs into `.copilot/` for context-aware assistance.
