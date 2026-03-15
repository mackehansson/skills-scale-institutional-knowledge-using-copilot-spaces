# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

See also: [Responsibility Matrix](roles-and-personas-matrix.md) | [Role Onboarding Template](role-onboarding-template.md)

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

### Interactions with Other Roles
- **PM**: Receive task assignments and timeline guidance; surface blockers early.
- **PdM**: Clarify acceptance criteria and feature intent.
- **QA**: Coordinate test handoffs and resolve defects.
- **Scrum Master**: Raise impediments during standups and retrospectives.
- **DevOps**: Align on deployment steps and environment requirements.

---

## Product Manager (PdM)

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

### Interactions with Other Roles
- **PM**: Align on scope, timeline, and resource trade-offs.
- **BA**: Review and refine requirements and user stories.
- **UX Designer**: Co-define user flows and validate usability.
- **CSM**: Gather post-launch feedback to inform the roadmap.
- **Stakeholders**: Present roadmap and obtain approvals.

---

## Project Manager (PM)

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

### Interactions with Other Roles
- **PdM**: Align on scope and priority during planning and execution.
- **Scrum Master**: Coordinate sprint ceremonies and remove process blockers.
- **Developers**: Communicate timelines and surface cross-team dependencies.
- **QA**: Track testing progress and quality gates for releases.
- **Stakeholders**: Provide status updates and manage expectations.

---

## QA / Testing

### Role Summary
QA engineers validate that features meet acceptance criteria and quality standards before release. They own the test strategy, identify defects, and provide a quality gate for releases.

### Responsibilities
- Define and execute test plans and test cases
- Validate acceptance criteria for each story or feature
- Report and track defects to resolution
- Participate in sprint planning to estimate test effort
- Contribute to the Definition of Done

### Goals
- Prevent defects from reaching production
- Maintain clear, repeatable test coverage
- Provide confidence for releases

### Typical Communication
- Sprint planning and daily standups
- Defect reports and test result summaries
- Sign-off notes for releases

### Interactions with Other Roles
- **Developers**: Triage defects and confirm fixes.
- **PM**: Report quality status and blockers ahead of release.
- **PdM**: Clarify acceptance criteria when stories are ambiguous.
- **DevOps**: Coordinate deployment to test environments.
- **CSM**: Share known issues that may affect customer experience.

---

## Stakeholders

### Role Summary
Stakeholders are executives, sponsors, customers, or business representatives who have a vested interest in the project outcome. They provide input, approvals, and resources.

### Responsibilities
- Provide business context and strategic direction
- Review and approve project scope and key decisions
- Escalate organizational blockers when needed
- Accept or validate deliverables at milestones

### Goals
- Ensure the project delivers business and customer value
- Make timely decisions to keep delivery on track

### Typical Communication
- Monthly or milestone-based status briefings
- Decision or approval requests via PM or PdM

### Interactions with Other Roles
- **PM**: Receive status updates; provide decisions and approvals.
- **PdM**: Align on product direction and priorities.
- **CSM**: Share strategic customer context and expectations.

---

## Scrum Master

### Role Summary
The Scrum Master facilitates Agile/Scrum ceremonies, helps remove impediments, and coaches the team on iterative delivery practices. They protect team focus and support continuous improvement.

### Responsibilities
- Facilitate daily standups, sprint planning, sprint reviews, and retrospectives
- Identify and remove blockers and impediments
- Coach the team on Agile best practices and self-organization
- Shield the team from unplanned interruptions during a sprint
- Track and report sprint velocity and health metrics

### Goals
- Maximize team throughput and predictability
- Maintain a healthy, sustainable team cadence
- Continuously improve team processes through retrospectives

### Typical Communication
- Daily standups and sprint ceremonies
- Impediment logs and escalation to PM or leadership
- Retrospective action items and follow-up

### Interactions with Other Roles
- **PM**: Escalate cross-team blockers and align on sprint goals. During planning, confirm capacity and scope; during execution, surface impediments promptly.
- **PdM**: Ensure backlog items are refined and ready before sprint planning.
- **Developers**: Protect sprint commitments and facilitate self-organization.
- **QA**: Coordinate testing timelines within sprint cadence.
- **Stakeholders**: Communicate progress via sprint reviews; manage ad-hoc requests.

---

## UX Designer

### Role Summary
The UX Designer designs solutions that are usable, accessible, and aligned with user needs. They translate requirements into intuitive flows and visual prototypes.

### Responsibilities
- Conduct user research and synthesize findings into design requirements
- Create user flows, wireframes, mockups, and interactive prototypes
- Ensure accessibility and usability best practices are applied
- Collaborate on acceptance criteria that capture UX expectations
- Review implemented features against design specifications

### Goals
- Deliver a consistent, user-centered product experience
- Reduce rework by validating designs before development begins
- Increase feature adoption through intuitive design

### Typical Communication
- Design reviews and feedback sessions with PdM and Developers
- Shared design files (e.g., Figma) linked in stories
- Handoff notes in tickets describing interaction details

### Interactions with Other Roles
- **PdM**: Co-define user stories and validate that designs meet product goals. During planning, provide design estimates; during execution, review implementations.
- **Developers**: Hand off detailed specs and answer design questions during development.
- **BA**: Align designs with documented requirements and business rules.
- **QA**: Share design specs so testers can validate visual and interaction fidelity.
- **Stakeholders**: Present prototypes for early feedback before development starts.

