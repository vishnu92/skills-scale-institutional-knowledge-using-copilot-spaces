# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Interactions
- Works closely with **Technical Lead/Architect** on technical feasibility and design
- Collaborates with **QA Lead** on acceptance criteria and test coverage
- Coordinates with **DevOps/Infrastructure Owner** on deployment and environment needs

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics
- Represent customer voice in feature discussions

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Interactions
- Partners with **Design/UX Lead** to validate user experience
- Coordinates with **Support/Customer Success Lead** on customer feedback integration
- Aligns with **Sponsor/Executive Stakeholder** on business priorities
- Reviews security and compliance considerations with **Security/Compliance Officer**

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Interactions
- Escalates risks and blockers to **Sponsor/Executive Stakeholder**
- Ensures DevOps/Infrastructure Owner input on deployment timelines
- Coordinates with all functional leads for status and risk updates
- Facilitates cross-team dependency management

---

## Specialized Roles

### Technical Lead / Architect

#### Role Summary
Technical Leads own technical strategy, system design decisions, and architectural direction. They guide development teams on best practices, technical standards, and long-term system health.

#### Responsibilities
- Define system architecture and technical strategy for projects
- Lead technical design reviews and provide architectural guidance
- Identify technical risks, scalability concerns, and performance bottlenecks
- Mentor developers on best practices and coding standards
- Evaluate new technologies and tools
- Ensure code quality, maintainability, and adherence to standards
- Participate in release readiness reviews

#### Goals
- Deliver technically sound, scalable, and maintainable solutions
- Reduce technical debt and improve system reliability
- Foster a culture of continuous technical improvement
- Enable team growth through mentorship and guidance

#### Typical Communication
- Technical design review meetings
- Architecture decision records (ADRs)
- Code review comments and mentoring sessions
- Technical feasibility assessments in planning meetings

#### Interactions
- Guides **Developers** on technical direction and best practices
- Collaborates with **Product Manager** on feasibility and trade-offs
- Partners with **DevOps/Infrastructure Owner** on scalability and deployment architecture
- Reviews **QA Lead** test strategy for technical comprehensiveness
- Consults with **Security/Compliance Officer** on technical security controls

---

### QA Lead / Quality Assurance

#### Role Summary
QA Leads define quality standards, test strategies, and acceptance criteria validation. They ensure that deliverables meet quality gates before release.

#### Responsibilities
- Define test strategy and quality standards for projects
- Collaborate with Product and Development on acceptance criteria
- Coordinate testing activities (unit, integration, end-to-end, regression)
- Triage and track bugs and quality issues
- Ensure Definition of Done includes quality gates
- Manage test automation roadmap and infrastructure
- Participate in release readiness reviews
- Conduct post-release verification and regression testing

#### Goals
- Ensure high-quality, reliable deliverables
- Reduce defect escape rates to production
- Enable fast, confident releases
- Continuously improve test coverage and automation

#### Typical Communication
- Test planning and strategy documents
- Weekly QA status and risk reports
- Bug triage meetings and acceptance criteria reviews
- Release readiness checklists

#### Interactions
- Works with **Developers** to establish and validate acceptance criteria
- Collaborates with **Product Manager** on user experience validation
- Partners with **Technical Lead** on test strategy comprehensiveness
- Coordinates with **Support/Customer Success Lead** on critical user paths
- Supports **DevOps/Infrastructure Owner** with test environment needs

---

### Design / UX Lead

#### Role Summary
Design/UX Leads drive user experience and usability standards. They validate that features are discoverable, accessible, and delightful for users.

#### Responsibilities
- Define user experience strategy and design standards
- Conduct user research and validate design solutions
- Review features for usability and accessibility compliance
- Establish design system, component library, and design patterns
- Collaborate with Product on feature definition and user workflows
- Review acceptance criteria for user-facing work
- Ensure brand consistency and design coherence

#### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and support burden
- Establish design consistency and patterns across products
- Advocate for users in feature prioritization

#### Typical Communication
- Design documents and wireframes/mockups
- User research findings and usability reports
- Design system documentation and component specs
- Design critique and review sessions

#### Interactions
- Partners with **Product Manager** on feature definition and user workflows
- Collaborates with **Developers** on design implementation and component libraries
- Coordinates with **QA Lead** to validate user experience in testing
- Consults with **Support/Customer Success Lead** on user pain points

---

### Security / Compliance Officer

#### Role Summary
Security/Compliance Officers ensure that projects adhere to security and regulatory requirements. They identify risks and enforce security best practices across the organization.

#### Responsibilities
- Review features for security and compliance risks
- Define security requirements and standards
- Conduct security assessments and penetration testing coordination
- Triage and track security incidents
- Ensure compliance with regulatory and legal requirements
- Maintain security incident response and escalation procedures
- Participate in pre-release security reviews
- Provide security training and guidance

#### Goals
- Prevent security breaches and data loss
- Maintain compliance with regulations and standards
- Build security awareness across teams
- Enable secure, compliant releases

#### Typical Communication
- Security risk assessments and compliance reviews
- Security incident reports and escalations
- Pre-release security checklists
- Threat modeling and architectural security reviews

#### Interactions
- Reviews features with **Product Manager** early in planning
- Consults with **Technical Lead/Architect** on security controls and architecture
- Coordinates with **Developers** on secure coding practices
- Participates in **Release and Deployment** security gate
- Escalates critical security issues to **Sponsor/Executive Stakeholder**

