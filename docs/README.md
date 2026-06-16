# OctoAcme Project Management Docs

This README centralizes the OctoAcme project management process documents and provides a summary of our overall project management approach.

## Project Management Processes Summary

OctoAcme follows a structured lifecycle approach to project management that emphasizes customer value, iterative delivery, and clear ownership. The organization operates five core phases:

- **Initiation**: Validate business need and stakeholder alignment through a lightweight one-pager, confirm measurable outcomes, and decide go/no-go for planning.
- **Planning**: Break work into shippable increments with acceptance criteria, identify dependencies and risks, align timelines, and create a release/milestone plan.
- **Execution & Tracking**: Use project boards, PR conventions, CI/CD rigor, daily standups, and weekly delivery syncs to manage day-to-day progress toward milestones.
- **Release & Deployment**: Follow pre-release checklists, automated pipelines, smoke tests, and documented rollback plans to minimize production risk.
- **Retrospectives & Continuous Improvement**: Capture learnings after each sprint or milestone, convert them into prioritized action items, and track improvements.

### Key Characteristics

OctoAcme emphasizes:
- **Clear Roles & Ownership**: Project Managers coordinate delivery and manage risks; Product Managers define outcomes and measure success; Developers implement features; QA validates quality.
- **Communication Cadence**: Daily standups, weekly PM-PdM syncs, twice-weekly delivery team meetings, monthly stakeholder updates, and ad-hoc escalation paths for blockers.
- **Quality & Rigor**: GitHub Projects workflow management, small PRs (≤400 lines), CI/CD enforcement of tests/linting/security scans, Definition of Done, and manual QA validation.
- **Risk Management**: Maintain risk registers reviewed weekly, identify dependencies during planning, and escalate via team → PM → Product Lead → Sponsor.
- **Continuous Improvement Culture**: Retrospectives (45–75 minutes per sprint), anonymous idea boards for candor, and measurable impact tracking of action items.

## Process Documents

Each document below covers a specific phase or aspect of OctoAcme's project management approach:

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise intro to OctoAcme's principles, core roles, key artifacts, lifecycle, and communication cadence.
- **[Project Initiation Guide](octoacme-project-initiation.md)** — How to validate and authorize new work; includes one-pager template and decision gate.
- **[Project Planning](octoacme-project-planning.md)** — Backlog creation, estimation, Definition of Done, dependency management, and planning checklist.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day workflows, team rhythm, PR conventions, CI/CD practices, blocker escalation, and execution checklist.
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk register structure, risk lifecycle, stakeholder communication templates, and escalation paths.
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Release types, pre-release requirements, deployment checklist, rollback playbook, and release notes template.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — How to run retrospectives, track action items, and measure improvement impact.
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed role summaries, responsibilities, goals, and typical communication patterns for Project Managers, Product Managers, and Developers.

## How to Use These Docs

- **Onboarding**: New team members should start with the [Project Management Overview](octoacme-project-management-overview.md) for a high-level understanding, then dive into phase-specific docs as needed.
- **Project Setup**: When initiating a new project, reference the [Project Initiation Guide](octoacme-project-initiation.md); move through planning, execution, and release docs as you progress through the lifecycle.
- **Single Source of Truth**: Keep this README and all process docs updated as OctoAcme's practices evolve. Reference this README in PRs that modify process docs.
- **Copilot Spaces**: These docs can be added to a Copilot Space to provide context-aware guidance during project execution.
