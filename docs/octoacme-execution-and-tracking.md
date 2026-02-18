# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation

### Escalation Levels and Timelines

**Level 1: Team-Level (Response: Same day)**
- **Trigger**: Blocker identified that impacts current sprint work
- **Action**: Discuss in daily standup or async in team channel
- **Owner**: Developer or team member who identified the blocker
- **Involves**: Development team, PM
- **Resolution Target**: Within 4 hours during business hours

**Level 2: Cross-Team/Management (Response: Within 24 hours)**
- **Trigger**: Blocker not resolved at team level OR affects multiple teams
- **Action**: PM escalates to Product Lead and relevant team leads
- **Owner**: Project Manager
- **Involves**: Product Lead, Engineering Manager, dependent team leads
- **Resolution Target**: Within 1-2 business days
- **Communication**: Status update to stakeholders if resolution extends beyond 24 hours

**Level 3: Executive/Sponsor (Response: Within 4 hours)**
- **Trigger**: Business-impacting issue OR risk to project timeline/scope
- **Action**: Formal escalation to Stakeholder Advisor and executive team
- **Owner**: Product Lead or Project Manager
- **Involves**: Stakeholder Advisor, VP Engineering, VP Product
- **Resolution Target**: Decision/direction within 4 hours
- **Communication**: Executive briefing document with impact analysis and options

### Escalation Decision Tree

```
Is the blocker resolved in < 4 hours by the team?
├─ YES → Document in standup notes, no escalation needed
└─ NO → Does it block sprint goals?
    ├─ NO → Add to backlog, address in planning
    └─ YES → Escalate to Level 2
        → Is there a business/timeline impact?
            ├─ NO → Continue Level 2 resolution
            └─ YES → Escalate to Level 3
```

### Escalation Checklist
- [ ] Blocker clearly documented with impact assessment
- [ ] Attempted team-level resolution documented
- [ ] Relevant context and options prepared
- [ ] Timeline impact quantified (days/sprint points)
- [ ] Stakeholder notification list identified
- [ ] Escalation documented in risk register

## Execution Checklist

### Project Setup
- [ ] Branching and PR conventions documented in repo CONTRIBUTING.md
- [ ] CI/CD pipeline configured for tests, lint, and security scans
- [ ] Project board created with standard columns
- [ ] Team access and permissions configured
- [ ] Repository branch protection rules enabled
- [ ] Code review requirements documented (minimum reviewers, required checks)

### Ongoing Execution
- [ ] Daily standups scheduled and facilitated
- [ ] Regular demos scheduled (sprint end or bi-weekly)
- [ ] Risk register reviewed and updated weekly
- [ ] Velocity and burndown tracked and visible
- [ ] Success metrics monitored via dashboard
- [ ] Dependencies tracked and communicated to dependent teams
- [ ] Technical debt log maintained and reviewed monthly
- [ ] Security scans reviewed weekly

### Quality Gates
- [ ] Unit test coverage meets minimum threshold (e.g., 80%)
- [ ] Integration tests pass in CI
- [ ] End-to-end smoke tests pass for critical flows
- [ ] Security scans show no high/critical issues (or approved exceptions)
- [ ] Code review completed by at least one team member
- [ ] Product Owner/PM sign-off on acceptance criteria
- [ ] Documentation updated for new features

### Knowledge Centralization
- [ ] Project README maintained with up-to-date setup instructions
- [ ] Architecture decision records (ADRs) documented for significant decisions
- [ ] Runbooks created for operational procedures
- [ ] Troubleshooting guides updated based on common issues
- [ ] Team knowledge base (wiki/docs) kept current
- [ ] Meeting notes and decisions documented in single source of truth
- [ ] Critical system diagrams maintained and version-controlled

## Onboarding New Team Members

### Week 1: Orientation
- [ ] Access to repositories, tools, and communication channels granted
- [ ] Review project README and documentation
- [ ] Attend team standups and observe workflows
- [ ] Pair with team member on a small task
- [ ] Complete security and compliance training
- [ ] Review architecture diagrams and system overview

### Week 2-3: Ramp-Up
- [ ] Complete first feature or bug fix (with guidance)
- [ ] Participate in code reviews (reviewing others' code)
- [ ] Attend sprint planning and retrospectives
- [ ] Review past incident reports and learnings
- [ ] Understand escalation paths and communication norms

### Week 4+: Full Integration
- [ ] Pick up work independently from backlog
- [ ] Lead a feature or initiative
- [ ] Present at demo or team meeting
- [ ] Contribute to documentation or process improvements
- [ ] Mentor newer team members when ready

### Onboarding Buddy Checklist (for assigned mentors)
- [ ] Schedule daily check-ins for first week
- [ ] Share team norms, tips, and unwritten rules
- [ ] Answer questions and provide context
- [ ] Review first PR in detail
- [ ] Introduce to key stakeholders
- [ ] Check in at 30, 60, 90 day marks
