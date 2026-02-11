# OctoAcme Roles and Personas — RACI Matrix

## Purpose
This document provides a RACI (Responsible, Accountable, Consulted, Informed) mapping of key activities across the project lifecycle to roles. Use this to clarify ownership, coordination, and communication expectations.

## RACI Legend
- **R (Responsible):** Does the work to complete the activity
- **A (Accountable):** Ultimately answerable for the completion and quality; only one A per activity
- **C (Consulted):** Provides input and expertise; two-way communication
- **I (Informed):** Kept informed of progress; one-way communication

---

## Project Initiation

| Activity | Developer | Product Manager | Project Manager | Business Analyst | UX Designer | Scrum Master | Technical Writer | QA Automation Engineer | Customer Support |
|----------|-----------|----------------|-----------------|------------------|-------------|--------------|------------------|----------------------|------------------|
| Define problem statement and success metrics | I | A/R | C | C | I | I | I | I | C |
| Create project one-pager | I | A | R | C | I | I | I | I | C |
| Identify stakeholders | I | R | A | C | I | C | I | I | C |
| High-level timeline and milestones | C | C | A/R | I | I | C | I | I | I |
| Initial risk assessment | C | C | A/R | C | I | C | I | C | I |
| Approve to move into planning | I | A | R | I | I | I | I | I | I |

---

## Project Planning

| Activity | Developer | Product Manager | Project Manager | Business Analyst | UX Designer | Scrum Master | Technical Writer | QA Automation Engineer | Customer Support |
|----------|-----------|----------------|-----------------|------------------|-------------|--------------|------------------|----------------------|------------------|
| Project kickoff meeting | R | A | R | R | R | R | C | R | C |
| Requirements gathering and analysis | C | C | I | A/R | C | I | I | C | C |
| User journey and flow design | C | C | I | C | A/R | I | I | C | C |
| Create prioritized backlog | R | A | C | C | C | R | I | C | I |
| Estimate scope | A/R | C | C | C | I | R | I | C | I |
| Define Definition of Done | R | C | C | C | C | A/R | I | R | I |
| Create test plan | R | C | C | C | I | I | I | A/R | I |
| Identify dependencies | R | C | A/R | C | I | R | I | C | I |
| Create release plan | C | C | A/R | I | I | R | I | C | I |
| Documentation planning | C | C | C | C | I | I | A/R | I | C |

---

## Execution & Tracking

| Activity | Developer | Product Manager | Project Manager | Business Analyst | UX Designer | Scrum Master | Technical Writer | QA Automation Engineer | Customer Support |
|----------|-----------|----------------|-----------------|------------------|-------------|--------------|------------------|----------------------|------------------|
| Daily standups | R | I | I | R | R | A/R | R | R | I |
| Feature implementation | A/R | C | I | C | I | I | I | I | I |
| Code reviews | A/R | I | I | I | I | I | I | C | I |
| Design implementation | A/R | C | I | I | C | I | I | I | I |
| Requirements clarification | R | C | I | A/R | C | I | I | C | I |
| Automated testing | R | I | I | I | I | I | I | A/R | I |
| Bug triage and prioritization | R | A | C | C | I | R | I | R | C |
| Sprint demos | R | A | R | R | R | R | I | R | I |
| Documentation updates | C | C | I | C | I | I | A/R | I | C |
| Track velocity and burndown | I | C | R | I | I | A/R | I | I | I |
| Remove blockers | I | C | C | I | I | A/R | I | I | I |
| Update project board | R | I | R | I | I | A/R | I | I | I |

---

## Release & Deployment

| Activity | Developer | Product Manager | Project Manager | Business Analyst | UX Designer | Scrum Master | Technical Writer | QA Automation Engineer | Customer Support |
|----------|-----------|----------------|-----------------|------------------|-------------|--------------|------------------|----------------------|------------------|
| Release planning | R | A | R | C | I | R | C | R | C |
| Regression testing | R | I | I | I | I | I | I | A/R | I |
| User acceptance testing | C | A | C | R | R | I | I | R | R |
| Release documentation | C | C | C | C | I | I | A/R | I | C |
| Deploy to production | A/R | I | R | I | I | I | I | C | I |
| Smoke testing post-deploy | R | I | C | I | I | I | I | A/R | I |
| Customer communication | I | A | R | I | I | I | C | I | R |
| Monitor success metrics | R | A | R | C | C | C | I | R | R |

---

## Retrospective & Continuous Improvement

| Activity | Developer | Product Manager | Project Manager | Business Analyst | UX Designer | Scrum Master | Technical Writer | QA Automation Engineer | Customer Support |
|----------|-----------|----------------|-----------------|------------------|-------------|--------------|------------------|----------------------|------------------|
| Facilitate retrospective | R | R | R | R | R | A/R | R | R | R |
| Gather feedback | R | R | R | R | R | R | R | R | R |
| Document lessons learned | I | C | R | I | I | A/R | C | I | C |
| Identify process improvements | R | R | R | R | R | A/R | R | R | R |
| Implement process changes | R | C | R | C | C | A/R | C | C | C |
| Update documentation | C | I | I | I | I | C | A/R | I | I |
| Track improvement metrics | I | C | R | I | I | A/R | I | C | C |

---

## Notes on RACI Usage
- When an activity shows **A/R** for a role, that role is both accountable and responsible (typically for smaller activities or single-owner tasks)
- For collaborative activities, multiple roles may share **R** while one role holds **A**
- Adjust this RACI to fit your team structure and project context
- Review and update during retrospectives as team practices evolve

## Related Documentation
- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md) — Detailed role descriptions
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning Guide](octoacme-project-planning.md)
- [Execution & Tracking Guide](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement Guide](octoacme-retrospective-and-continuous-improvement.md)
