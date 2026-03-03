# OctoAcme Role Handoffs & Responsibilities

## Purpose
Define clear handoff points between roles throughout the project lifecycle to reduce ambiguity and improve accountability.

## Project Initiation Phase

### Sponsor → Project Manager
**What**: Project charter, business case, budget, resource approval
**How**: Kickoff meeting, documented approval email
**Success Criteria**:
- Charter clearly states problem, objectives, and success metrics
- Budget and resources approved in writing
- Sponsor expectations documented

### Project Manager → Product Manager
**What**: Project context, timeline constraints, stakeholder list
**How**: Initiation meeting, shared documentation in project repo
**Success Criteria**:
- PdM understands business objectives and constraints
- Stakeholder list is complete with communication preferences
- Timeline and milestone dates are realistic and agreed

---

## Planning Phase

### Product Manager → Developers & UX Designer
**What**: User stories, acceptance criteria, design direction
**How**: Backlog refinement sessions, design reviews, documentation
**Success Criteria**:
- Each story has clear acceptance criteria
- Developers and UX Designer have agreed on approach
- Definition of Done is documented and agreed

### UX Designer → Developers
**What**: Design specs, user flows, accessibility requirements
**How**: Design review meeting, documented design system, Figma/design tool access
**Success Criteria**:
- Design is feasible for development timeline
- Developers understand interaction model and edge cases
- Accessibility requirements are clear

### Developers → Scrum Master & Project Manager
**What**: Effort estimates, risks, dependencies, capacity
**How**: Planning meeting, risk register, project board setup
**Success Criteria**:
- Sprint/iteration backlog reflects team capacity
- Known dependencies and risks are documented
- Team is aligned on sprint goals

---

## Development Phase

### Developers → Code Review Process
**What**: Code changes with PR description, linked issue, test evidence
**How**: Pull request with reviewers assigned
**Success Criteria**:
- PR includes link to acceptance criteria
- Tests pass in CI
- At least one approval before merge

### Developers → QA/Testing
**What**: Completed features ready for quality validation
**How**: Mark as "Ready for QA" on project board, notify QA in standup
**Success Criteria**:
- Feature meets acceptance criteria on staging environment
- Manual testing checklist provided
- Known limitations documented

### Scrum Master ← Developers (Blockers)
**What**: Blockers, impediments, risks discovered during sprint
**How**: Raised in daily standup, Scrum Master follows up
**Success Criteria**:
- Blocker is timely addressed or escalated
- Root cause is identified
- Mitigation plan is in place

---

## Quality Assurance Phase

### QA/Testing → Product Manager
**What**: Quality validation complete, acceptance criteria met or gaps identified
**How**: Status update in project board, shared bug report
**Success Criteria**:
- Acceptance criteria verified as met
- Known issues are documented with severity
- Feature is signed off for release or rework identified

### QA/Testing → Developers (Issues)
**What**: Bug reports with reproduction steps, screenshots, severity
**How**: GitHub issue or project board card, assigned to developer
**Success Criteria**:
- Bug is clearly reproducible
- Developer can prioritize based on severity
- Root cause investigation leads to fix

---

## Release Phase

### DevOps Engineer → Developers
**What**: Deployment readiness checklist, release timeline
**How**: Release meeting, deployment runbook shared
**Success Criteria**:
- All acceptance criteria are met
- Smoke tests are prepared
- Rollback plan is documented

### Project Manager → Stakeholders
**What**: Release announcement, deployment window, support contact
**How**: Email, shared release notes, Slack/communication channel
**Success Criteria**:
- Stakeholders know when feature will be live
- Known limitations are communicated
- Support contact and incident process is clear

### DevOps Engineer → Operations/Support
**What**: Deployment complete, system healthy, monitoring active
**How**: Deployment confirmation, handoff to support team
**Success Criteria**:
- Production metrics are green (errors, latency, availability)
- Support team has runbook and escalation path
- Monitoring and alerting are active

---

## Post-Release Phase

### Operations/Support → Product Manager
**What**: Usage metrics, customer feedback, support volume
**How**: Weekly report, shared dashboard, feedback summary
**Success Criteria**:
- PdM understands adoption and impact
- Critical issues are identified for hotfix
- User feedback informs roadmap priorities

### Project Manager → Sponsor
**What**: Project completion, business impact assessment, lessons learned
**How**: Final status meeting, retrospective summary, business metrics review
**Success Criteria**:
- Project is closed with documented results
- Success metrics are assessed against baselines
- Action items from retrospective are prioritized

---

## Escalation Path

### Level 1: Team Triage
**Who**: Scrum Master + Developers
**When**: Daily standup, unplanned blocker
**How**: Raise in standup, discuss mitigation, escalate if unresolved in 24 hours

### Level 2: Project Management
**Who**: Project Manager + Product Manager
**When**: Blocker impacts timeline or scope
**How**: Risk register update, stakeholder communication, mitigation plan

### Level 3: Executive Decision
**Who**: Sponsor + Product Lead
**When**: Business impact or strategic alignment at risk
**How**: Executive escalation meeting, approval for scope/timeline change

### Security/Incident Path
**Who**: Security Lead, DevOps Engineer, Incident Commander
**When**: Security vulnerability or production incident discovered
**How**: Follow security incident runbook, notify on-call, execute incident response