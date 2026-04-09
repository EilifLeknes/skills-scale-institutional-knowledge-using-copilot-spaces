# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This folder contains detailed guidance on how OctoAcme runs projects, manages risks, communicates with stakeholders, and continuously improves.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured five-phase project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The Initiation phase focuses on validating business need and creating a lightweight Project One-pager that defines the problem, goals, success metrics, and stakeholders. Once approved, Planning breaks the work into shippable increments with clear acceptance criteria, estimates, and a prioritized backlog. During Execution, teams follow a daily standup cadence (15 minutes), weekly delivery syncs, and use GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Pull requests are kept small (≤400 lines), require automated CI checks, linting, and at least one approval before merging. This structured approach ensures predictable delivery while maintaining flexibility through iterative refinement.

OctoAcme operates with clearly defined roles: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize work, and measure success; **Developers** implement features and collaborate on design and testing; and **QA/Testing** validates quality and acceptance criteria. Communication is highly structured with a weekly sync between PM and Product Manager, twice-weekly standups for the delivery team, monthly stakeholder updates, and ad-hoc escalations as needed. Risk escalation follows a tiered approach: Level 1 is team-level triage in daily standup, Level 2 involves PM escalation to Product Lead and dependent teams, and Level 3 is sponsor-level escalation for business-impacting issues. This multi-tiered communication ensures blockers are surfaced quickly while maintaining appropriate visibility at each organizational level.

OctoAcme emphasizes quality through layered testing practices: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows before release, and security scanning in CI. A Definition of Done is documented for each project to ensure consistency, and manual QA is conducted for feature acceptance when needed. Risk management is integrated throughout the project lifecycle via a maintained Risk Register that tracks ID, description, impact, likelihood, owner, mitigation plan, and status. Teams identify risks during planning and continuously monitor them at weekly syncs. Before release, all acceptance criteria must be met, CI and security scans must pass, release notes must be drafted, and rollback/mitigation plans documented. This comprehensive approach to quality and risk reduces production incidents and enables confident, rapid deployment.

OctoAcme closes the feedback loop through structured retrospectives held after each sprint, release, or important milestone. Retrospectives timebox 45–75 minutes, capture what went well and what could improve, and generate 2–3 prioritized action items with clear owners and due dates. Outstanding action items are reviewed in the weekly PM sync and tracked as project backlog issues. This commitment to continuous improvement, combined with measurement of action item impact, creates a learning culture where teams iteratively refine processes and practices. By capturing learnings in versioned documentation (stored in this folder and referenced via Copilot Spaces), OctoAcme builds scalable institutional knowledge that accelerates onboarding and reduces single-person dependency risks across the organization.

---

## Process Documents

### Getting Started
- **[OctoAcme Project Management Overview](./octoacme-project-management-overview.md)** — High-level introduction to roles, principles, key artifacts, and the five-phase lifecycle.
- **[OctoAcme Personas](./octoacme-roles-and-personas.md)** — Detailed descriptions of Developers, Product Managers, and Project Managers.

### Project Phases
- **[Project Initiation Guide](./octoacme-project-initiation.md)** — Validate business need, align stakeholders, and create a Project One-pager.
- **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments with acceptance criteria and risk management.
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Daily standups, PR workflow, testing, blocker escalation, and metrics.
- **[Release & Deployment Guide](./octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklist, and rollback procedures.

### Cross-Cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk Register maintenance, stakeholder communication, and escalation paths.
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and converting them into actionable improvements.

---

## How to Use These Docs

1. **New Project Lead?** Start with the [OctoAcme Project Management Overview](./octoacme-project-management-overview.md), then review the process documents for each phase as you move through your project.

2. **Role-Specific Guidance?** Check [OctoAcme Personas](./octoacme-roles-and-personas.md) to understand your responsibilities and communication patterns.

3. **Need a Template?** Each process document includes checklists and templates (e.g., Project One-pager, Risk Register, Release Notes).

4. **Using Copilot Spaces?** These docs are versioned and can be added to Copilot Spaces as context to provide role-specific guidance and process assistance in real time.

---

## Feedback & Improvements

Found a gap in these docs? Have a suggestion for improvement? Please open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template, and we'll review and incorporate your feedback.
