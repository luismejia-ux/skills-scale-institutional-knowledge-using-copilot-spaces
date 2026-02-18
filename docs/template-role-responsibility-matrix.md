# Role Responsibility Matrix (RACI) Template

**Project**: [Project Name]  
**Last Updated**: [Date]  
**Owner**: [Project Manager Name]

## What is RACI?

- **R** = Responsible: Person who does the work to complete the task
- **A** = Accountable: Person ultimately answerable for the task (only one A per task)
- **C** = Consulted: People whose opinions are sought (two-way communication)
- **I** = Informed: People who are kept up to date (one-way communication)

## Project Phase: [Phase Name, e.g., Planning, Execution, Release]

| Activity/Decision | PM | PdM | Dev | QA | UX | Data | Sec | Release Mgr | Customer Success | Stakeholder |
|------------------|----|----|-----|----|----|------|-----|-------------|------------------|-------------|
| Define project charter | C | A | I | I | C | I | I | I | C | R |
| Prioritize backlog | C | A/R | C | C | C | C | I | I | C | I |
| Technical design | C | C | R/A | C | C | I | C | I | I | I |
| UI/UX design | C | C | C | I | R/A | C | I | I | C | I |
| Feature development | I | C | R/A | C | C | I | C | I | I | I |
| Write tests | I | I | R/A | R | I | I | C | I | I | I |
| Code review | I | I | R/A | C | I | I | C | I | I | I |
| Security review | C | I | C | I | I | I | R/A | I | I | I |
| User acceptance testing | C | C | C | R/A | C | I | I | I | C | I |
| Deploy to production | C | I | C | C | I | I | C | R/A | I | I |
| Monitor production | I | C | R | R | I | R | R | A | C | I |
| Incident response | A | C | R | R | I | I | R | C | C | I |
| Customer communication | C | C | I | I | I | I | I | I | R/A | C |
| Success metrics tracking | C | C | C | I | C | R/A | I | I | C | I |

## Decision Authority Matrix

| Decision Type | Primary Decision Maker | Consulted | Informed |
|--------------|----------------------|----------|----------|
| Product roadmap & priorities | Product Manager | PM, Stakeholder, Dev Lead, Customer Success | Full team |
| Technical architecture | Tech Lead / Engineering Manager | Developers, PM, Security | Product team |
| Project scope changes | Product Manager + Stakeholder | PM, Dev Lead | Full team |
| Resource allocation | Engineering Manager + PM | Product Manager, Stakeholder | Team |
| Release go/no-go | Release Manager | PM, PdM, QA, Security | Full team, Stakeholders |
| Security exceptions | Security Engineer + CISO | Dev, PM | Stakeholder |
| Design approach | UX Designer | Product Manager, Developers | PM, Stakeholders |
| Deployment strategy | Release Manager + SRE | Dev, PM, Security | Product team, Stakeholders |

## Escalation Matrix

| Issue Type | Level 1 | Level 2 | Level 3 |
|-----------|---------|---------|---------|
| Technical blockers | Dev → Tech Lead | Engineering Manager | VP Engineering |
| Product decisions | PdM → Product Lead | VP Product | Stakeholder/Executive |
| Project timeline/scope | PM → Product Lead | VP Product + VP Engineering | Stakeholder/Executive |
| Security incidents | Security Engineer → Security Manager | CISO | Executive Team |
| Customer escalations | Customer Success → CS Manager | VP Customer Success | Executive Team |

## Communication Ownership

| Communication Type | Owner (R/A) | Contributors (C) | Audience (I) |
|-------------------|-----------|-----------------|-------------|
| Weekly status update | PM | All leads | Stakeholders, full team |
| Sprint demos | PM | Developers, UX | Full team, Stakeholders |
| Release notes | Release Manager | Product Manager, Developers | Customers, Support, Sales |
| Incident communications | PM | Engineers, Customer Success | Stakeholders, Customers |
| Roadmap updates | Product Manager | PM, UX, Data | Stakeholders, full team |
| Architecture docs | Tech Lead | Developers, Security | Engineering team |
| User research findings | UX Designer | Product Manager, Data | Full team |
| Security advisories | Security Engineer | PM, Release Manager | Engineering, Stakeholders |

