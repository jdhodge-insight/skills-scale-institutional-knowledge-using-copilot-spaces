# OctoAcme Project Management Docs

This README centralizes OctoAcme's project management process documentation, providing a quick overview and links to all primary process guides in this folder.

## Overview

OctoAcme runs projects through a clear, staged lifecycle that moves work from a lightweight initiation through planning, execution, release, and retrospective. New initiatives begin with a Project One-pager to capture the problem, success metrics, stakeholders, and a rough timeline. Approved work is broken into a prioritized backlog during planning, with acceptance criteria, estimates, and a documented Definition of Done. Day-to-day execution is managed on a project board (Backlog → Ready → In Progress → In Review → QA → Done) and follows a small-PR, CI-first workflow to ensure incremental, reviewable changes.

Roles and ownership are explicit: Product Managers define outcomes and prioritize the backlog; Project Managers coordinate delivery, schedules, risks, and communications; Developers implement features and tests; QA/testing validates acceptance criteria and quality. Each project names a PM and Product Lead to maintain clear accountability, and artifacts such as the Project Charter, roadmap, risk register, and retrospective notes serve as the canonical project record.

Communication is cadence-driven and structured to surface progress and risks early: daily standups for immediate blockers, a weekly delivery sync to surface progress and flagged risks, sprint/milestone demos, and monthly stakeholder updates. The team uses single-source status artifacts (project README or release doc) along with communication templates (weekly status, incident brief) and defined escalation paths (team → PM → Product Lead → Sponsor). Cross-team dependencies and risk items are tracked in the Risk Register and elevated during regular syncs.

Quality assurance is integrated into every stage. The team requires unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows. CI must run automated tests and security scans before reviews; PRs should be small (target ≤ 400 lines), include issue links and acceptance criteria, and require at least one approval before merging. Releases follow a checklist—pre-release checks, staging smoke tests, automated pipelines where possible, and post-deploy verifications—with rollback plans and incident playbooks documented. Continuous improvement is supported by timeboxed retrospectives that convert findings into tracked action items.

## Process Documentation

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## How to Use These Docs

These documents are intended to be used as reference material for OctoAcme project teams and contributors. When working with **GitHub Copilot Spaces**, add process-specific docs from this folder into `.copilot/` in the relevant project repository so Copilot can draw on them as grounding context. Keep the project-level `README.md` in each project repo updated with current status and links to active process docs. For new or evolving processes, open a PR against this folder to propose changes and ensure team alignment.

## Acceptance Criteria

- [x] Content aligns with existing process docs
- [x] README improves discoverability of docs in `docs/`
- [x] Proposed content added to `docs/README.md` and ready for review
