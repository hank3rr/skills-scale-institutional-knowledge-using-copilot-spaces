# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation. This folder contains the complete framework and processes used to successfully plan, execute, and deliver projects across the organization.

## Quick Start

New to OctoAcme projects? Start here:

1. Read [OctoAcme Project Management Overview](octoacme-project-management-overview.md) for roles, principles, and the high-level lifecycle
2. Review [OctoAcme Roles & Personas](octoacme-roles-and-personas.md) to understand key team members
3. Explore the process docs below relevant to your current project phase

## OctoAcme Project Management Overview

**OctoAcme Project Lifecycle & Workflows**

OctoAcme operates projects through a structured five-phase lifecycle: Initiation, Planning, Execution, Release, and Close & Retrospective. During Initiation, teams validate business need, identify stakeholders, and create a lightweight Project One-pager with success metrics to make a go/no-go decision. In Planning, approved initiatives are broken into prioritized, estimated backlog items with clear acceptance criteria and a Definition of Done. The Execution phase emphasizes iterative delivery through daily standups, weekly syncs, and a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done). Small pull requests (≤400 lines) are encouraged with required approvals and automated CI checks. The Release phase ensures readiness through pre-deployment checklists, smoke tests, and rollback planning, while the final Retrospective phase captures learnings and converts them into actionable improvements tracked in the backlog.

**Roles, Responsibilities & Communication**

Three core personas drive OctoAcme projects: Project Managers coordinate delivery, manage schedules, risks, and communications; Product Managers define what should be built, prioritize the backlog, and measure outcomes; and Developers implement features, write tests, identify technical risks, and collaborate on design. Communication follows a structured cadence: daily standups (15 min) and twice-weekly delivery team syncs focus on progress and blockers; weekly PM-PdM alignment ensures smooth cross-functional coordination; monthly stakeholder updates provide status visibility; and ad-hoc escalations address critical issues. Teams maintain a single source of truth through project repositories, README documentation, and decision logs to ensure transparency and alignment across all stakeholders.

**Quality Assurance & Risk Management**

Quality is embedded throughout OctoAcme projects via unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for feature acceptance. A Risk Register tracks identified risks by ID, description, impact/probability, owner, and mitigation plan—reviewed weekly during syncs and escalated through three levels: team triage → PM escalation to Product Lead and dependencies → sponsor escalation for business-impacting issues. Dependencies and cross-team risks are marked explicitly on project boards and escalated during weekly syncs. Pre-release requirements mandate that all acceptance criteria are met, PRs merged, CI/security scans passing, and rollback plans documented before deployment.

**Data-Driven Decision Making & Continuous Improvement**

OctoAcme is built on core principles of customer-first focus, iterative delivery, clear ownership, data-informed decisions, and psychological safety. Teams measure velocity and burndown, monitor success metrics identified in the Project One-pager, and use dashboards for key signals (errors, latency, usage). After each sprint, release, or milestone, retrospectives (45–75 min) capture what went well, what could improve, and generate 2–3 prioritized action items with clear owners and due dates. These improvements are tracked in the project backlog and reviewed in weekly PM syncs, creating a continuous feedback loop that evolves processes and practices over time.

## Project Lifecycle

OctoAcme projects follow five key phases. Click on each to learn about the process:

### 1. **Initiation** — Validate the idea and align stakeholders

- **[Project Initiation Guide](octoacme-project-initiation.md)** — Define business need, identify stakeholders, create a one-pager, and make the go/no-go decision

### 2. **Planning** — Turn the approved initiative into an actionable plan

- **[Project Planning](octoacme-project-planning.md)** — Build the backlog, estimate scope, define DoD, identify risks and dependencies

### 3. **Execution** — Build, test, review, and iterate

- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery, team rhythm, quality gates, and blocker escalation
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify and monitor risks, communicate status to stakeholders

### 4. **Release** — Deploy to production

- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Prepare for release, execute deployment, handle rollbacks

### 5. **Close & Improve** — Capture learnings

- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Run retros, track action items, measure impact

## Core Principles

All OctoAcme processes are built on these principles:

- **Customer-first** — Prioritize customer value and usability
- **Iterative delivery** — Ship small, testable increments
- **Clear ownership** — Each project has a named PM and Product Lead
- **Data-informed** — Measure impact and iterate based on evidence
- **Psychological safety** — Encourage feedback and learning

## Key Artifacts

- **Project Charter / One-pager** — Business case and success criteria
- **Roadmap & Release Plan** — Timeline and milestones
- **Sprint/Iteration Backlog** — Prioritized work items with acceptance criteria
- **Risk Register** — Identified risks, impact, and mitigation plans
- **Retrospective Notes** — Learnings and action items

## Key Roles

### Project Manager (PM)
Coordinates delivery, schedules, risks, and communications. Creates and maintains project plans and timelines, manages risks and dependencies, facilitates key meetings, and ensures transparent status reporting.

### Product Manager (PdM)
Defines outcomes, prioritizes the backlog, and measures success. Owns the product vision, validates solutions through research and metrics, and ensures product-market fit and usability.

### Developers
Implement features, write and maintain tests, participate in design and code reviews, assist in estimation, and identify technical risks and mitigations.

### QA/Testing
Validates quality and acceptance criteria, ensures test coverage, and confirms feature acceptance before release.

## Communication Cadence

- **Daily** — 15-minute standups (focus on progress, blockers, dependencies)
- **Twice-weekly** — Delivery team syncs for execution teams
- **Weekly** — PM + PdM alignment for cross-functional coordination
- **Monthly** — Stakeholder updates for visibility and alignment
- **Ad-hoc** — Escalations and incident communications as needed

## Questions?

Refer to the specific process doc for your phase, or reach out to your Project Manager or Product Lead.
