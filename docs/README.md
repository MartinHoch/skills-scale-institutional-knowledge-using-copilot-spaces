# OctoAcme Project Management Processes

## Overview

OctoAcme follows a structured yet flexible project management approach designed around core principles:
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named PM and Product Lead roles
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## OctoAcme Project Management Summary

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The framework consists of five distinct phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. Each phase is supported by lightweight but comprehensive artifacts—including a Project One-pager, prioritized backlog, risk register, and release notes—that serve as a single source of truth for stakeholders. The approach prioritizes psychological safety, data-informed decisions, and transparency, with success measured against pre-defined metrics established during the initiation phase.

Core roles are clearly defined to ensure accountability and effective collaboration. The **Project Manager (PM)** coordinates delivery, schedules, and risk management; the **Product Manager (PdM)** owns outcomes, prioritizes the backlog, and measures success; **Developers** implement features and contribute to design and testing; and **QA/Testing** validates quality against acceptance criteria. This cross-functional structure is reinforced by a consistent communication cadence: daily standups (15 min) focused on progress and blockers, weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates. Escalation follows a clear four-level path (team-level → PM → Product Lead → Sponsor) to resolve blockers efficiently without creating bottlenecks.

Quality and execution rigor are embedded throughout the lifecycle. During planning, teams establish a Definition of Done and acceptance criteria for all backlog items; during execution, small pull requests (≤400 lines) with automated testing and linting gate the process before requiring at least one approval. The project board (e.g., GitHub Projects) maintains visibility with columns for Backlog, Ready, In Progress, In Review, QA, and Done. Pre-release requirements—including passing CI, security scans, and smoke tests—minimize deployment risk, and a documented rollback plan ensures rapid response to production incidents.

Finally, OctoAcme embeds continuous improvement into its culture through structured retrospectives after each sprint, release, or milestone. These retrospectives capture learnings, prioritize 2–3 actionable improvements, assign clear owners and due dates, and track impact against previous action items. Combined with regular risk monitoring, weekly status updates using a standardized template, and a blameless incident retrospective process, this creates a learning organization that iteratively refines both its delivery processes and product quality.

## Process Documentation

OctoAcme projects follow a lifecycle from initiation through retrospective. Use the guides below to navigate each phase:

### Project Lifecycle

1. [Project Initiation Guide](./octoacme-project-initiation.md) — Validate business need, align stakeholders, create lightweight plan
2. [Project Planning](./octoacme-project-planning.md) — Break work into shippable increments, identify dependencies and risks
3. [Execution & Tracking](./octoacme-execution-and-tracking.md) — Manage day-to-day execution, track progress, handle blockers
4. [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize releases and deployments to reduce risk
5. [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert to actionable improvements

### Cross-functional Guidance

- [Project Management Overview](./octoacme-project-management-overview.md) — High-level introduction to roles, artifacts, and lifecycle
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Personas & Roles](./octoacme-roles-and-personas.md) — Define typical roles and responsibilities

## Getting Started

- **New to OctoAcme?** Start with [Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Currently executing?** Reference [Execution & Tracking](./octoacme-execution-and-tracking.md) and [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Preparing to release?** Use the [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- **Wrapping up?** Follow [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)

## Purpose

These documents centralize project management knowledge and support consistent, repeatable project execution across OctoAcme teams. By converting tacit team insights into searchable, versioned artifacts, we enable all team members to:
- Quickly understand OctoAcme's approach
- Access processes when needed
- Reduce onboarding time and single-person dependency risk
- Maintain alignment and psychological safety
- Continuously improve our execution through shared learning
