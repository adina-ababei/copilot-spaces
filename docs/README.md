# OctoAcme Project Management Docs

## Overview

OctoAcme uses a structured, iterative approach to project management grounded in customer-first delivery, clear ownership, and data-driven decisions. These docs capture our processes, roles, and best practices to ensure consistent, repeatable execution across all projects.

Our process is built on five core phases—**Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**—each with clear deliverables, governance gates, and communication touchpoints. This lifecycle ensures that only well-aligned initiatives are planned, that teams have unambiguous acceptance criteria and definitions of done, and that learnings are captured and fed back into continuous improvement.

### Key Process Highlights

**Lightweight but Rigorous**: Each phase includes a checklist to ensure completeness without bureaucratic overhead. During initiation, a one-pager validates business need and stakeholder alignment. During planning, we break work into shippable increments with clear acceptance criteria. During execution, daily standups and a consistent PR workflow keep teams synchronized. Pre-release checklists ensure quality gates are met before production deployment.

**Embedded Quality & Testing**: Unit tests, integration tests, end-to-end smoke tests, and security scanning are built into the development workflow. Manual QA validates feature acceptance when needed. Post-release verifications and rollback playbooks minimize incident impact.

**Clear Roles & Communication**: Project Managers coordinate delivery and manage risks; Product Managers define outcomes and prioritize the backlog; Developers implement and collaborate; QA validates quality. Weekly PM/PdM syncs, twice-weekly team standups, and monthly stakeholder updates keep everyone aligned. A three-level escalation path (team → PM → Product Lead → Sponsor) surfaces blockers quickly.

**Risk & Continuous Improvement**: Risk registers are maintained and reviewed weekly. Retrospectives run after each sprint or release to capture learnings and surface 2–3 actionable improvements. This closed-loop approach enables the team to deliver reliably while continuously refining processes based on evidence and feedback.

## Core Principles
- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Process Lifecycle
1. **Initiation** → Define the problem, goals, and stakeholders
2. **Planning** → Break work into shippable increments with acceptance criteria
3. **Execution** → Build, test, review, and iterate with daily standups
4. **Release** → Deploy to production with verification and announcement
5. **Close & Retrospective** → Capture learnings and next steps

## Core Roles
- **Project Manager (PM)**: Coordinates delivery, schedules, risks, communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features and collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

## Documentation Index

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction, principles, roles, and lifecycle
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed responsibilities and communication for each role

### Phase-Specific Guides
- **[Project Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, and get go/no-go to plan
- **[Project Planning](octoacme-project-planning.md)** — Break work into backlog, estimate scope, define DoD, identify dependencies
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Daily standups, PR workflow, quality standards, and blocker escalation
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Pre-release checklist, deployment process, rollback playbook
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Run retros, capture learnings, and drive action items

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk lifecycle, stakeholder updates, escalation paths

## Key Artifacts
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog
- Acceptance Criteria & Definition of Done
- Risk Register
- Retrospective notes and action items

## Communication Cadence
- **Daily**: Standups (15 min) — progress, blockers, dependencies
- **Weekly**: PM + PdM sync; delivery team sync
- **Monthly**: Stakeholder updates
- **As needed**: Ad-hoc escalations

## How to Use These Docs
- Keep your Project Charter updated in the project repo
- Add process-specific docs to `.copilot/` if you want Copilot Spaces to reference them
- Link to relevant sections from your project issues and pull requests
- Use these guides in team onboarding and process training
