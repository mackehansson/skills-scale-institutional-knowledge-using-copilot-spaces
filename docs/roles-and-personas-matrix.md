# OctoAcme Responsibility Matrix

This document provides a RACI-style matrix mapping common project activities to team roles. Use it to assign clear ownership at the start of a project and reduce ambiguity during execution.

See also: [Roles & Personas](octoacme-roles-and-personas.md) | [Role Onboarding Template](role-onboarding-template.md)

---

## RACI Key

| Letter | Meaning |
|--------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; final decision-maker |
| **C** | **Consulted** — provides input before or during the activity |
| **I** | **Informed** — kept up-to-date on progress or decisions |

---

## Responsibility Matrix

| Activity | PdM | PM | Scrum Master | Developers | QA | UX | BA | CSM | DevOps | Stakeholders |
|---|---|---|---|---|---|---|---|---|---|---|
| **Project Initiation** (problem statement, charter) | A | R | I | C | I | C | C | C | I | C |
| **Backlog Prioritization** | A | C | C | C | C | C | R | C | I | I |
| **Sprint Planning** | C | C | A | R | C | C | C | I | I | I |
| **Acceptance Criteria Definition** | A | C | I | C | C | C | R | C | I | I |
| **UX Design & Prototyping** | C | I | I | C | C | A/R | C | I | I | I |
| **Development / Implementation** | C | I | I | A/R | C | C | C | I | C | I |
| **QA Sign-off / Test Execution** | I | C | I | C | A/R | C | C | I | C | I |
| **Release / Deployment** | I | A | I | C | C | I | I | C | R | I |
| **Post-release Monitoring** | I | I | I | C | C | I | I | C | A/R | I |
| **Incident Response** | I | C | I | R | C | I | I | C | A | I |
| **Customer Feedback Collection** | C | I | I | I | I | C | C | A/R | I | I |
| **Stakeholder Communication / Updates** | C | A/R | I | I | I | I | I | C | I | I |
| **Retrospective & Process Improvement** | C | C | A/R | R | R | R | C | I | C | I |

> **Note**: A single cell showing `A/R` means the same person is both accountable and doing the work — common on small teams.

---

## How to Use This Matrix

### 1. Assign roles at kickoff
At project kickoff, review the matrix with the full team and confirm who is filling each role. Update any cells where the default assignment doesn't fit your team structure. Record named owners in the project one-pager.

### 2. Ensure single accountability
Each activity should have exactly one **A**. If two people share accountability, clarify who has the final say to avoid decision bottlenecks.

### 3. Limit the number of Consulted parties
More **C** entries mean more coordination overhead. For small or fast-moving teams, trim the list of consulted parties to essential stakeholders only.

### 4. Recommended defaults for small teams
On lean teams where roles overlap, use these suggested consolidations:

| Combined Role | Activities Covered |
|---|---|
| PM + Scrum Master | Sprint facilitation, status reporting, impediment removal |
| PdM + BA | Backlog refinement, acceptance criteria, requirements |
| Developer + DevOps | Deployment, CI/CD, post-release monitoring |
| PdM + CSM | Customer feedback loops and roadmap input |

### 5. Review and update during retrospectives
The matrix is a living document. Add project-specific activities or adjust assignments as the team learns what works best.
