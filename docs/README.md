# OctoAcme Project Management Docs

OctoAcme runs projects through a lightweight, evidence-driven lifecycle: initiation (one‑pager to validate need and align stakeholders), planning (backlog, acceptance criteria, and release milestones), iterative execution (small shippable increments with CI + PR controls), and release + retrospective activities to capture learnings. Core artifacts — Project One‑pager, prioritized backlog, Definition of Done, risk register, release notes, and retrospective action items — live in the repo to serve as the single source of truth.

Workflows emphasize small, testable delivery and clear handoffs. Planning uses kickoff meetings, lightweight estimation (T‑shirt sizing or story points), and backlog grooming. Teams operate a project board with columns such as Backlog → Ready → In Progress → In Review → QA → Done. The pull request workflow encourages small PRs, an explicit acceptance-criteria link to the issue, CI checks (tests, linters, security), and at least one reviewer approval before merge. Releases follow a documented checklist (staging smoke tests, rollback plan, post‑deploy verifications) and are classified (patch/minor/major) to apply the appropriate guardrails.

Roles and responsibilities are explicit: Product Managers (PdMs) set outcomes and prioritize, Project Managers (PMs) coordinate schedules/risks/communication, Developers implement and maintain tests and docs, QA validates acceptance criteria with automated/manual testing, and stakeholders provide decisions and approvals. Persona templates and role definitions are provided to make ownership and communication responsibilities repeatable across projects.

Communication and quality assurance are tightly coupled to cadence. Regular touchpoints include daily standups for immediate blockers and progress, weekly delivery syncs and PM–PdM alignment meetings, sprint demos/reviews, and monthly stakeholder updates. Risk and incident communication use templates and follow an escalation path (team → PM → Product Lead → Sponsor). QA combines unit, integration, and end‑to‑end smoke tests enforced by CI with manual acceptance testing and retrospectives that feed prioritized improvements back into the backlog.

## Docs Index
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md