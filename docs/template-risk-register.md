# Risk Register Template

## Purpose
Track and manage project risks throughout the project lifecycle. This register should be reviewed weekly and updated as risks evolve.

## How to Use
1. Copy this template to your project repository
2. Add identified risks as they are discovered
3. Review and update during weekly project sync meetings
4. Archive or close risks as they are resolved or no longer applicable

---

## Risk Register

| Risk ID | Description | Impact | Likelihood | Risk Level | Owner | Mitigation Plan | Status | Last Updated |
|---------|-------------|--------|------------|------------|-------|-----------------|--------|--------------|
| R-001 | Example: Third-party API dependency may become unavailable | High | Medium | High | Dev Lead | Implement circuit breaker pattern and fallback mechanism | Active | 2024-01-15 |
| R-002 | | | | | | | | |

---

## Risk Assessment Guidelines

### Impact Levels
- **High**: Significant impact on timeline, budget, or quality; may cause project failure
- **Medium**: Moderate impact; may cause delays or require additional resources
- **Low**: Minor impact; can be absorbed within normal project buffers

### Likelihood Levels
- **High**: Very likely to occur (>60% probability)
- **Medium**: May occur (30-60% probability)
- **Low**: Unlikely to occur (<30% probability)

### Risk Level Matrix
Risk Level = Impact × Likelihood

| Impact / Likelihood | Low | Medium | High |
|---------------------|-----|--------|------|
| **High** | Medium | High | Critical |
| **Medium** | Low | Medium | High |
| **Low** | Low | Low | Medium |

### Status Values
- **Active**: Risk is currently present and being monitored
- **Mitigated**: Mitigation actions completed; monitoring for effectiveness
- **Closed**: Risk no longer applicable or has been fully resolved
- **Realized**: Risk has occurred; now tracking as an issue

---

## Risk Review Schedule
- **Weekly**: Review all active and mitigated risks
- **Monthly**: Trend analysis and risk reporting to stakeholders
- **Ad-hoc**: When new risks are identified or existing risks change significantly

## Escalation Criteria
Escalate to project sponsors when:
- Risk level is Critical
- Mitigation requires additional budget or resources
- Risk may impact committed deliverables or timelines
