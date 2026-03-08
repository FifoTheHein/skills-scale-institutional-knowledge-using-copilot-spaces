# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Engineering Managers / Tech Leads

### Role Summary
Engineering Managers / Tech Leads provide technical direction and leadership for the delivery team. They ensure that solutions are architecturally sound, maintainable, and aligned with platform standards while supporting Developers in execution and growth.

### Responsibilities
- Define and review technical approach and architecture for projects.
- Align implementation with engineering standards (security, reliability, observability).
- Support Developers with design reviews, pairing, and unblocking complex issues.
- Anticipate technical risks and dependencies; partner with Project Managers to surface and manage them.
- Ensure that technical debt and refactoring work are represented in the backlog.

### Goals
- Maintain a healthy, scalable technical foundation for projects.
- Reduce risk from technical unknowns and cross-team dependencies.
- Enable Developers to deliver efficiently with fewer regressions and incidents.

### Typical Communication
- Technical design reviews and architecture discussions.
- Weekly syncs with Product and Project Managers on scope, trade-offs, and feasibility.
- As-needed coordination with other engineering teams (platform, security, infra).

### Interaction with Existing Roles
- **Developers**: Provide guidance, review code and designs, help unblock work.
- **Product Managers**: Collaborate on scope and technical trade-offs to meet product goals.
- **Project Managers**: Partner on timelines, risk mitigation, and dependency tracking.

---

## Designers / UX Researchers

### Role Summary
Designers and UX Researchers ensure that solutions are intuitive, accessible, and aligned with user needs. They translate customer insights into flows, wireframes, and visual designs that Developers can implement.

### Responsibilities
- Conduct user research, interviews, and usability tests as needed.
- Produce UX flows, wireframes, and high-fidelity designs.
- Collaborate with Product Managers on problem framing and feature scope.
- Provide design specifications and guidance to Developers.
- Validate user experience in pre-release and post-release stages.

### Goals
- Deliver experiences that are usable, accessible, and aligned with customer needs.
- Reduce rework caused by unclear or late-stage design changes.
- Ensure a cohesive user experience across related features and surfaces.

### Typical Communication
- Design reviews with Developers and Product Managers.
- Feedback sessions with stakeholders and end-users.
- Documentation of design decisions and rationale in design tools and project docs.

### Interaction with Existing Roles
- **Product Managers**: Partner on problem statements, user journeys, and prioritization.
- **Developers**: Provide specs, clarify interactions, and review implemented UI/UX.
- **Project Managers**: Coordinate design milestones and ensure design tasks are visible on the project board.

---

## Quality Assurance / Test Engineers

### Role Summary
Quality Assurance (QA) and Test Engineers focus on validating that solutions meet acceptance criteria, are reliable, and regressions are minimized. They complement automated testing with exploratory and scenario-based validation.

### Responsibilities
- Collaborate on test strategies and coverage (unit, integration, E2E).
- Create and maintain test cases based on acceptance criteria.
- Run manual and exploratory testing for complex or high-risk features.
- Document bugs clearly and work with Developers and Product Managers to prioritize fixes.
- Contribute to test automation where appropriate.

### Goals
- Improve product quality and reliability.
- Catch defects early in the lifecycle to reduce production incidents.
- Provide clear, actionable feedback on release readiness.

### Typical Communication
- Test summaries during execution and prior to release.
- Bug reports and triage discussions with Developers and Product Managers.
- QA sign-off or quality gates tied to key milestones.

### Interaction with Existing Roles
- **Developers**: Align on reproducible test environments, test data, and bug reproduction.
- **Product Managers**: Clarify acceptance criteria and critical user journeys.
- **Project Managers**: Coordinate test windows, track defects and quality-related risks.

---

## Customer Support / Customer Success

### Role Summary
Customer Support and Customer Success act as the voice of the customer in day-to-day operations. They surface issues from the field, help translate them into actionable work, and support customers through launches and incidents.

### Responsibilities
- Capture customer issues, feedback, and feature requests.
- Provide context and impact for bugs and regressions reported by customers.
- Support communication during releases and incidents.
- Help validate that fixes and features address customer needs.

### Goals
- Reduce customer friction and time-to-resolution for issues.
- Provide a clear feedback loop from customers to the delivery team.
- Support successful adoption of new features.

### Typical Communication
- Incident and release updates from the project team.
- Regular feedback sessions with Product and Project Managers.
- Documentation of common questions, workarounds, and best practices.

### Interaction with Existing Roles
- **Product Managers**: Share prioritized customer feedback and outcomes.
- **Project Managers**: Align on timelines and communication plans for customer-facing changes.
- **Developers**: Provide context for bug impact and confirm resolution.

---

## Business Stakeholders / Sponsors

### Role Summary
Business Stakeholders and Sponsors provide strategic direction, approve investments, and are accountable for realizing business outcomes from the project.

### Responsibilities
- Define or validate business goals and success metrics.
- Approve scope, timelines, and major trade-offs.
- Remove organizational blockers and secure resources.
- Participate in key project reviews and go/no-go decisions.

### Goals
- Ensure projects deliver measurable business value.
- Maintain alignment between project direction and organizational strategy.
- Support the team in resolving high-impact risks and dependencies.

### Typical Communication
- Periodic status updates and milestone reviews.
- Decision meetings on scope changes, funding, or timelines.
- Summary reports focusing on outcomes and risks.

### Interaction with Existing Roles
- **Product Managers**: Align on roadmap, priorities, and success metrics.
- **Project Managers**: Receive clear, concise status and risk updates.
- **Developers**: Occasionally consulted for feasibility and technical impacts (via PM/Tech Lead).

---

## Sales / Solutions Engineers

### Role Summary
Sales and Solutions Engineering roles connect technical capabilities with customer needs during pre-sales and rollout phases. They help ensure that product features and integrations are positioned correctly and are feasible in customer environments.

### Responsibilities
- Provide customer context and use cases for roadmap and feature design.
- Coordinate with engineering on feasibility of proposed solutions.
- Enable customers and internal teams with demos, configurations, and technical documentation.
- Surface pre-sales risks and integration dependencies early.

### Goals
- Improve win rates and customer satisfaction for solution deployments.
- Reduce surprises in implementation by aligning expectations early.
- Ensure product capabilities are correctly understood and represented.

### Typical Communication
- Early discovery and scoping sessions with Product and Engineering.
- Feedback loops on customer requests and objections.
- Coordination around pilot programs and key launches.

### Interaction with Existing Roles
- **Product Managers**: Share market-facing insights and customer requirements.
- **Project Managers**: Align on commitments, timelines, and external dependencies.
- **Developers / Tech Leads**: Clarify technical feasibility and constraints.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

