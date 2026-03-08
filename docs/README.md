# OctoAcme Project Management — Overview

This README summarizes OctoAcme's project management processes for new and existing team members. For full details, refer to the individual documents linked in each section.

---

## Principles

OctoAcme project delivery is guided by five core principles:

- **Customer-first** — prioritize customer value and usability.
- **Iterative delivery** — ship small, testable increments.
- **Clear ownership** — every project has a named Project Manager (PM) and Product Lead.
- **Data-informed decisions** — measure impact and iterate based on evidence.
- **Psychological safety** — encourage feedback and learning.

---

## Core Roles & Personas

See [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) for full persona definitions, responsibilities, and interaction patterns.

| Role | Responsibilities |
|---|---|
| **Project Manager (PM)** | Coordinates delivery, schedules, risks, and stakeholder communication |
| **Product Manager (PdM)** | Defines outcomes, prioritizes backlog, and measures success |
| **Developers** | Implement features, write tests, participate in design and code reviews |
| **Engineering Manager / Tech Lead** | Provides technical direction, architecture guidance, and developer support |
| **Designer / UX Researcher** | Translates user needs into flows, wireframes, and validated designs |
| **QA / Test Engineer** | Validates quality, acceptance criteria, and release readiness |
| **Customer Support / Customer Success** | Surfaces customer issues and supports launches and incidents |
| **Business Stakeholder / Sponsor** | Approves investments, defines business goals, removes organizational blockers |
| **Sales / Solutions Engineer** | Connects technical capabilities to customer needs during pre-sales and rollout |

---

## Key Artifacts

| Artifact | Purpose |
|---|---|
| Project One-pager / Charter | Problem statement, goals, success metrics, and initial timeline |
| Roadmap & Release Plan | Milestone map and release schedule |
| Sprint / Iteration Backlog | Prioritized work items with acceptance criteria |
| Definition of Done (DoD) | Shared quality bar for completing work |
| Risk Register | Tracked risks with impact, likelihood, owner, and mitigation |
| Retrospective Notes | Learnings and action items from each sprint or milestone |

---

## Project Lifecycle

### 1. Initiation
> Full guide: [`octoacme-project-initiation.md`](octoacme-project-initiation.md)

- Confirm the business need and define measurable success criteria.
- Identify stakeholders and create a communication plan.
- Produce a **Project One-pager** (problem, goal, metrics, timeline, risks).
- Hold a sponsor/stakeholder alignment meeting and get a **go/no-go** decision before moving to planning.

### 2. Planning
> Full guide: [`octoacme-project-planning.md`](octoacme-project-planning.md)

- Run a kickoff meeting with the delivery team and stakeholders.
- Build a **prioritized backlog** with acceptance criteria and estimates.
- Document the **Definition of Done** and an initial QA approach.
- Create a **release plan and milestone map**.
- Capture dependencies and risks in the Risk Register.

### 3. Execution & Tracking
> Full guide: [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md)

- Follow the **team rhythm**: daily standups (15 min), weekly delivery sync, sprint demo/review.
- Manage work through the **project board** (Backlog → Ready → In Progress → In Review → QA → Done).
- Keep PRs small (≤ 400 lines), linked to issues, and passing CI before requesting review.
- Track velocity and burndown; monitor success metrics from the One-pager.

### 4. Risk Management & Communication
> Full guide: [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md)

- Maintain a **Risk Register** (ID, description, impact, likelihood, owner, mitigation, status).
- Review and update risks weekly; escalate along the path: **Team → PM → Product Lead → Sponsor**.
- Provide stakeholders with regular status updates using the weekly status template:
  - Progress this week / Next steps / Risks & blockers / Decisions needed.

### 5. Release & Deployment
> Full guide: [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md)

- Classify each release: **Patch** (hotfix), **Minor** (incremental feature), or **Major** (breaking change).
- Pre-release requirements: all acceptance criteria met, CI and security scans passing, release notes drafted, rollback plan documented.
- Deploy to **staging** first with smoke tests, then to **production** (automated pipeline preferred), then run post-deploy verifications and announce to stakeholders.
- Follow the **Rollback & Incident Playbook** if a deployment causes a critical issue.

### 6. Retrospective & Continuous Improvement
> Full guide: [`octoacme-retrospective-and-continuous-improvement.md`](octoacme-retrospective-and-continuous-improvement.md)

- Hold a retrospective after each sprint, release, or major incident (45–75 min).
- Structure: What went well / What could be improved / Action items / Follow-up on previous items.
- Prioritize **2–3 top action items** per retrospective, add them to the backlog with clear owners and due dates.
- Review outstanding actions in the weekly PM sync and measure their impact over time.

---

## Communication Cadence

| Cadence | Participants | Purpose |
|---|---|---|
| Daily standup (15 min) | Delivery team | Progress, blockers, dependencies |
| Twice-weekly (or as agreed) | Delivery team | Deep-dive on in-flight work |
| Weekly PM + PdM sync | PM, PdM | Alignment, risks, decisions |
| Weekly delivery sync | PM + team leads | Status, risks, escalations |
| Monthly stakeholder update | PM, stakeholders | Roadmap progress, upcoming milestones |
| Ad-hoc escalation | As needed | Business-impacting issues |

---

## Quality & Blocker Management

**Quality practices:**
- Unit tests for all new logic; integration tests where applicable.
- End-to-end smoke tests for critical flows before each release.
- Security scanning in CI on every PR.
- Manual QA for feature acceptance when needed.

**Blocker escalation:**
1. **Level 1** — Team-level triage in daily standup.
2. **Level 2** — PM escalates to Product Lead and dependent teams.
3. **Level 3** — Sponsor-level escalation for business-impacting issues.

---

## Document Index

| Document | Description |
|---|---|
| [`octoacme-project-management-overview.md`](octoacme-project-management-overview.md) | High-level summary of principles, roles, artifacts, and lifecycle |
| [`octoacme-roles-and-personas.md`](octoacme-roles-and-personas.md) | Detailed persona definitions for all nine project roles |
| [`octoacme-raci-matrix.md`](octoacme-raci-matrix.md) | RACI matrix clarifying accountability across roles for key activities |
| [`octoacme-project-initiation.md`](octoacme-project-initiation.md) | Initiation checklist and One-pager template |
| [`octoacme-project-planning.md`](octoacme-project-planning.md) | Planning activities, backlog template, sprint planning guidance |
| [`octoacme-definition-of-done.md`](octoacme-definition-of-done.md) | Shared DoD standard, sprint/release DoD, and project-level override guidance |
| [`octoacme-meeting-templates.md`](octoacme-meeting-templates.md) | Reusable agendas for kickoff, sprint planning, standup, review, retro, and design review |
| [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md) | Day-to-day execution, PR workflow, metrics |
| [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md) | Risk register, stakeholder communication templates |
| [`octoacme-release-and-deployment.md`](octoacme-release-and-deployment.md) | Release types, QA sign-off checklist, deployment checklist, rollback playbook |
| [`octoacme-retrospective-and-continuous-improvement.md`](octoacme-retrospective-and-continuous-improvement.md) | Retrospective structure and continuous improvement practices |
