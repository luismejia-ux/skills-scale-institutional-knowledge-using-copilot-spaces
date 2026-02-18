# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register

### Risk Assessment Checklist
Before adding a risk to the register:
- [ ] Risk clearly described with specific scenario
- [ ] Impact assessed (High/Medium/Low) with quantifiable criteria
- [ ] Likelihood estimated based on evidence or historical data
- [ ] Owner assigned who can drive mitigation
- [ ] Mitigation plan defined with specific actions
- [ ] Target resolution date set
- [ ] Related risks identified and linked

### Risk Impact Criteria
- **High**: Threatens project success, >2 week delay, >$100K cost impact, or customer escalation
- **Medium**: Significant impact but manageable, 1-2 week delay, $25K-$100K cost impact
- **Low**: Minor impact, <1 week delay, <$25K cost impact, can be absorbed

### Risk Likelihood Criteria
- **High**: >60% probability, has happened before in similar projects
- **Medium**: 30-60% probability, possible but not certain
- **Low**: <30% probability, unlikely but worth tracking

Maintain a simple table with:
- ID (e.g., RISK-001)
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Risk Score (Impact x Likelihood)
- Owner
- Mitigation plan
- Target Date
- Status (Open/In Progress/Mitigated/Closed)

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication

### Identify Stakeholders and Communication Needs

Create a stakeholder map with:
- **Name/Role**: Who they are
- **Interest Level**: High/Medium/Low
- **Influence Level**: High/Medium/Low
- **Communication Frequency**: Daily/Weekly/Monthly/Milestone-based
- **Preferred Channel**: Email/Slack/Meeting/Dashboard
- **Key Information Needs**: What they care about most

### Stakeholder Communication Matrix

| Stakeholder Type | Frequency | Format | Content Focus |
|-----------------|-----------|---------|---------------|
| **Executive Team** | Monthly | Executive briefing | Business impact, ROI, strategic alignment |
| **Product Leadership** | Weekly | Status report | Progress, metrics, decisions needed |
| **Engineering Teams** | Daily/Weekly | Standups, demo | Technical details, blockers, dependencies |
| **Customer Success** | Weekly | Sync meeting | Customer impact, feature readiness, support needs |
| **Sales** | Milestone-based | Release notes | New capabilities, customer benefits, launch timing |
| **Support** | Before release | Training session | New features, known issues, troubleshooting |
| **Security/Compliance** | As needed | Security review | Risk assessment, compliance status, vulnerabilities |

### Communication Best Practices

1. **Single Source of Truth**: Maintain project status in one location (project README or dashboard)
2. **Consistent Format**: Use templates for regular communications
3. **Right Level of Detail**: Tailor depth to audience (executive summary vs. technical details)
4. **Proactive Updates**: Don't wait for stakeholders to ask; push updates regularly
5. **Highlight Changes**: Call out what changed since last update
6. **Action-Oriented**: Clear on who needs to do what by when
7. **Accessible**: Ensure communications are inclusive and accessible to all stakeholders

### Cross-Functional Communication Guidelines

**For Effective Cross-Team Collaboration**:
- Schedule regular sync meetings (weekly or bi-weekly)
- Use shared project boards visible to all teams
- Document dependencies and owners clearly
- Escalate blockers early and explicitly
- Celebrate wins and share learnings across teams
- Maintain a RACI matrix (Responsible, Accountable, Consulted, Informed) for major decisions

**Communication Channels by Purpose**:
- **Urgent/Blocking**: Slack mention or direct call
- **Status Updates**: Email or project board
- **Decisions**: Documented in meeting notes or decision log
- **Technical Discussion**: PR comments or design doc
- **Team Coordination**: Standups or team channel
- **Stakeholder Updates**: Email or presentation

## Communication Templates

### Weekly Status Template
**Project**: [Project Name]  
**Week Ending**: [Date]  
**Status**: 🟢 On Track | 🟡 At Risk | 🔴 Blocked

**Progress this week**:
- [Key accomplishment 1]
- [Key accomplishment 2]
- [Metrics update if applicable]

**Next steps**:
- [Planned work item 1]
- [Planned work item 2]

**Risks & blockers**:
- 🔴 **[Blocker Title]**: [Brief description] - Owner: [Name], ETA: [Date]
- 🟡 **[Risk Title]**: [Brief description] - Mitigation: [Actions]

**Asks / decisions needed**:
- [Decision or help needed] - Needed by: [Date] - From: [Role/Person]

**Metrics** (if applicable):
- Velocity: [X story points] (Target: [Y])
- Burndown: [X%] complete
- Success metric: [Current value vs. target]

---

### Incident Communication Template

**Initial Communication (within 1 hour of detection)**

