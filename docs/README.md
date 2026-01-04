# OctoAcme Project Management Docs

## Overview

The OctoAcme Project Management Docs provide a centralized, living knowledge base for initiating, planning, executing, releasing, and improving projects at OctoAcme. These resources make team processes, decisions, rationale, and templates discoverable so teams can work consistently and onboard faster.

### Brief overview of project management processes

OctoAcme runs projects with a lightweight, repeatable lifecycle that moves work from initiation through planning, execution, release, and continuous improvement. Initiation captures the problem, goals, success metrics, stakeholders, and a high-level timeline (Project One-pager) and includes a decision gate before planning. Planning breaks approved initiatives into a prioritized, estimated backlog with defined acceptance criteria and a Definition of Done; teams use a project board (Backlog → Ready → In Progress → In Review → QA → Done) to manage flow. Execution emphasizes small, reviewable pull requests, automated CI and security checks, frequent demos, and a pre-release checklist (staging verification, smoke tests, rollback plan). Retrospectives and tracked action items close the improvement loop.

Key roles are explicitly defined so responsibilities and handoffs are clear: Product Manager (PdM) owns the problem, outcomes, and prioritization; Project Manager (PM) coordinates delivery, schedules, risks, and communications; Developers implement features, write tests, and perform reviews; QA validates acceptance criteria; Stakeholders provide input and approvals. Communication follows a predictable cadence (daily standups, weekly delivery syncs, PM+PdM weekly alignment, monthly stakeholder updates) with templates for weekly status and escalation paths for blockers and incidents.

Quality assurance and risk management are embedded throughout: unit/integration tests and security scans run in CI; manual QA and end-to-end smoke tests are used for acceptance; pre-release checks (passing CI, security scans, acceptance criteria met, rollout/rollback plans) are required before production deployments. Risks are tracked in a Risk Register (ID, impact, likelihood, owner, mitigation) and reviewed in regular syncs.

## Process Docs Index

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](octoacme-roles-and-personas.md)

Refer to each linked document for templates, checklists, and examples. To propose changes, use the issue templates under .github/ISSUE_TEMPLATE/ (for example: "Add Content to Project Management Process Docs").