## Meetings & Ceremonies

| Meeting | Facilitator | Required Attendees | Optional/As-Needed |
|---------|------------|-------------------|-------------------|
| Daily standup | PM or Scrum Master | Dev team, PM, PdM | UX, QA, others as needed |
| Sprint planning | PM | Dev team, PM, PdM, UX | QA, Security, Data |
| Sprint demo | PM | Dev team, PM, PdM, Stakeholders | All interested parties |
| Retrospective | PM | Dev team, PM, PdM, UX, QA | Release Manager |
| Weekly PM/PdM sync | PM | PM, PdM | Dev Lead, UX Lead |
| Technical design review | Tech Lead | Dev team, Security | PM, PdM, UX |
| Release planning | Release Manager | PM, PdM, Dev Lead, QA, Security | Stakeholders |
| Incident post-mortem | Incident Commander | Incident response team | PM, PdM, Stakeholders |

## Role-Specific Responsibilities by Project Phase

### Project Initiation
- **Stakeholder Advisor**: Approve project charter, provide strategic direction
- **Product Manager**: Define problem statement, success metrics, business case
- **Project Manager**: Coordinate stakeholder alignment, create project plan
- **Security Engineer**: Initial security assessment, compliance review
- **Customer Success**: Provide customer insights and feature requests

### Project Planning
- **Product Manager**: Prioritize features, write user stories, define acceptance criteria
- **Project Manager**: Create timeline, identify risks and dependencies, resource planning
- **Tech Lead/Developers**: Technical design, effort estimation
- **UX Designer**: Create wireframes and design system
- **QA**: Define testing strategy and acceptance criteria
- **Data Analyst**: Define instrumentation and success metrics

### Execution
- **Developers**: Implement features, write tests, code reviews
- **PM**: Track progress, manage blockers, coordinate across teams
- **QA**: Test features, validate acceptance criteria
- **UX Designer**: Design reviews, usability testing
- **Security Engineer**: Security code reviews, vulnerability assessments
- **Data Analyst**: Implement analytics, monitor metrics

### Release & Deployment
- **Release Manager**: Coordinate deployment, manage release process
- **Developers**: Deploy code, monitor systems, fix critical issues
- **QA**: Final validation, smoke tests
- **PM**: Stakeholder communication, go/no-go coordination
- **Security Engineer**: Final security sign-off
- **Customer Success**: Customer communication, support readiness

### Post-Release
- **All roles**: Participate in retrospective
- **PM**: Capture lessons learned, process improvements
- **Data Analyst**: Measure success metrics, report on outcomes
- **Customer Success**: Gather customer feedback
- **Product Manager**: Assess impact, plan next iteration

---

## Instructions for Use

1. **Customize for your project**: Add or remove roles/activities as needed
2. **Keep it updated**: Review and update as roles or responsibilities change
3. **Resolve ambiguity**: Ensure only one "A" (Accountable) per activity
4. **Communicate clearly**: Share with team and reference in onboarding
5. **Use in planning**: Reference during sprint planning and milestone reviews
6. **Review regularly**: Update during retrospectives or when friction occurs

---

## Common Pitfalls to Avoid

- ❌ Multiple "Accountable" for one task → Always have exactly one A
- ❌ Too many "Consulted" → Creates bottlenecks, be selective
- ❌ Forgetting "Informed" → Stakeholders surprised, communication gaps
- ❌ No "Responsible" → Work doesn't get done
- ❌ Setting and forgetting → Review and update as project evolves

---

**Notes**:
[Add project-specific notes or exceptions here]
