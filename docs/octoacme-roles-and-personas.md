# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Stakeholder Communication Lead

### Role Summary
Stakeholder Communication Leads manage stakeholder expectations and ensure consistent, transparent communication across the project. They serve as a central hub for coordinating information flow between project teams and external stakeholders.

### Responsibilities
- Manage stakeholder expectations and engagement
- Coordinate cross-functional communication channels
- Maintain and update stakeholder registry
- Identify and escalate communication blockers
- Develop and execute communication plans for key milestones
- Gather and synthesize feedback from stakeholders

### Goals
- Maintain stakeholder alignment and satisfaction
- Reduce miscommunication and rework
- Enable timely escalation and resolution of issues
- Improve project transparency and trust

### Interactions with Other Roles
- **Project Manager**: Collaborate on status updates, timeline changes, and risk communications
- **Quality Assurance Owner**: Report on quality metrics and test results to stakeholders
- **Executive Sponsor**: Provide executive summaries and highlight risks requiring escalation
- **Developers**: Communicate progress, demos, and technical constraints to stakeholders
- **Product Managers**: Align on feature announcements and capability updates

### Decision-Making Authority
- Full authority over communication frequency and channel selection
- Recommends communication strategies for complex issues
- Escalates communication risks to Project Manager

### Typical Communication
- Stakeholder meeting facilitation and notes
- Communication plan documentation
- Status reports and executive briefings
- Stakeholder feedback summaries

---

## Quality Assurance Owner

### Role Summary
Quality Assurance Owners define quality standards, oversee testing strategies, and ensure all deliverables meet established quality gates. They are the final authority on release readiness from a quality perspective.

### Responsibilities
- Define quality standards and acceptance criteria
- Develop and oversee testing strategies (unit, integration, system, UAT)
- Manage defect triage, prioritization, and resolution tracking
- Ensure compliance with quality gates before release
- Collaborate on automation frameworks and test coverage goals
- Provide quality metrics and trend reporting
- Participate in retrospectives to identify quality improvements

### Goals
- Deliver high-quality, reliable software
- Reduce defects in production
- Minimize rework and post-release issues
- Build confidence in release readiness

### Interactions with Other Roles
- **Developers**: Collaborate on test strategies, automation frameworks, and defect resolution
- **Project Manager**: Provide quality status updates and risk assessments
- **Stakeholder Communication Lead**: Report quality metrics and release readiness status
- **Release Manager**: Make final go/no-go decisions based on quality gate compliance
- **Product Managers**: Define quality acceptance criteria alongside functional requirements

### Decision-Making Authority
- Full authority to block releases that do not meet quality standards
- Authority to request additional testing before sign-off
- Recommends quality process improvements

### Typical Communication
- Quality dashboards and metrics reports
- Test strategy and plan documentation
- Defect logs and resolution tracking
- Release readiness reports

---

## Change Management Lead

### Role Summary
Change Management Leads assess the impact of changes, coordinate change communication, and track adoption and resistance. They minimize disruption by ensuring changes are well-planned, communicated, and supported.

### Responsibilities
- Assess impact of proposed changes on teams, processes, and systems
- Coordinate change communication and messaging
- Develop change adoption plans and training strategies
- Identify resistance and develop mitigation approaches
- Track change implementation progress and outcomes
- Maintain change log and history
- Facilitate change retrospectives and lessons learned

### Goals
- Minimize disruption from organizational and process changes
- Accelerate adoption and reduce resistance
- Capture and share lessons learned
- Improve change execution effectiveness

### Interactions with Other Roles
- **Project Manager**: Partner on timeline impacts and resource planning for change initiatives
- **Stakeholder Communication Lead**: Coordinate change messaging and stakeholder preparation
- **Team Leads**: Align on resource requirements and team-level change impacts
- **Product Managers**: Understand feature/product changes and implications for users
- **Developers**: Communicate technical changes and support implementation

### Decision-Making Authority
- Reviews and approves change impact assessments
- Full authority to manage the change log and prioritization
- Recommends change sequencing and timing decisions

### Typical Communication
- Change impact assessment documents
- Change communication plans and messaging
- Change adoption tracking and dashboards
- Stakeholder readiness reports
- Lessons learned documentation

---

## RACI Matrix for Key Activities

| Activity | Developers | Product Managers | Project Managers | Stakeholder Communication Lead | Quality Assurance Owner | Change Management Lead |
|----------|-----------|-----------------|-----------------|-------------------------------|------------------------|----------------------|
| Define Requirements | C | R/A | C | I | C | I |
| Develop Features | R/A | C | I | I | C | I |
| Test & QA | C | I | C | R/A | I | I |
| Communicate Status | C | C | A | R/A | C | C |
| Manage Risks | C | C | R/A | C | C | C |
| Release Planning | C | I | R/A | C | A | C |
| Change Impact Assessment | C | C | I | C | C | R/A |
| Stakeholder Engagement | I | C | C | R/A | I | C |
| Quality Gates | A | I | C | C | R/A | I |

**Legend:** R = Responsible, A = Accountable, C = Consulted, I = Informed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the RACI matrix to understand decision-making paths and collaboration points across roles.