**Subject**: [INCIDENT] [Severity] - [Brief Description]

**Status**: 🔴 Investigating | 🟡 Identified | 🟢 Resolved

**Summary**:
[Brief description of the incident and customer impact]

**Impact**:
- Affected users/systems: [Description]
- Started at: [Timestamp]
- Current status: [What's working, what's not]

**Actions being taken**:
- [Action 1] - Owner: [Name]
- [Action 2] - Owner: [Name]

**Expected timeline**:
- Next update: [Time]
- Estimated resolution: [Time or "investigating"]

**Incident Commander**: [Name]  
**Communication Lead**: [Name]

---

**Update Communication (every 30-60 minutes)**

**Subject**: [INCIDENT UPDATE] [Severity] - [Brief Description]

**Status**: [Update on progress]

**New information**:
[What we've learned since last update]

**Actions completed**:
- [Completed action 1]
- [Completed action 2]

**Next steps**:
- [Planned action 1]
- [Planned action 2]

**Next update**: [Time]

---

**Resolution Communication**

**Subject**: [RESOLVED] [Brief Description]

**Summary**:
[Brief description of incident and resolution]

**Timeline**:
- Incident start: [Time]
- Incident resolved: [Time]
- Total duration: [Duration]

**Root cause** (preliminary):
[Brief explanation - detailed RCA to follow]

**Resolution**:
[What was done to resolve]

**Next steps**:
- Post-incident review scheduled: [Date/Time]
- Action items: [Key follow-ups]

---

### Sprint Demo Template

**Sprint**: [Sprint Number/Name]  
**Date**: [Date]  
**Goal**: [Sprint goal]

**Completed**:
- [Feature 1] - Demo: [Person] - [Brief description]
- [Feature 2] - Demo: [Person] - [Brief description]

**In Progress** (carrying over):
- [Item 1] - [Reason] - Expected completion: [Sprint]

**Metrics**:
- Velocity: [Completed points] / [Committed points]
- Success metric movement: [Change]

**Learnings**:
- [Key learning 1]
- [Key learning 2]

**Next Sprint Focus**:
- [Priority 1]
- [Priority 2]

---

### Cross-Functional Sync Template

**Meeting**: [Purpose of sync]  
**Date**: [Date]  
**Attendees**: [Roles present]

**Updates by Team**:
- **Engineering**: [Progress, blockers, upcoming work]
- **Product**: [Priorities, customer feedback, roadmap updates]
- **Design**: [Design status, user research insights]
- **Data**: [Metrics, insights, data requests]
- **Customer Success**: [Customer feedback, escalations]

**Dependencies**:
- [Team A] needs [X] from [Team B] by [Date]

**Decisions Made**:
- [Decision 1] - Owner: [Name]
- [Decision 2] - Owner: [Name]

**Action Items**:
- [ ] [Action] - Owner: [Name] - Due: [Date]

**Next Meeting**: [Date/Time]

## Escalation Paths

### Standard Escalation Flow
1. **Team-level** → PM → Product Lead → Stakeholder Advisor
2. **Technical Issues** → Developer → Tech Lead → Engineering Manager → VP Engineering
3. **Product Decisions** → Product Manager → Product Lead → VP Product → Stakeholder Advisor
4. **Security Incidents** → Security Engineer → Security Manager → CISO → Executive Team
5. **Customer Issues** → Customer Success → CS Manager → VP Customer Success → Executive Team

### Escalation Timelines and Criteria

| Escalation Level | Response Time | Decision Time | Criteria |
|-----------------|---------------|---------------|----------|
| Team-level | 4 hours | Same day | Blockers affecting current work |
| Cross-team/Management | 24 hours | 1-2 days | Multi-team dependencies, scope questions |
| Executive/Sponsor | 4 hours | Same day | Budget impact >$50K, timeline slip >2 weeks, customer escalation |
| Security Incident | 1 hour | 4 hours | Security breach, data leak, compliance violation |

### Escalation Best Practices
- Document the issue clearly before escalating (what, impact, options)
- Attempt resolution at current level before escalating
- Provide specific ask or decision needed
- Include timeline urgency and business impact
- Follow up with outcome and actions taken
- Update stakeholders at each level

### Security Incident Escalation
- **Priority 1 (Critical)**: Active breach, data leak, system down
  - Immediate notification to Security on-call
  - CISO notified within 1 hour
  - Incident response team activated
  - Hourly updates until resolved

- **Priority 2 (High)**: Vulnerability discovered, potential breach
  - Security team notified within 4 hours
  - Risk assessment within 24 hours
  - Mitigation plan within 48 hours

- **Priority 3 (Medium)**: Non-critical vulnerability
  - Security team notified within 1 business day
  - Scheduled for upcoming sprint
  - Standard review process