---

### DevOps / Infrastructure Owner

#### Role Summary
DevOps/Infrastructure Owners manage deployment pipelines, infrastructure, and operational readiness. They ensure systems are reliable, scalable, and observable.

#### Responsibilities
- Design and maintain CI/CD pipelines and deployment automation
- Manage cloud/on-premises infrastructure and environments
- Ensure application scalability, reliability, and disaster recovery
- Implement monitoring, observability, and alerting
- Support incident response and troubleshooting
- Participate in capacity planning and performance optimization
- Advise on operational risk and reliability engineering
- Ensure infrastructure security and compliance

#### Goals
- Enable fast, reliable, repeatable deployments
- Minimize downtime and maximize system reliability
- Reduce operational overhead through automation
- Provide operational insights and visibility

#### Typical Communication
- Infrastructure and deployment documentation
- Release readiness and deployment execution
- Incident response and post-incident reviews
- Operational metrics and dashboards
- Capacity planning and infrastructure roadmap

#### Interactions
- Partners with **Developers** on deployment and environment needs
- Works with **Technical Lead** on scalability and architectural concerns
- Collaborates with **QA Lead** on test environment infrastructure
- Supports **Release and Deployment** readiness and execution
- Escalates operational risks to **Project Manager** and **Sponsor**

---

### Sponsor / Executive Stakeholder

#### Role Summary
Sponsors represent business priorities, strategic alignment, and executive accountability. They provide governance, resource allocation, and escalation authority.

#### Responsibilities
- Define business objectives and strategic priorities
- Provide go/no-go decisions at key project gates
- Allocate budget, resources, and staffing
- Communicate project status to leadership and board
- Escalate business-impacting issues and decisions
- Align projects with organizational strategy
- Remove organizational blockers

#### Goals
- Ensure strategic alignment and business value realization
- Optimize resource allocation and ROI
- Reduce business risk and escalation
- Enable executive visibility and governance

#### Typical Communication
- Executive status reports and steering committee updates
- Business case and ROI tracking
- Escalation notifications and go/no-go decision meetings
- Resource allocation and planning communications

#### Interactions
- Receives escalations from **Project Manager** on business-impacting issues
- Aligns **Product Manager** roadmap with strategic priorities
- Approves major resource and budget decisions
- Participates in key project gates (initiation, planning, release decision)
- Communicates with external stakeholders and board

---

### Support / Customer Success Lead

#### Role Summary
Support/Customer Success Leads represent customer needs and operational readiness. They ensure the organization can support new features and capture customer feedback for product improvement.

#### Responsibilities
- Represent customer support perspective in feature planning
- Validate feature documentation and operational runbooks
- Prepare support team for new feature releases
- Triage and escalate customer support issues
- Capture and prioritize customer feedback
- Identify product gaps discovered through customer interactions
- Coordinate with Product on documentation and training needs
- Monitor customer satisfaction and support metrics

#### Goals
- Enable smooth customer adoption and satisfaction
- Reduce support burden through quality documentation and runbooks
- Create feedback loop from customers to product
- Minimize customer impact during releases

#### Typical Communication
- Customer feedback reports and feature request summaries
- Support readiness documentation and runbooks
- Release impact assessments from customer perspective
- Customer satisfaction metrics and trends
- Training and documentation requirements

#### Interactions
- Partners with **Product Manager** on customer feedback integration
- Collaborates with **Design/UX Lead** on documentation and usability
- Works with **Developers** on operational documentation and troubleshooting
- Reviews **Release and Deployment** plans from support readiness perspective
- Provides input to **QA Lead** on critical customer workflows

---

## How These Personas Are Used

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When roles are not explicitly defined on your team, combine responsibilities where appropriate.
- For larger organizations, these roles may be distributed across multiple team members; for smaller teams, individuals may hold multiple roles.

---

## Persona Interaction Matrix

| Primary Role | Key Partners | Handoff Points | Conflict Resolution |
|---|---|---|---|
| **Product Manager** | Technical Lead, Design/UX, Support, Sponsor | Feature specs, acceptance criteria, roadmap | Sponsor or Product Lead approval |
| **Project Manager** | All roles | Timeline, resource allocation, risk escalation | Sponsor or Executive decision |
| **Developer** | Technical Lead, QA, DevOps | Code reviews, test coordination, deployment | Technical Lead or Architect decision |
| **Technical Lead** | Developers, DevOps, Security | Architecture decisions, tech standards, security review | Architecture review board or CTO |
| **QA Lead** | Developers, Product, Support | Acceptance criteria, test plans, release readiness | Product Manager or Project Manager |
| **Design/UX Lead** | Product Manager, Developers | Design specs, usability validation, component library | Design Lead or UX Director |
| **Security Officer** | Technical Lead, DevOps, all teams | Security requirements, risk mitigation, pre-release review | CISO or Security Lead |
| **DevOps Owner** | Developers, Technical Lead, Release Lead | Deployment plans, infrastructure needs, incident response | DevOps Lead or Infrastructure Director |
| **Support Lead** | Product Manager, Developers, QA | Customer readiness, documentation, feedback loop | Product Manager or Customer Success Director |
| **Sponsor** | Project Manager, Product Manager | Go/no-go decisions, resource allocation, escalations | Executive or Board |
