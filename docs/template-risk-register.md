# Risk Register Template

**Project**: [Project Name]  
**Last Updated**: [Date]  
**Owner**: [Project Manager Name]

## Active Risks

| ID | Description | Impact | Likelihood | Risk Score | Owner | Mitigation Plan | Target Date | Status |
|----|-------------|---------|-----------|------------|-------|-----------------|-------------|---------|
| RISK-001 | [Brief description of risk] | High | Medium | H/M | [Name] | [Actions to reduce/eliminate risk] | [YYYY-MM-DD] | Open |
| RISK-002 | [Example: Key engineer may leave team] | High | Low | H/L | PM | Cross-train team, document critical knowledge | 2026-03-15 | In Progress |
| RISK-003 | [Example: Third-party API may have downtime] | Medium | Medium | M/M | Tech Lead | Implement circuit breaker, cache responses | 2026-02-28 | Open |

## Risk Assessment Guide

### Impact Levels
- **High**: Threatens project success, >2 week delay, >$100K cost impact, or customer escalation
- **Medium**: Significant but manageable, 1-2 week delay, $25K-$100K cost impact
- **Low**: Minor impact, <1 week delay, <$25K cost impact, can be absorbed

### Likelihood Levels
- **High**: >60% probability, has occurred in similar projects
- **Medium**: 30-60% probability, possible but not certain
- **Low**: <30% probability, unlikely but worth tracking

### Risk Score Prioritization
- **H/H** (High Impact, High Likelihood): Immediate attention, executive visibility
- **H/M, H/L**: Active mitigation required
- **M/H, M/M**: Monitor closely, mitigation planned
- **M/L, L/H, L/M, L/L**: Monitor, address if escalates

## Risk Status Definitions
- **Open**: Risk identified, mitigation plan pending or in early stages
- **In Progress**: Mitigation actions underway
- **Mitigated**: Risk reduced to acceptable level
- **Closed**: Risk no longer applicable or fully resolved
- **Realized**: Risk has occurred, now an issue (move to issue tracker)

## Closed/Mitigated Risks

| ID | Description | Impact | Likelihood | Owner | Resolution | Date Closed |
|----|-------------|---------|-----------|-------|------------|-------------|
| RISK-XXX | [Past risk description] | Medium | High | [Name] | [How it was resolved] | [YYYY-MM-DD] |

## Risk Review Schedule
- **Weekly**: PM reviews all active risks, updates status
- **Sprint Planning**: Team reviews risks that may impact upcoming sprint
- **Monthly**: Executive review of High/High and High/Medium risks
- **Major Milestones**: Comprehensive risk assessment before key deliveries

## Instructions for Use
1. Assign unique ID to each risk (RISK-001, RISK-002, etc.)
2. Describe risk clearly in terms of "If [event], then [consequence]"
3. Assess impact and likelihood objectively
4. Assign owner who can drive mitigation (not just track it)
5. Define specific mitigation actions with dates
6. Review and update status at least weekly
7. Escalate High/High risks immediately
8. Archive closed risks for future reference
