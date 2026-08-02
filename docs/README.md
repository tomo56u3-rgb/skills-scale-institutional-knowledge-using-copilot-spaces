# OctoAcme Project Management — Overview

This repository contains OctoAcme's project management process documents. These docs are intended to centralize our team rhythms, lifecycle steps, roles, artifacts, and checklists so new and existing teammates can find consistent guidance for initiating, planning, executing, and closing work.

Where to find the docs
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

Purpose
- Provide a single, shareable introduction to how OctoAcme runs cross-functional projects.
- Reduce single-person knowledge dependencies and speed onboarding.
- Capture repeatable practices for planning, delivery, risks, and retrospectives.

High-level lifecycle
1. Initiation — Create a Project One-pager, confirm stakeholders and success metrics.
2. Planning — Prioritize backlog, estimate work, define Definition of Done and release milestones.
3. Execution & Tracking — Use the project board, run daily standups, follow PR and CI conventions.
4. Release & Deployment — Follow pre-release checks, smoke tests, and a rollback plan.
5. Retrospective & Improvement — Capture actions, track impact, and feed changes back into docs.

Team rhythm & workflows
- Standups: daily (15 min) for progress and blockers.
- Weekly delivery sync: progress, dependencies, and risks.
- Demos/reviews at end of each sprint or milestone.
- Project board columns: Backlog → Ready → In Progress → In Review → QA → Done
- PR guidance: small PRs where possible, link issues and acceptance criteria, CI and security scans pass, require approvals before merge.

Quality & testing
- Unit and integration tests for new logic.
- E2E smoke tests for critical flows.
- Security scanning in CI and manual QA when needed.

Risk, communication & escalation
- Maintain a Risk Register (ID, impact, likelihood, mitigation, owner, status).
- Weekly risk review; escalate: Team -> PM -> Product Lead -> Sponsor.
- Use weekly status templates for stakeholders and incident runbooks for outages.

Contributing updates to these process docs
- Use the issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
- Propose changes via that template and link PRs back to the issue for review.

How these docs are used by Copilot Spaces
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context for space-specific guidance.
