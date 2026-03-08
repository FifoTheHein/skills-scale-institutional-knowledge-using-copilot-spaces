# OctoAcme — Meeting Templates

## Purpose
Provide reusable agendas and facilitation guides for the most common recurring meetings in an OctoAcme project. Consistent meeting structures reduce preparation overhead, improve focus, and make it easier to onboard new team members.

---

## Project Kickoff Meeting

**When:** Start of planning phase, after go/no-go approval  
**Duration:** 60–90 minutes  
**Required attendees:** Project Manager, Product Manager, Developers, Engineering Manager / Tech Lead, Designer (if applicable), QA Engineer (if applicable)  
**Optional attendees:** Business Stakeholder / Sponsor, Customer Support, Sales / Solutions Engineer

### Agenda

| # | Topic | Owner | Time |
|---|---|---|---|
| 1 | Welcome & introductions | PM | 5 min |
| 2 | Project background & problem statement | PdM | 10 min |
| 3 | Goals, success metrics, and scope | PdM | 10 min |
| 4 | High-level architecture / technical approach | EM / Tech Lead | 10 min |
| 5 | Design overview (if ready) | Designer | 5 min |
| 6 | Roles, responsibilities & RACI | PM | 5 min |
| 7 | Timeline, milestones & release plan | PM | 10 min |
| 8 | Risks & dependencies (initial) | PM + Team | 10 min |
| 9 | Team working agreements (ceremonies, tools, communication) | PM | 5 min |
| 10 | Q&A and next steps | All | 10 min |

### Outputs
- [ ] Team is aligned on goals, scope, and roles
- [ ] Key risks and dependencies identified
- [ ] Working agreements documented
- [ ] First sprint / iteration backlog seeded

---

## Sprint Planning Meeting

**When:** Start of each sprint / iteration  
**Duration:** 1 hour per week of sprint length (e.g., 2-week sprint = 2 hours max)  
**Required attendees:** Project Manager, Product Manager, Developers, Engineering Manager / Tech Lead  
**Optional attendees:** Designer, QA Engineer

### Agenda

| # | Topic | Owner | Time |
|---|---|---|---|
| 1 | Review sprint goal | PdM | 5 min |
| 2 | Backlog review: top items ready for sprint | PdM | 10 min |
| 3 | Capacity check (who is available, any PTO, dependencies) | PM | 5 min |
| 4 | Item-by-item walkthrough: acceptance criteria, estimates, assignees | Team | 30–60 min |
| 5 | Confirm sprint commitment & sprint goal | PM + PdM | 5 min |
| 6 | Surface any blockers or dependencies for the sprint | All | 5 min |

### Outputs
- [ ] Sprint backlog committed with owners and estimates
- [ ] Sprint goal clearly articulated
- [ ] Any blockers or dependencies flagged in risk register

---

## Daily Standup

**When:** Each working day during execution  
**Duration:** 15 minutes maximum  
**Required attendees:** Developers, PM, EM / Tech Lead  
**Optional attendees:** Designer, QA Engineer

### Format (per person, ~2 min each)
1. **What did I complete since the last standup?**
2. **What am I working on today?**
3. **Do I have any blockers or dependencies?**

### Facilitation Notes
- Keep it to status; take detailed discussions offline ("parking lot").
- PM captures blockers immediately and escalates if needed (see [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md)).
- If attendance is fully remote, async standups (written) in the team channel are acceptable.

---

## Weekly Delivery Sync

**When:** Weekly, mid-sprint or once per week  
**Duration:** 30–45 minutes  
**Required attendees:** PM, PdM, EM / Tech Lead  
**Optional attendees:** Designer, QA, stakeholder representatives

### Agenda

| # | Topic | Owner | Time |
|---|---|---|---|
| 1 | Sprint / milestone progress review (burndown / board) | PM | 10 min |
| 2 | Risk register review: new or changed risks | PM | 5 min |
| 3 | Dependency check: cross-team or external blockers | PM + EM | 5 min |
| 4 | Design / QA status (if in-flight) | Des / QA | 5 min |
| 5 | Decisions needed | All | 10 min |
| 6 | Actions & owners | PM | 5 min |

