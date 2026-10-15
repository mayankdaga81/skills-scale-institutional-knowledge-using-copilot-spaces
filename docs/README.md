# OctoAcme Project Management Docs

This directory centralizes OctoAcme's project management process documents and provides a short, practical summary of how projects are started, planned, executed, released, and improved. These docs are intended to make it easy for new teammates and contributors to find the key artifacts, understand roles and responsibilities, and follow the team's cadence and conventions.

Overview

OctoAcme follows a lightweight, outcome-oriented project management process that emphasizes clear initiation, iterative planning, disciplined execution, and continuous improvement. Work starts with a Project One‑pager that captures the problem statement, measurable success metrics, stakeholders, and a high‑level timeline. Teams only move into formal planning once success criteria and stakeholder alignment are confirmed at the decision gate.

During planning, teams break approved initiatives into a prioritized backlog with acceptance criteria, estimates, a Definition of Done (DoD), and a release/milestone plan. Dependencies and risks are identified and recorded in a simple Risk Register so they can be monitored and mitigated during execution.

Execution relies on a predictable cadence and workflow: daily standups to surface progress and blockers, weekly delivery syncs for progress and risk discussion, and demos or reviews at the end of sprints or milestones. The project board follows the flow Backlog → Ready → In Progress → In Review → QA → Done, and Pull Requests are kept small, include acceptance criteria, and require CI/lint checks and approvals before merging.

Quality & Testing

Quality assurance is built into the lifecycle: unit tests for new logic, integration tests as needed, end‑to‑end smoke tests for critical flows, CI‑based security scans, and manual QA for acceptance when appropriate. Releases are classified as patch, minor, or major and require pre‑release checks, release notes, rollback plans, and post‑deploy verifications.

Continuous Improvement

Retrospectives capture what went well, what could be improved, and 2–3 prioritized action items with owners and due dates. Action items are added to the backlog as issues and reviewed in weekly PM syncs to ensure measurable improvements over time.

## Docs (in this folder)
- octoacme-project-management-overview.md — Overview, roles, and key artifacts
- octoacme-project-initiation.md — Project initiation guide and one‑pager template
- octoacme-project-planning.md — Planning activities, backlog template, and checklists
- octoacme-execution-and-tracking.md — Team rhythm, workflows, and execution checklist
- octoacme-release-and-deployment.md — Release types, deployment checklist, and playbook
- octoacme-retrospective-and-continuous-improvement.md — Retrospective format and tracking improvements
- octoacme-risks-and-communication.md — Risk register, communication templates, and escalation
- octoacme-roles-and-personas.md — Roles, responsibilities, and persona use
