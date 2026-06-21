# OctoAcme Project Management Docs

This README is the central entrypoint for OctoAcme's project management process documentation. Use it to discover, navigate, and understand the key artifacts that guide how OctoAcme plans, executes, and ships work.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

## Overview

OctoAcme uses a lightweight but structured project lifecycle that runs from **initiation → planning → execution → release → retrospective**. Work starts with a one-pager to define the problem, SMART goal, success metrics, stakeholders, timeline, risks, and team roles, followed by a clear go/no-go decision gate before planning proceeds. During planning, teams break work into shippable increments, prioritize and estimate backlog items, define acceptance criteria and Definition of Done, map dependencies, and align milestone and release plans. This creates a consistent path from idea validation to delivery readiness.

Execution is managed through a steady team rhythm and explicit workflow controls. Teams use project boards (Backlog, Ready, In Progress, In Review, QA, Done), daily standups to surface blockers and dependencies, weekly delivery syncs, and sprint-end demos. PR practices emphasize small changes, issue linkage, acceptance criteria in descriptions, CI checks (tests and lint), and required approvals before merge. Progress is tracked via velocity, burndown, and dashboards for operational signals such as errors, latency, and usage, with risk escalation moving from team triage up to PM, Product Lead, and sponsor as impact increases.

Role clarity is central to the model. **Project Managers** coordinate delivery, timelines, risks, and communication. **Product Managers** define outcomes, prioritize the roadmap and backlog, and validate value through metrics. **Developers** implement, test, document, and surface technical risks. **QA/Testing** validates acceptance criteria and release readiness, while **Stakeholders** provide inputs and approvals. The model emphasizes clear ownership, iterative delivery, and data-informed decisions supported by psychologically safe collaboration.

Communication and quality are integrated throughout rather than treated as end-stage activities. OctoAcme maintains a risk register (impact, likelihood, owner, mitigation, status), uses weekly or milestone-based status updates, and keeps a single source of truth for project status. Quality expectations include unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, CI security scanning, and manual QA for feature acceptance when needed. Releases require passing checks, release notes, rollback planning, and post-deploy verification. Retrospectives capture what worked, what didn't, and 2–3 prioritized improvement actions with owners and due dates.
