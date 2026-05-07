# Cross-Functional Collaboration Checklist

## Purpose
Ensure effective coordination and communication across specialized roles throughout the project lifecycle.

---

## Pre-Project Planning

- [ ] **Sponsor & Executive Alignment**
  - Sponsor has approved business case and strategic alignment
  - Budget and resource allocation confirmed
  - Executive escalation paths documented

- [ ] **Product Manager Readiness**
  - Success metrics defined and measurable
  - Customer/user research completed
  - Market context and competitive analysis available
  - Acceptance criteria template prepared

- [ ] **Technical Lead Involvement**
  - Technical feasibility assessment completed
  - Architectural constraints identified
  - Technology stack decisions documented
  - Scalability and performance requirements defined

- [ ] **Security/Compliance Review**
  - Security and compliance requirements identified
  - Data privacy considerations documented
  - Regulatory or industry standards noted
  - Security review checkpoints scheduled

- [ ] **Design/UX Preparation**
  - UX research or user personas available
  - Design system and component library reviewed
  - Accessibility requirements confirmed
  - Design review schedule planned

---

## Project Initiation Phase

- [ ] **Kickoff Meeting Completed**
  - All key roles present: PM, PdM, Tech Lead, QA Lead, Design, Security, DevOps, Support
  - Project one-pager reviewed and approved
  - Success criteria and metrics shared
  - Timeline and milestones confirmed

- [ ] **Role Assignments & Ownership**
  - Project Manager assigned
  - Product Manager assigned
  - Technical Lead identified
  - QA/Testing lead assigned
  - On-call/escalation contacts defined
  - Sponsor point-of-contact confirmed

- [ ] **Communication Plan Established**
  - Stakeholder communication cadence set (weekly, bi-weekly, monthly)
  - Stand-up frequency and format defined
  - Escalation procedures documented
  - Status report template agreed
  - Decision-making authority clarified

---

## Planning Phase

- [ ] **Technical Design & Architecture**
  - Technical design review held with Tech Lead and Developers
  - Architecture Decision Records (ADRs) documented
  - DevOps input on deployment and infrastructure approach obtained
  - Security/Compliance architectural requirements reviewed
  - Scalability and reliability patterns validated

- [ ] **Acceptance Criteria & Definition of Done**
  - Product Manager defines acceptance criteria
  - QA Lead reviews for testability
  - Technical Lead validates feasibility
  - Design/UX validates user experience aspects
  - Support Lead reviews for operational readiness
  - Final DoD approved by all parties

- [ ] **Quality & Testing Strategy**
  - Test strategy defined by QA Lead
  - Test automation roadmap created
  - QA environment requirements identified with DevOps
  - Security testing approach defined with Security Officer
  - Release readiness criteria documented

- [ ] **Risk Assessment & Mitigation**
  - Risk register created and populated
  - Technical risks assessed by Technical Lead
  - Security/Compliance risks identified
  - Dependencies mapped to cross-functional teams
  - Escalation paths documented in risk register
  - Mitigation owners assigned

- [ ] **Release & Deployment Planning**
  - Release window scheduled with DevOps
  - Deployment steps documented by DevOps/Tech Lead
  - Rollback plan prepared
  - Post-deployment verification steps defined
  - Support readiness plan created with Support Lead
  - Customer communication plan drafted with Support and Product

---

## Execution Phase

- [ ] **Ongoing Collaboration**
  - Daily standups held (include all relevant roles)
  - Weekly sync between PM and PdM
  - Technical design reviews scheduled as needed
  - Code review process active (including Design/UX review for UI changes)
  - QA testing aligned with development pace

- [ ] **Risk & Issue Management**
  - Risk register reviewed weekly
  - Blockers escalated promptly
  - Cross-team dependencies tracked and monitored
  - Security/Compliance issues triage weekly
  - Operational metrics and alerts monitored by DevOps

- [ ] **Documentation & Knowledge Sharing**
  - Architecture and design decisions documented (ADRs)
  - Code documentation kept current
  - Runbooks and operational guides drafted by DevOps
  - Customer documentation prepared by Support/Product
  - Known issues and workarounds tracked
  - Design system components updated

- [ ] **Quality Assurance Checkpoints**
  - Acceptance criteria reviewed before QA
  - QA testing completed and sign-off obtained
  - Security testing/scanning results reviewed
  - Performance benchmarks validated
  - Accessibility compliance verified

---

## Pre-Release Phase

- [ ] **Release Readiness Review (Gate 1)**
  - All acceptance criteria met (sign-off from Product Manager)
  - QA sign-off obtained (no critical/high-severity bugs)
  - Security scan results reviewed and approved by Security Officer
  - Performance/scalability testing completed by DevOps/Tech Lead
  - Design/UX review completed for user-facing changes
  - Accessibility audit passed

