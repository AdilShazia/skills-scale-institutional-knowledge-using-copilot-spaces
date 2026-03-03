# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Delivery Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations
- Collaborate with UX Designer on implementation feasibility
- Support DevOps Engineer on deployment readiness

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed
- Design review sessions with UX Designer

---

### Scrum Master

#### Role Summary
The Scrum Master facilitates agile processes, coaches team practices in iterative delivery, and removes execution roadblocks. They protect the team from distractions and ensure healthy team dynamics and process adherence.

#### Responsibilities
- Facilitate sprint ceremonies (standups, planning, reviews, retrospectives)
- Coach team members on agile practices and self-organization
- Identify and help remove blockers and impediments
- Track team health metrics and delivery cadence
- Act as a communication bridge among team members and external stakeholders
- Support the Project Manager in process enforcement
- Facilitate problem-solving when conflicts arise

#### Goals
- Enable the team to deliver at a sustainable pace
- Improve team velocity and predictability over time
- Foster psychological safety and continuous improvement
- Reduce context-switching and external distractions

#### Typical Communication
- Daily standups (facilitate and timekeeper role)
- Weekly retros and process improvement discussions
- One-on-ones with team members facing impediments
- Status summaries for Project Manager

#### Key Interactions
- **With Developers**: Removes blockers, facilitates technical discussions, coaches on sprint discipline
- **With Project Manager**: Provides input on team velocity, risks, and capacity for planning
- **With Product Manager**: Clarifies backlog priorities and acceptance criteria during planning

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog based on business impact
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Partner with UX Designer on user experience strategy
- Work with QA/Testing to define acceptance criteria
- Communicate feature impact and roadmap to stakeholders

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability
- Maintain alignment between customer needs and development capacity

#### Typical Communication
- Weekly alignment with Project Manager and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specifications
- Design collaboration sessions with UX Designer

#### Key Interactions
- **With UX Designer**: Aligns on user needs, validates design direction, ensures usability focus
- **With Developers**: Clarifies requirements, accepts completed work, answers product questions
- **With Project Manager**: Aligns on priorities, timeline, and success metrics

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently and maintain stakeholder alignment.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication
- Track progress against milestones and escalate risks
- Work with Scrum Master on team capacity and blockers
- Maintain the project's decision log and risk register

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders
- Ensure clear accountability and role clarity

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation
- Escalation and triage discussions

#### Key Interactions
- **With Scrum Master**: Receives team health insights, works together on capacity and scheduling
- **With Product Manager**: Aligns on priorities, timeline, and success criteria
- **With Developers**: Communicates milestones, coordinates dependencies, escalates blockers
- **With Stakeholders**: Provides regular status updates and manages expectations

---

## Supporting Delivery Roles

### UX Designer

#### Role Summary
The UX Designer advocates for users and ensures design quality and usability throughout the product lifecycle. They partner with product and engineering to deliver user-centric solutions.

#### Responsibilities
- Conduct user research and translate findings into insights
- Create wireframes, prototypes, and visual designs
- Define user experience standards and design system patterns
- Partner with Product Managers on feature requirements and user flows
- Collaborate with Developers on implementation feasibility and pixel-perfect delivery
- Validate design decisions through user testing and feedback
- Document design decisions and rationale for future reference

#### Goals
- Ensure products are intuitive, accessible, and delightful to use
- Reduce support costs through clear, usable interfaces
- Enable faster feature adoption through good design
- Maintain consistency across the product ecosystem

#### Typical Communication
- Design review sessions with Product Manager and Developers
- User research findings and recommendations
- Design specs and interaction documentation
- Feedback loops during development sprints

#### Key Interactions
- **With Product Manager**: Translates user needs and requirements into design direction
- **With Developers**: Reviews implementation for usability and design fidelity, answers design questions
- **With QA/Testing**: Helps define acceptance criteria for user experience aspects

---

### QA & Testing Lead

#### Role Summary
The QA/Testing Lead ensures product quality and validates that completed work meets acceptance criteria and quality standards. They act as a quality advocate throughout the development process.

#### Responsibilities
- Define quality standards and test strategies for features
- Create and maintain test plans and test cases
- Execute manual testing and coordinate automated testing
- Validate acceptance criteria before marking work as done
- Identify, document, and triage bugs and quality issues
- Collaborate with Developers on test coverage and testability
- Provide quality metrics and trend reporting
- Support production validation and release verification

