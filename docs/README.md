# OctoAcme Project Management Docs

This README provides a concise overview of OctoAcme's project management processes and links to the detailed process documents in this folder.

OctoAcme runs projects through a clear, staged lifecycle from lightweight initiation through planning, execution, release, and retrospective. New initiatives begin with a Project One‑pager to capture the problem, success metrics, stakeholders, and a rough timeline. Approved work is broken into a prioritized backlog during planning, with acceptance criteria, estimates, and a documented Definition of Done. Day‑to‑day execution is managed on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and follows a small‑PR, CI‑first workflow to ensure incremental, reviewable changes.

Roles and ownership are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, schedules, risks, and communications; Developers implement features and tests; QA validates acceptance criteria and quality. Each project names a PM and Product Lead to maintain clear accountability, and artifacts such as the Project One‑pager, risk register, roadmap, and retrospective notes serve as the canonical project record.

Communication is cadence-driven and structured to surface progress and risks early: daily standups for immediate blockers, a weekly delivery sync to surface progress and flagged risks, sprint/milestone demos, and monthly stakeholder updates. Quality assurance is integrated into every stage — unit and integration tests, smoke tests for critical flows, CI-based security scans, small PRs with required reviews, and a release checklist that includes staging verification and rollback plans. Retrospectives convert learnings into tracked action items to drive continuous improvement.

## Process documentation

- ./octoacme-project-management-overview.md
- ./octoacme-project-initiation.md
- ./octoacme-project-planning.md
- ./octoacme-execution-and-tracking.md
- ./octoacme-risks-and-communication.md
- ./octoacme-release-and-deployment.md
- ./octoacme-retrospective-and-continuous-improvement.md
- ./octoacme-roles-and-personas.md

## How to use these docs

Keep project-specific artifacts (Project One‑pager, roadmap, risk register, release notes) updated in the project repo README or docs/ so this folder remains a reliable single source of truth. To make these process docs available to Copilot Spaces and other tooling, add project-specific process documents into `.copilot/` when appropriate. Use the templates and checklists in this folder to onboard contributors and maintain consistent delivery practices.

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] README improves discoverability of docs in docs/
- [x] Proposed content added to docs/README.md and ready for review