- [ ] **Deployment Readiness (Gate 2)**
  - Deployment plan finalized by DevOps
  - Rollback procedure tested and documented
  - Infrastructure capacity verified by DevOps
  - Monitoring and alerting configured by DevOps
  - Incident response runbook prepared
  - On-call schedule for deployment window defined

- [ ] **Support Readiness (Gate 3)**
  - Support documentation complete and reviewed
  - Support team trained by Support Lead
  - FAQ and known issues list prepared
  - Customer communication drafted and reviewed
  - Support escalation procedures updated
  - Support systems (ticketing, runbooks) updated

- [ ] **Stakeholder Sign-Off (Gate 4)**
  - Sponsor/Executive approval obtained
  - Customer/client sign-off (if applicable)
  - Release notes reviewed and approved
  - Go/No-Go decision made by Sponsor

---

## Release & Deployment Phase

- [ ] **Deployment Execution**
  - Deployment team assembled (DevOps, Tech Lead, Support)
  - Staging deployment verification completed
  - Production deployment executed by DevOps
  - Post-deployment verifications passed
  - Monitoring alerts active and reviewed
  - All parties on standby for incident response

- [ ] **Post-Deployment Verification**
  - Smoke tests passed
  - Business metrics verified by Product Manager
  - User-facing functionality spot-checked by Design/UX
  - Performance metrics within acceptable range
  - Error rates and logs reviewed by DevOps
  - Customer communications sent by Support

- [ ] **Incident Response (if needed)**
  - Issue severity classified immediately
  - Incident commander assigned
  - Relevant roles notified (Tech Lead, DevOps, Product, Support)
  - Root cause analysis initiated
  - Rollback decision made (if necessary)
  - Customer communication issued

---

## Post-Release Phase

- [ ] **Retrospective & Learning**
  - Retrospective held within 2 weeks of release
  - All functional leads participate
  - What went well documented
  - Areas for improvement identified
  - Action items assigned with clear owners and due dates
  - Process improvements captured for next release

- [ ] **Feedback & Continuous Improvement**
  - Customer feedback collected by Support Lead
  - Feature usage metrics reviewed by Product Manager
  - Technical debt captured by Technical Lead
  - Security/Compliance findings documented
  - Design/UX user experience feedback gathered
  - Improvements prioritized for next phase

- [ ] **Documentation Updates**
  - Process docs updated with lessons learned
  - Runbooks and troubleshooting guides updated
  - Known issues and resolutions documented
  - Architecture decisions reviewed and updated
  - Design system refreshed with new patterns
  - Training materials updated

---

## Escalation & Decision-Making

### Issue Escalation Path
1. **Level 1 (Team)**: Addressed in daily standup or by directly involved roles
2. **Level 2 (Leadership)**: Project Manager escalates to Product Manager and Sponsor
3. **Level 3 (Executive)**: Sponsor makes final decision or escalates further

### Typical Escalation Scenarios
- **Schedule Risk**: PM escalates to Sponsor → Resource reallocation or scope adjustment
- **Technical Blocker**: Tech Lead escalates to PM → Architectural decision or dependency resolution
- **Security Issue**: Security Officer escalates to Tech Lead & PM → Remediation plan required
- **Quality Issue**: QA Lead escalates to PM → Acceptance criteria review or timeline adjustment
- **Customer Impact**: Support Lead escalates to Product Manager → Customer communication and mitigation

### Decision Authority Matrix

| Decision | Authority | Participants |
|---|---|---|
| Feature scope/acceptance criteria | Product Manager | PdM, Tech Lead, Design, Dev |
| Technical approach/architecture | Technical Lead | Tech Lead, Developers, DevOps |
| Quality gates/release readiness | QA Lead + Product Manager | QA, Product, Tech Lead |
| Security approval | Security Officer | Security, Tech Lead, DevOps |
| Release go/no-go | Sponsor | Sponsor, PM, Product, Tech Lead |
| Timeline/schedule changes | Project Manager with Sponsor approval | PM, Sponsor, all leads |
| Resource allocation | Sponsor | Sponsor, PM, all leads |

---

## Success Metrics

Track these metrics to ensure cross-functional collaboration effectiveness:

- **On-time delivery** vs. initial estimate
- **Defect escape rate** (bugs found post-release vs. in QA)
- **Security/Compliance issues** found post-launch vs. during reviews
- **Support burden** (tickets, issues) within first 2 weeks
- **Team satisfaction score** from retrospectives
- **Stakeholder satisfaction** on communication and transparency
- **Rework percentage** (estimated time spent on rework vs. new work)
- **Cycle time** from idea to production