### Outputs
- [ ] Updated risk register
- [ ] Escalated blockers actioned
- [ ] Stakeholder status update drafted (using template in [`octoacme-risks-and-communication.md`](octoacme-risks-and-communication.md))

---

## Sprint Review / Demo

**When:** End of each sprint or milestone  
**Duration:** 30–60 minutes  
**Required attendees:** Full delivery team, Product Manager  
**Optional attendees:** Business Stakeholder / Sponsor, Customer Support, Sales

### Agenda

| # | Topic | Owner | Time |
|---|---|---|---|
| 1 | Sprint goal recap | PdM | 3 min |
| 2 | Demo of completed work | Dev / Designer | 15–30 min |
| 3 | What was deferred and why | PdM | 5 min |
| 4 | Metrics / success indicators (if measurable) | PdM | 5 min |
| 5 | Stakeholder feedback & questions | All | 10 min |
| 6 | Next sprint preview | PdM | 5 min |

### Outputs
- [ ] Stakeholder feedback captured
- [ ] Deferred items re-prioritized in backlog
- [ ] Demo recording or notes saved for asynchronous stakeholders

---

## Retrospective Meeting

**When:** End of each sprint, release, or major milestone; also after incidents  
**Duration:** 45–75 minutes  
**Required attendees:** Full delivery team  
**Optional attendees:** PM may invite a guest facilitator for process-intensive retros

### Format (suggested: Start / Stop / Continue or 4Ls)

**Option A — Start / Stop / Continue**
1. **Start** — What should we begin doing that we are not doing?
2. **Stop** — What should we stop doing that is not helping?
3. **Continue** — What is working well that we should keep doing?

**Option B — 4Ls**
1. **Liked** — What did we enjoy or appreciate?
2. **Learned** — What did we learn?
3. **Lacked** — What was missing or could have been better?
4. **Longed for** — What do we wish we had?

### Agenda

| # | Topic | Owner | Time |
|---|---|---|---|
| 1 | Set the stage (safety check, ground rules) | Facilitator (PM or guest) | 5 min |
| 2 | Follow-up on previous action items | PM | 5 min |
| 3 | Individual idea generation (silent, 5 min) | All | 5 min |
| 4 | Share & group themes | Facilitator | 10 min |
| 5 | Dot-vote on top themes | All | 5 min |
| 6 | Discussion on top 2–3 themes | All | 20–30 min |
| 7 | Action items: owner, due date, success criteria | PM | 10 min |

### Outputs
- [ ] 2–3 prioritized action items with owners and due dates
- [ ] Action items added to project backlog or issues
- [ ] Notes saved in project repo or shared doc

---

## Design Review

**When:** When UX flows or designs are ready for developer implementation  
**Duration:** 30–60 minutes  
**Required attendees:** Designer, Developer(s), Product Manager  
**Optional attendees:** QA Engineer, Engineering Manager / Tech Lead

### Agenda

| # | Topic | Owner | Time |
|---|---|---|---|
| 1 | Design goals and user problem | Designer / PdM | 5 min |
| 2 | Walkthrough of UX flows and screens | Designer | 15–25 min |
| 3 | Developer questions: feasibility, edge cases, states | Dev / EM | 10–15 min |
| 4 | Accessibility considerations | Designer | 5 min |
| 5 | Agreement on open items and next steps | All | 5 min |

### Outputs
- [ ] Design specs approved or feedback documented
- [ ] Open design questions captured as tasks
- [ ] Acceptance criteria updated if design reveals scope changes

---

## Reference
- RACI for meeting ownership: [`octoacme-raci-matrix.md`](octoacme-raci-matrix.md)
- Working agreements and team cadence: [`octoacme-execution-and-tracking.md`](octoacme-execution-and-tracking.md)
- Retrospective action item tracking: [`octoacme-retrospective-and-continuous-improvement.md`](octoacme-retrospective-and-continuous-improvement.md)
