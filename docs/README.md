# OctoAcme — Project Management Docs

This folder contains OctoAcme's project management process documents and a short summary of how we run projects. These docs provide guidance for initiating work, planning and estimating, executing delivery, releasing to production, and capturing continuous improvement.

## Brief summary of OctoAcme project management processes

OctoAcme follows a lightweight, iterative lifecycle with clear decision gates: Initiation → Planning → Execution → Release → Retrospective. Work begins with a Project One‑pager to confirm the problem, success metrics, stakeholders, and a go/no‑go decision for planning. Planning turns approved initiatives into a prioritized backlog with estimates, a Definition of Done (DoD), and a release/milestone map.

Day‑to‑day delivery uses a visible project board (Backlog → Ready → In Progress → In Review → QA → Done), timeboxed sprint planning, and small pull requests that include acceptance criteria and CI checks. Developers, Product Managers, Project Managers, and QA each have defined responsibilities to ensure clear ownership and predictable delivery. Releases follow checklist-driven staging and production steps, with smoke tests, rollback plans, and release notes to reduce risk.

Retrospectives and continuous improvement are mandatory after sprints, releases, or incidents: capture what went well, what could improve, and 2–3 action items that are tracked back into the backlog. Risks are logged in a simple register with owners and mitigations and are reviewed in weekly syncs; escalation follows an explicit path from team → PM → Product Lead → Sponsor.

## Process documents (in this folder)
- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retro & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## How to use
1. Read the Project Management Overview for context and principles.
2. Use the Initiation Guide when starting a new project.
3. Follow Planning and Execution docs during delivery for backlog, DoD, and PR guidance.
4. Use Release & Deployment for shipping and rollback steps.
5. Add action items from retros into the backlog and track progress in the project board.

## Want to update a doc?
Propose changes using the repository’s process doc issue template: .github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml
