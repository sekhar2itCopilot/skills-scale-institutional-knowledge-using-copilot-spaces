# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

The following additional personas are proposed to clarify responsibilities and improve handoffs across project activities. Each entry includes a short Role Summary, Responsibilities, and Interaction points with existing roles.

### Delivery Lead
Role Summary: Coordinates day-to-day delivery across multiple squads; focuses on milestones, cross-team dependencies, and schedule trade-offs.

Responsibilities:
- Track milestone progress and adjust plans with PM and PdM
- Coordinate cross-team handoffs and integration points
- Run weekly delivery syncs and maintain risk register
- Monitor capacity and highlight scheduling conflicts

Interaction with existing roles:
- Works closely with Project Managers on scheduling and risk mitigation
- Partners with Product Managers on priority trade-offs and scope decisions
- Coordinates with Developers and QA to resolve blockers and ensure readiness for release

---

### Release Manager
Role Summary: Owns release coordination, cutover, and rollback plans.

Responsibilities:
- Prepare release notes and deployment checklist
- Coordinate staging and production rollouts with DevOps/Infra
- Ensure pre-release smoke tests and post-deploy verifications
- Maintain rollback and mitigation plans

Interaction with existing roles:
- Collaborates with Developers and QA to verify release readiness
- Works with Project Managers to schedule release windows and communications
- Coordinates with Support Lead for post-release monitoring and response

---

### UX Designer
Role Summary: Owns user experience, research inputs, and acceptance criteria related to usability.

Responsibilities:
- Provide designs, prototypes, and UX acceptance criteria
- Conduct or coordinate lightweight usability testing
- Review PRs for UX regressions and ensure design consistency
- Collaborate on accessibility and usability improvements

Interaction with existing roles:
- Works with Product Managers to define user outcomes and acceptance criteria
- Partners with Developers to ensure designs are implemented correctly
- Supports QA with UX-focused test cases and validation

---

### Product Analyst (or Data Analyst)
Role Summary: Defines success metrics, sets up dashboards, and validates product impact.

Responsibilities:
- Propose measurable success metrics and instrumentation
- Build dashboards and run analysis for experiments and releases
- Validate that releases meet success criteria and report findings
- Support A/B testing and experimentation design

Interaction with existing roles:
- Works with Product Managers to define and measure success metrics
- Collaborates with Developers and DevOps on instrumentation and data pipelines
- Reports results to stakeholders and informs prioritization decisions

---

### Security Liaison
Role Summary: Point-of-contact for security reviews and vulnerability triage.

Responsibilities:
- Coordinate security scans and follow-up remediation
- Triage security findings and escalate as needed
- Ensure a minimal viable security checklist is applied to releases
- Advocate for secure design and threat modelling early in planning

Interaction with existing roles:
- Works with Developers and DevOps to remediate findings and apply secure configurations
- Advises Project Managers on security-related risks and prioritization
- Coordinates with Product Managers when security impacts feature scope or timelines

---

### Support Lead / Customer Operations
Role Summary: Owns customer-facing support coordination and incident follow-ups.

Responsibilities:
- Surface frequent customer issues into the backlog and provide context
- Coordinate post-incident communications and RCA follow-up items
- Maintain escalation paths to engineering, product, and stakeholders
- Track trends in customer tickets and recommend product improvements

Interaction with existing roles:
- Works with Product Managers to prioritize customer-reported issues
- Coordinates with Project Managers and Developers during incidents
- Collaborates with Release Manager on communication plans for users

---

### How to integrate these personas
- Add an "Additional Personas" section to the roles document (this section)
- For each persona, include: Role Summary, Responsibilities, Interaction points, and (optionally) suggested owners or titles
- Reference these personas in relevant process docs (planning, release, incident response) and templates to make handoffs explicit

---

