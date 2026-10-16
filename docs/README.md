# OctoAcme Project Management Docs

This folder contains OctoAcme's core process documents for initiating, planning, executing, releasing, and continuously improving projects. Use this README as the single entry point to find process guidance, templates, and checklists that help teams move from idea to production safely and predictably.

OctoAcme follows an iterative lifecycle with clear decision gates and lightweight artifacts: Initiation (validate ideas with a Project One-pager and confirm stakeholders), Planning (prioritize and size backlog items, define acceptance criteria and a release plan), Execution & Tracking (work tracked on a project board and progressed through small, CI-gated PRs), Release & Deployment (pre-release checks, staging smoke tests, and rollback playbooks), and Retrospective & Continuous Improvement (timeboxed reviews that produce tracked action items).

Key workflows emphasize small, testable increments and guarded handoffs. Backlog items follow a standard template (title, description, acceptance criteria, estimate, owner) and are timeboxed into iterations. Pull requests should be small where possible, include issue links and acceptance criteria, and run automated tests and security scans in CI prior to review. Releases use a checklist-driven process that includes smoke tests, release notes, and rollback plans so production risk is minimized.

Roles and communication are explicit to ensure accountability and alignment. Product Managers set outcomes and success metrics; Project Managers coordinate delivery, risks, and stakeholder communications; Developers implement and test features; QA validates acceptance criteria; and stakeholders provide inputs and approvals. Teams follow a regular cadence (daily standups for blockers, weekly delivery syncs for progress and risks, demos at the end of sprints/milestones, and monthly stakeholder updates). Risk and incident communication use standard templates and a clear escalation path (team → PM → Product Lead → Sponsor), with security incidents routed to the security runbook.

Quality assurance is layered: unit and integration tests for correctness, end-to-end smoke tests for critical flows, security scanning in CI, and manual QA for acceptance when needed. Continuous improvement is enforced through retrospectives that produce a small number of prioritized action items which are added back into the backlog and tracked to completion.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## How to use

- Link this README from the repository README or docs index to make process guidance discoverable.
- When new process documents are added to this folder, update this README to include them.
- Use the included templates and checklists as the canonical starting point for project artifacts and release preparations.

---

*Created from Issue #2: "[Process Doc Update]: README, project management processes summary, and links to docs"*