---

## Business Analyst (BA)

### Role Summary
The Business Analyst translates business needs into clear, actionable requirements. They bridge the gap between stakeholders and the delivery team to ensure the right solution is built.

### Responsibilities
- Elicit, document, and refine requirements and user stories
- Analyze current-state processes and identify improvement opportunities
- Validate that deliverables meet business objectives and requirements
- Maintain a requirements traceability matrix
- Facilitate workshops and requirements-gathering sessions

### Goals
- Ensure requirements are complete, unambiguous, and testable
- Reduce scope creep through clear documentation
- Improve alignment between business goals and technical solutions

### Typical Communication
- Requirements documents, user story descriptions, and acceptance criteria
- Workshops and structured interviews with stakeholders
- Refinement sessions with PdM and Developers

### Interactions with Other Roles
- **PdM**: Refine and validate requirements against product strategy. During initiation, capture business goals; during planning, break down epics into stories.
- **PM**: Communicate requirements dependencies and scope changes.
- **Developers**: Clarify requirements and confirm technical feasibility during refinement.
- **QA**: Provide test scenarios and acceptance criteria aligned with requirements.
- **Stakeholders**: Conduct discovery sessions and validate requirements sign-off.

---

## Customer Success Manager (CSM)

### Role Summary
The Customer Success Manager advocates for customers, manages post-launch engagement, and feeds real-world feedback back into the product cycle.

### Responsibilities
- Collect, synthesize, and relay customer feedback to PdM and PM
- Monitor product adoption, health metrics, and support escalations
- Coordinate post-release communications and customer onboarding
- Identify at-risk customers or emerging issues early
- Support product launches with enablement materials and training

### Goals
- Maximize customer satisfaction and product adoption
- Minimize customer churn through proactive engagement
- Ensure the team has visibility into real-world product usage

### Typical Communication
- Periodic feedback reports shared with PdM and PM
- Customer-facing release notes and communications
- Escalation alerts during and after releases

### Interactions with Other Roles
- **PdM**: Provide customer insight to inform the roadmap. Post-release, share adoption data and emerging feature requests.
- **PM**: Escalate customer-impacting issues and coordinate release announcements.
- **QA**: Share known customer pain points to prioritize testing focus areas.
- **Stakeholders**: Represent the voice of the customer in strategic discussions.
- **Developers / DevOps**: Coordinate on hotfix priorities when customer-critical issues arise.

---

## DevOps / Platform Engineer

### Role Summary
The DevOps/Platform Engineer ensures reliable, automated deployment pipelines, manages infrastructure, and maintains the observability and reliability of production systems.

### Responsibilities
- Design and maintain CI/CD pipelines and deployment workflows
- Manage cloud or on-prem infrastructure, environments, and configuration
- Monitor production reliability, respond to incidents, and conduct post-mortems
- Automate operational tasks (provisioning, scaling, patching)
- Ensure security, compliance, and cost efficiency of infrastructure

### Goals
- Achieve high deployment frequency with low change-failure rate
- Maintain system reliability and reduce mean-time-to-recover (MTTR)
- Reduce manual operational toil through automation

### Typical Communication
- Deployment runbooks and environment setup guides
- Incident reports and post-mortem summaries
- Infrastructure change requests in the project board

### Interactions with Other Roles
- **Developers**: Provide environment access, pipeline guidance, and deployment support. During planning, review infrastructure needs; during release, execute and monitor deployments.
- **QA**: Provision and maintain test environments; coordinate deployment windows.
- **PM**: Communicate deployment schedules, incidents, and infrastructure risks.
- **PdM**: Flag infrastructure constraints that affect feature feasibility or timelines.
- **Stakeholders**: Report on system reliability and SLA compliance post-release.

---

## How to Apply These Personas

Use this section to decide which roles to engage and at what level of involvement for each project.

**Full-time involvement** (dedicated for the duration of the project):
- PM, PdM, and Developers are typically full-time on a project.
- Scrum Master is full-time on actively sprinting teams.

**Part-time / as-needed involvement**:
- UX Designer: heavily involved during discovery and design phases; lighter during execution.
- BA: most active during initiation and planning; available on-call during execution for clarification.
- DevOps: heavily involved at kickoff (environment setup) and during release; monitoring post-release.
- CSM: engaged during release planning and post-launch; periodic check-ins during execution.

**External stakeholder involvement**:
- Stakeholders attend milestone reviews and decision gates, not day-to-day ceremonies.
- If a stakeholder needs ongoing involvement, assign them a named role (e.g., Executive Sponsor) in the project charter.

**When to assign roles**:
1. **At project initiation**: identify which roles are needed and confirm availability in the project one-pager.
2. **During kickoff**: assign responsibilities using the [Responsibility Matrix](roles-and-personas-matrix.md) and complete the [Role Onboarding Template](role-onboarding-template.md) for each new participant.
3. **Small teams**: on lean teams, one person may cover multiple roles (e.g., PM + Scrum Master, or PdM + BA). Document combined roles explicitly to avoid gaps.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

