# OctoAcme Project Management Docs

## About
This README indexes and introduces OctoAcme's project management process documents stored in `docs/`. Use it as the central hub for onboarding, reference, and as the single source of truth for project status and process artifacts.

## Linked Documents

### Core Process Documents
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution and Tracking](octoacme-execution-and-tracking.md)
- [Risks and Communication](octoacme-risks-and-communication.md)
- [Release and Deployment](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

### Templates and Checklists
Use these templates to standardize documentation and ensure consistency across roles and processes:
- [Role Description Template](templates/role-description-template.md) – Standardized format for documenting roles and personas
- [Stakeholder Review Checklist](templates/stakeholder-review-checklist.md) – Checklist for updating process docs or introducing new roles
- [Change Management Checklist](templates/change-management-checklist.md) – Guide for assessing impact, communications, training, and rollback plans

## OctoAcme Project Management Summary
OctoAcme runs projects with an iterative, customer-first framework that emphasizes clear ownership, measurable outcomes, and small, testable deliveries. Projects follow a defined lifecycle—initiation, planning, execution, release, and retrospective—backed by core artifacts like a Project One-pager/charter, roadmap and release plan, prioritized backlog, acceptance criteria / Definition of Done, a Risk Register, and retrospective action items. Decision gates ensure initiatives only move from initiation to planning when success metrics, stakeholder alignment, and team availability are confirmed.

Responsibilities are explicitly assigned across core personas: the Project Manager (PM) coordinates delivery, risk, schedule, and communications; the Product Manager (PdM) defines outcomes and prioritizes the backlog; developers implement features and design for testability; QA/testing validates quality and acceptance criteria; and stakeholders provide inputs and approvals. Role clarity is reinforced by requiring a named PM and Product Lead for each project and by documenting owners on backlog items and risks.

Operational workflows are concrete: planning includes kickoff meetings, backlog prioritization and estimation, and a release/milestone map; execution uses a project board workflow (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined PR process (small PRs, include issue link and acceptance criteria, CI runs automated tests and linters, require approvals before merge). Teams track velocity and burndown, schedule demos/reviews at the end of sprints or milestones, and maintain CI-driven quality checks including unit, integration, and end-to-end smoke tests plus security scanning.

Communication and quality assurance are integrated into cadence and escalation paths. Regular rhythms include daily standups, weekly delivery syncs, weekly PM+PdM syncs, and monthly stakeholder updates; status lives in a single source of truth and follows templates for weekly updates and incident summaries. Risks are tracked in a Risk Register with owners and mitigation plans and are reviewed at weekly syncs; escalation paths run from team → PM → Product Lead → Sponsor, with a separate security incident runbook. QA combines automated testing in CI with manual acceptance testing as needed, and the team uses blameless retrospectives to capture improvements.

## How to use this README
- Update this README when documents are added or reorganized.
- Link to the project README from project boards and release notes.
- Use the linked docs for templates, checklists, and process enforcement.
