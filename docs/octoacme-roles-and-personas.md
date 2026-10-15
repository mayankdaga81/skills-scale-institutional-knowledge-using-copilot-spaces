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

## Additional Personas (proposed additions)

These personas are proposed to reduce ambiguity, improve ownership, and clarify handoffs across planning, execution, release, and measurement.

### Delivery Lead (Operational PM)
- Responsibilities: Coordinates day-to-day delivery (sprint-level planning), runs standups, tracks sprint progress, owns sprint-level risk items and blockers, coordinates cross-functional work to unblock delivery.
- Interacts with: Developers (daily syncs, removes blockers), Project Manager (escalates cross-sprint risks and progress), QA (ensures sprint-quality gate), Product Manager (aligns on sprint scope).
- Example deliverables: Sprint commitment board, daily standup notes, sprint risk log.

### Engineering Manager (Team Lead)
- Responsibilities: Owns engineering capacity planning, developer mentoring, technical quality and architecture decisions, and technical debt prioritization.
- Interacts with: Developers (coaching, code review guidance), Product Manager (capacity and trade-off discussions), Project Manager (resource planning), UX/Design (technical feasibility).
- Example deliverables: Capacity forecasts, technical design reviews, staffing/mentorship plans.

### UX / Design Lead
- Responsibilities: Owns user research synthesis, interaction design, accessibility oversight, and ensures designs meet acceptance criteria prior to implementation.
- Interacts with: Product Manager (requirements and acceptance criteria), Developers (handoff and implementation questions), QA (usability testing).
- Example deliverables: Design specs, accessibility checklist, user research summaries.

### Release Manager / On-call Coordinator
- Responsibilities: Coordinates release scheduling and readiness checks, ensures deployment runbooks and rollback plans are in place, coordinates post-release verification and incident routing.
- Interacts with: QA (release gates and smoke tests), SRE/DevOps (deployment pipelines), Product/PM (release windows and stakeholder notifications), Support (on-call handoff).
- Example deliverables: Release checklist, deployment runbook, post-release verification report.

### Stakeholder Representative (e.g., Sales / Support Lead)
- Responsibilities: Serves as the voice of operational stakeholders (sales, support, customer success), provides business context and priority signals, participates in milestone reviews and acceptance decisions for cross-functional impacts.
- Interacts with: Product Manager (priority and acceptance), Project Manager (communication and timelines), Developers and QA when clarifying customer scenarios.
- Example deliverables: Stakeholder acceptance notes, customer impact assessments.

### Data Analyst / Metrics Owner
- Responsibilities: Defines success metrics, builds dashboards and reports, validates outcomes post-release, and ensures instrumentation is in place for experiments and releases.
- Interacts with: Product Manager (success criteria), Developers (instrumentation needs), Project Manager (reporting cadence).
- Example deliverables: Dashboards, metric definitions, A/B analysis summaries.

---

## How these personas interact (summary)
- Delivery Lead syncs daily with Developers and reports sprint progress and blockers to the Project Manager.
- Engineering Manager aligns with Developers on estimates and capacity, and advises Product on technical trade-offs.
- UX Lead finalizes acceptance criteria and collaborates on QA scenarios to ensure design and accessibility goals are met.
- Release Manager drives pre-release readiness checks with QA and SRE/DevOps and coordinates stakeholder notifications.
- Stakeholder Representative attends milestone reviews and signs off on cross-functional impacts.
- Data Analyst provides measurement frameworks and post-release analyses to validate success metrics.

---

## Suggested format for insertion in docs/octoacme-roles-and-personas.md
- Add a short table or section per persona with:
  - Persona name
  - Responsibilities (short bullets)
  - Typical interactions (who they work with)
  - Example deliverables

This keeps the document scannable and makes it easier to assign clear owners for actions and risks.
