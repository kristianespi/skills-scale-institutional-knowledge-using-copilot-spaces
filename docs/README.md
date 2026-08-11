# OctoAcme Project Management Documentation

## Overview
OctoAcme follows a clear, iterative project management lifecycle that begins with a lightweight initiation and moves through planning, execution, release, and retrospective stages. Work is grounded in measurable outcomes (Project One‑pagers), explicit ownership, and data‑informed decisions. Processes are designed to be lightweight, scalable, and to promote psychological safety and continuous improvement.

## Key workflows
Key workflows emphasize small, reviewable changes and predictable delivery. Teams use a project board with columns: Backlog → Ready → In Progress → In Review → QA → Done. The Pull Request workflow favors small PRs with CI checks and required approvals before merging. Releases follow a checklist that includes staging verification, smoke tests, and rollback plans.

Planning practices require backlog items to include clear acceptance criteria, estimates, and owners so sprints produce shippable increments. Risk and dependency management is tracked in a Risk Register and raised in weekly syncs when needed.

## Roles & communication
Roles are explicit: Project Managers coordinate delivery, schedules, risk, and stakeholder communications; Product Managers define outcomes, prioritize the backlog, and measure success; Developers implement features and maintain tests and docs; QA validates acceptance criteria and quality.

Communication cadence includes daily standups (15 minutes), weekly PM+PdM syncs, sprint demos and retrospectives, and monthly stakeholder updates. Escalation paths progress from team-level triage to PM → Product Lead → Sponsor for business-impacting issues.

## Quality & continuous improvement
Quality gates include unit and integration tests, security scanning in CI, and manual QA for feature acceptance when necessary. Releases require passing CI/security checks, release notes, and rollback plans. Retrospectives capture learnings and convert them into tracked action items that feed the backlog for continuous improvement.

## Process documents (start here)
- Project Management Overview — ./octoacme-project-management-overview.md
- Roles & Personas — ./octoacme-roles-and-personas.md
- Project Initiation Guide — ./octoacme-project-initiation.md
- Project Planning — ./octoacme-project-planning.md
- Execution & Tracking — ./octoacme-execution-and-tracking.md
- Release & Deployment Guide — ./octoacme-release-and-deployment.md
- Risk Management & Communication — ./octoacme-risks-and-communication.md
- Retrospective & Continuous Improvement — ./octoacme-retrospective-and-continuous-improvement.md

## How to use these docs
- New to OctoAcme: start with the Project Management Overview and Roles & Personas.
- Starting a project: follow the Initiation and Planning guides.
- In delivery: use Execution & Tracking and the Risk Register.
- Preparing to release: follow the Release & Deployment checklist.
- Want to suggest updates: open an issue using the .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml template.

---

These docs are living artifacts — please propose improvements or additions via the process doc issue template.