#### Goals
- Ensure delivered work meets quality standards and acceptance criteria
- Reduce production defects and support escalations
- Enable confident, risk-reduced releases
- Improve product reliability and user satisfaction

#### Typical Communication
- Test plans and test case documentation
- Bug reports with clear reproduction steps
- Quality metrics and trend reports in status updates
- Acceptance validation checklist before release

#### Key Interactions
- **With Developers**: Clarifies acceptance criteria, reports quality issues, partners on testability
- **With Product Manager**: Validates feature completeness against acceptance criteria
- **With Project Manager**: Provides quality status and timeline impact of issues
- **With DevOps Engineer**: Validates deployment and smoke tests

---

### Business Analyst

#### Role Summary
The Business Analyst bridges the gap between business stakeholders and the delivery team. They gather requirements, validate business value, and ensure delivered work aligns with business objectives.

#### Responsibilities
- Conduct stakeholder interviews and requirements gathering
- Document business requirements and user stories
- Translate strategic business needs into actionable work items
- Validate that delivered solutions address the original business problem
- Identify business process changes and training needs
- Support change management and stakeholder communication
- Provide business context to the delivery team

#### Goals
- Ensure projects deliver measurable business value
- Reduce scope creep and misaligned requirements
- Improve stakeholder satisfaction and adoption
- Enable data-driven business decisions

#### Typical Communication
- Requirements documentation and user story creation
- Stakeholder interview summaries and findings
- Business value assessment for prioritization
- Post-release business impact analysis

#### Key Interactions
- **With Product Manager**: Ensures business requirements translate to product features
- **With Project Manager**: Helps clarify scope and business impact of decisions
- **With Stakeholders**: Gathers requirements and validates delivered value

---

### DevOps Engineer

#### Role Summary
The DevOps Engineer maintains infrastructure, CI/CD pipelines, and operational excellence. They enable continuous delivery and production reliability through automation and monitoring.

#### Responsibilities
- Build and maintain CI/CD pipelines for automated testing and deployment
- Manage infrastructure, environments, and configuration
- Implement monitoring, logging, and alerting for production systems
- Automate repetitive operational tasks
- Support developers with deployment and production troubleshooting
- Plan and execute releases with minimal downtime
- Document deployment procedures and runbooks
- Ensure security and compliance in deployment processes

#### Goals
- Enable fast, reliable, automated deployments
- Minimize production incidents and downtime
- Reduce manual operational work through automation
- Maintain high system availability and performance

#### Typical Communication
- Deployment procedures and release notes
- Infrastructure and deployment documentation
- Production metrics and incident reports
- Collaboration with developers on deployment readiness

#### Key Interactions
- **With Developers**: Supports deployment, troubleshoots production issues, provides infrastructure guidance
- **With QA/Testing**: Coordinates smoke testing and production validation
- **With Project Manager**: Provides deployment timeline and risk assessment
- **With Scrum Master**: Communicates operational blockers and constraints

---

## Executive & Stakeholder Roles

### Product Sponsor / Stakeholder

#### Role Summary
The Sponsor represents business interests and provides the authority, resources, and strategic direction for the project. They are accountable for business outcomes.

#### Responsibilities
- Approve project initiation and charter
- Provide required resources and budget
- Make strategic decisions and resolve escalations
- Receive and review status updates
- Validate business alignment and value
- Support change management and stakeholder engagement
- Remove organizational barriers to delivery

#### Goals
- Ensure project delivers expected business value
- Maintain strategic alignment with organizational goals
- Minimize disruption to ongoing operations
- Enable the team to focus on delivery

#### Typical Communication
- Monthly executive updates and milestone reviews
- Escalation decisions and approvals
- Go/no-go decision gates
- Post-project business impact review

#### Key Interactions
- **With Project Manager**: Receives regular updates, provides escalation decisions
- **With Product Manager**: Reviews roadmap and prioritization alignment
- **With Developers/Team**: Rare direct contact; primarily through Project Manager and Product Manager

---

### Technical Lead / Solutions Architect

#### Role Summary
The Technical Lead provides architectural guidance and technical strategy. They make key technical decisions and help Developers navigate complex technical challenges.

#### Responsibilities
- Define technical architecture and technology strategy
- Review and approve technical designs for major features
- Guide Developers on technical best practices
- Make technology selection decisions
- Help identify and mitigate technical risks
- Collaborate with DevOps Engineer on infrastructure needs
- Document technical decisions and rationale

