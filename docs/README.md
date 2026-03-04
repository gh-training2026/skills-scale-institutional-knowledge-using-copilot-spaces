# OctoAcme Project Management — Docs Overview

Welcome to the OctoAcme project management documentation. This README provides a quick orientation for new teammates so you can understand how we run projects before diving into the detailed guides.

---

## Core Principles

- **Customer-first**: Prioritize customer value and usability in every decision.
- **Iterative delivery**: Ship small, testable increments rather than big-bang releases.
- **Clear ownership**: Every project has a named Project Manager (PM) and Product Lead.
- **Data-informed decisions**: Measure impact and iterate based on evidence.
- **Psychological safety**: Encourage open feedback and continuous learning.

---

## Roles and Responsibilities

| Role | Primary Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, manages schedules, risks, and cross-team communication. |
| **Product Manager (PdM)** | Defines outcomes, owns the roadmap and backlog, and measures success metrics. |
| **Developers** | Implement features, write tests and documentation, participate in design and code reviews. |
| **QA / Testing** | Validate quality and acceptance criteria; run smoke tests before releases. |
| **Stakeholders** | Provide inputs, approvals, and business context throughout the project. |

See [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) for detailed persona descriptions.

---

## Project Lifecycle (High-Level)

1. **Initiation** — Validate the business need; create a Project One-pager with problem statement, goals, success metrics, stakeholders, and a high-level timeline. Decide go/no-go before moving forward.
2. **Planning** — Break work into a prioritized backlog with acceptance criteria; define the Definition of Done, release plan, milestones, and risk register.
3. **Execution** — Build, test, and review work in short iterations using the project board (Backlog → Ready → In Progress → In Review → QA → Done). Run daily standups and weekly delivery syncs.
4. **Release** — Meet pre-release requirements (CI passing, release notes drafted, rollback plan ready), deploy to staging then production, and announce to stakeholders.
5. **Close & Retrospective** — Capture what went well and what to improve; assign owners to action items and track them in the backlog.

---

## Communication Cadence

| Cadence | Participants | Purpose |
|---|---|---|
| Daily standup (15 min) | Delivery team | Progress, blockers, dependencies |
| Weekly PM + PdM sync | PM, PdM | Alignment, risk review, action items |
| Weekly stakeholder status | PM → Stakeholders | Progress update, risks, decisions needed |
| Sprint demo / review | Team + stakeholders | Demonstrate completed work |
| Monthly stakeholder update | PM → Broader stakeholders | Roadmap progress and outlook |
| Ad-hoc escalation | PM → Product Lead → Sponsor | Business-impacting blockers |

---

## Key Process Artifacts

| Artifact | Description |
|---|---|
| **Project One-pager / Charter** | Problem statement, goals, success metrics, stakeholders, timeline |
| **Roadmap & Release Plan** | Milestones, release types (patch / minor / major), timelines |
| **Sprint / Iteration Backlog** | Prioritized items with acceptance criteria, estimates, and owners |
| **Definition of Done (DoD)** | Agreed quality bar for completed work |
| **Risk Register** | ID, description, impact, likelihood, owner, mitigation, status |
| **Release Notes** | Summary of changes, migration steps, known issues |
| **Retrospective Notes** | What went well, improvements, action items with owners and due dates |

---

## Detailed Guides

| Guide | Description |
|---|---|
| [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) | High-level overview of principles, roles, lifecycle, and artifacts |
| [octoacme-project-initiation.md](./octoacme-project-initiation.md) | Initiation checklist, One-pager template, and decision gate |
| [octoacme-project-planning.md](./octoacme-project-planning.md) | Planning activities, backlog template, sprint planning, and DoD |
| [octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md) | Day-to-day workflows, PR conventions, quality practices, escalation paths |
| [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) | Release types, deployment checklist, rollback playbook, release notes template |
| [octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure, running the session, tracking improvements |
| [octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md) | Risk register format, risk lifecycle, stakeholder communication templates |
| [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) | Detailed role descriptions for Developers, Product Managers, and Project Managers |
