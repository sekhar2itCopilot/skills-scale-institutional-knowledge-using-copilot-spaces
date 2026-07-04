# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management knowledge base. These docs capture the processes, roles, and practices used across all OctoAcme cross-functional projects.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, customer-first project management approach designed to ensure iterative delivery, clear ownership, and data-informed decision-making. The framework applies to all cross-functional projects delivering product features, services, or integrations. Key roles include Project Managers (who coordinate delivery and timelines), Product Managers (who define outcomes and prioritize work), Developers (who implement features and collaborate on design), and QA/Testing teams (who validate quality). This clear role definition ensures accountability and smooth execution across projects, with established communication cadences including weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates.

OctoAcme projects follow a five-phase lifecycle: **Initiation** (problem validation and stakeholder alignment), **Planning** (backlog prioritization and scope definition), **Execution** (build, test, review, iterate), **Release** (deploy and verify), and **Close & Retrospective** (capture learnings). The execution phase leverages GitHub Projects with kanban-style columns (Backlog, Ready, In Progress, In Review, QA, Done) and follows disciplined Pull Request practices—including small PRs (≤400 lines), mandatory acceptance criteria documentation, automated CI testing, and at least one required approval before merging. Daily standups focus on progress, blockers, and dependencies, while weekly delivery syncs track progress against milestones and flag emerging risks.

Quality is built into every phase through comprehensive testing practices: unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. Security scanning is integrated into CI pipelines, and manual QA validates feature acceptance when needed. Risk management is central to OctoAcme's approach—teams maintain a Risk Register throughout the project lifecycle, identifying issues by ID, impact (High/Med/Low), likelihood, and mitigation plans. A formal escalation path exists (team-level → PM → Product Lead → Sponsor) to address blockers and business-impacting issues, ensuring risks are surfaced and resolved transparently.

## Quick Start

New to OctoAcme? Start here:
- [Project Management Overview](./octoacme-project-management-overview.md) — understand our principles, roles, and lifecycle
- [Roles & Personas](./octoacme-roles-and-personas.md) — learn who does what

## Process Guides

Use these guides based on where you are in the project lifecycle:

### Phase 1: Initiation
- [Project Initiation Guide](./octoacme-project-initiation.md) — validate ideas, align stakeholders, create a lightweight plan

### Phase 2: Planning
- [Project Planning](./octoacme-project-planning.md) — break work into increments, manage dependencies, create the backlog

### Phase 3: Execution
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — day-to-day delivery, standups, quality standards, metrics

### Phase 4: Release
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — standardize releases, reduce risk, deploy to production

### Phase 5: Close & Learn
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — capture learnings, measure impact, improve processes

## Cross-Cutting Concerns

These guides apply throughout the project:
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — identify risks, escalate blockers, communicate with stakeholders

## Key Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named PM and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Need Help?

If you have questions about these processes, reach out to your Project Manager or check the specific guide for your current phase.