#### Goals
- Ensure scalable, maintainable technical solutions
- Reduce technical debt and rework
- Enable faster development through clear architecture
- Support team learning and growth

#### Typical Communication
- Technical design reviews and documentation
- Architecture decision records (ADRs)
- Technical guidance and mentoring sessions
- Technology selection recommendations

#### Key Interactions
- **With Developers**: Provides architectural guidance and design review
- **With DevOps Engineer**: Aligns on infrastructure needs and scalability
- **With Product Manager**: Advises on technical feasibility and timeline impact
- **With Project Manager**: Communicates technical risks and mitigation

---

### Security Lead / Security Officer

#### Role Summary
The Security Lead ensures that security requirements are met throughout the project lifecycle. They act as the security advocate and incident responder.

#### Responsibilities
- Define security requirements and standards
- Review designs and code for security vulnerabilities
- Ensure compliance with security policies and standards
- Conduct security assessments and penetration testing
- Lead incident response and post-incident reviews
- Provide security training and guidance to the team
- Maintain security documentation and runbooks

#### Goals
- Ensure products are built with security by design
- Reduce security vulnerabilities and breaches
- Enable confident, secure releases
- Maintain compliance with regulations and standards

#### Typical Communication
- Security requirements and threat assessments
- Vulnerability reports and remediation plans
- Incident response coordination
- Security metrics and audit reports

#### Key Interactions
- **With Developers**: Reviews code and designs for security vulnerabilities
- **With DevOps Engineer**: Ensures secure deployment and monitoring
- **With Project Manager**: Escalates security risks and timeline impact
- **With Sponsor**: Reports on security posture and incident status

---

### Operations / Support Lead

#### Role Summary
The Operations/Support Lead manages post-release support and operational stability. They represent the voice of operational teams and support the transition from development to production.

#### Responsibilities
- Develop support plans and runbooks for new features
- Train support and operations teams on new releases
- Triage and manage post-release issues
- Coordinate with Developers on hotfixes and escalations
- Monitor operational metrics and system health
- Manage customer escalations and satisfaction
- Provide feedback on operational improvements

#### Goals
- Minimize post-release support burden
- Ensure fast resolution of production issues
- Improve customer satisfaction and retention
- Reduce operational overhead

#### Typical Communication
- Support runbooks and playbooks
- Post-release support plans
- Operational metrics and incident reports
- Feedback from support and customers

#### Key Interactions
- **With Developers**: Escalates issues, provides operational feedback
- **With DevOps Engineer**: Coordinates on infrastructure and monitoring
- **With Project Manager**: Reports on operational readiness and post-release issues
- **With Product Manager**: Provides customer feedback and usage insights

---

## Role Interaction Matrix

| Interaction | Primary | Secondary | Frequency | Key Handoff |
|---|---|---|---|---|
| **Planning Phase** | PM ↔ PdM | Dev, Scrum Master | Weekly | Backlog, estimates, Definition of Done |
| | UX Designer ↔ PdM | Dev | 2x/week | User flows, design specs |
| | BA → Stakeholder | PM | Weekly | Requirements, business alignment |
| **Development Phase** | Dev ↔ Scrum Master | PM, QA | Daily | Blockers, progress, impediments |
| | Dev ↔ UX Designer | PM | 3x/week | Implementation feasibility, design review |
| | Dev ↔ Tech Lead | Scrum Master | 2x/week | Architecture, technical guidance |
| | QA → Dev | PM | Continuous | Acceptance criteria, bug reports |
| **Release Phase** | DevOps ↔ Dev | QA, PM | 2x/week | Deployment readiness, release timing |
| | Security Lead → Dev | DevOps | As needed | Vulnerability fixes, security validation |
| | PM → Sponsor | PdM | Weekly | Status, risks, decisions |
| **Post-Release** | Support Lead → Dev | DevOps, PM | As needed | Hotfixes, operational feedback |
| | PdM → Sponsor | PM | Monthly | Business impact, next steps |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction matrix when planning cross-functional work and identifying communication needs.

---

## Onboarding Checklist by Role

When adding a new team member to a project, ensure they understand:

- [ ] Their role summary and key responsibilities
- [ ] Who they interact with and how often
- [ ] Where to find project documentation and status
- [ ] Escalation paths and decision criteria
- [ ] Current project phase and upcoming milestones
- [ ] Key success metrics and acceptance criteria
- [ ] How feedback and improvements are captured