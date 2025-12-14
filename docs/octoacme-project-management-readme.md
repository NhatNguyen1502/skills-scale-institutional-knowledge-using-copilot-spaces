# OctoAcme Project Management Documentation

This file serves as the entry point to the OctoAcme project management process documentation. Whether you are a new team member getting up to speed or an experienced contributor looking for a specific process, this README will guide you to the right resources for understanding how OctoAcme manages projects from initiation through retrospective.

## Summary

OctoAcme runs projects with an iterative, outcome-driven lifecycle that moves work through five clear stages: Initiation, Planning, Execution, Release, and Close &amp; Retrospective. Initiation centers on a lightweight Project One-pager to confirm the problem, success metrics, stakeholders, and a go/no‑go decision. Planning breaks approved initiatives into a prioritized, estimated backlog, defines a Definition of Done, captures dependencies and risks in a Risk Register, and produces a release plan and milestone map. Execution uses timeboxed iterations or deliveries with continuous tracking against milestones and an explicit handoff into Release when acceptance criteria are met.

Workflows are organized around a project board (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request process: small PRs, linked issues and acceptance criteria, automated CI checks (tests, linting, security scans), and required approvals before merging. Execution guidance includes a daily/team rhythm (standups, weekly delivery syncs, demos) and an execution checklist (branch/PR conventions, CI, smoke tests, risk register upkeep). Blocker escalation is tiered (team triage → PM → Product Lead/dependent teams → Sponsor) so issues affecting delivery are escalated promptly.

Roles and responsibilities are explicit: Project Managers coordinate delivery, schedules, risks, and stakeholder communications; Product Managers define outcomes, prioritize work, and measure success; Developers implement features, tests, and reviews; QA/Testing validate quality and acceptance criteria; stakeholders supply input and approvals. These personas are used to assign ownership for artifacts (one‑pager, release notes, risk mitigations) and to structure meetings and decision gates, reducing ambiguity about who acts on what and when.

Quality assurance and communication are woven into every stage. QA practices include unit, integration, and end-to-end smoke tests, manual QA as needed, CI security scanning, and post‑deploy verifications. Communication cadence combines daily standups, weekly PM+PdM syncs, twice‑weekly or team‑agreed standups, and monthly stakeholder updates, with templates for weekly status and incident communications. Retrospectives after sprints, releases, or incidents capture actionable improvements and track action items back into the backlog to drive continuous improvement.

## Key Documents

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning Guide](octoacme-project-planning.md)
- [Execution and Tracking Guide](octoacme-execution-and-tracking.md)
- [Risks and Communication Guide](octoacme-risks-and-communication.md)
- [Release and Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement Guide](octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas Guide](octoacme-roles-and-personas.md)

## How to use these docs

- Keep the Project One-pager updated in the project repo
- Add process-specific docs into .copilot/ if you want Copilot Spaces to use them as context
