# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status
- Security/Compliance reviewed (yes/no) (Security/Compliance Officer)

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based) (PM, Release Manager)
- Use a single source of truth (project README or release doc) for status
- Customer-facing communications coordinated through Customer Success Manager
- Security/compliance updates communicated by Security/Compliance Officer
- Quality metrics shared by QA Lead

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security/Compliance Officer
- For quality concerns: QA Lead -> PM -> Product Lead
- For release issues: Release Manager -> PM -> Product Lead
- For customer escalations: Customer Success Manager -> Product Manager -> Product Lead
