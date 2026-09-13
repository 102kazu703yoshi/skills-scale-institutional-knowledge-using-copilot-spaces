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

### Interactions with Other Roles
- Work with **QA/Testing Leads** to ensure test coverage and address defects
- Collaborate with **Technical Architects** on design reviews and architectural decisions
- Partner with **Project Managers** for task tracking and dependency management
- Receive requirements from **Product Managers** and implement acceptance criteria
- Report security concerns to **Security Champions** and incorporate security reviews into development

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

### Interactions with Other Roles
- Partner with **Project Managers** on release planning and timeline management
- Align with **Sponsors** on business objectives and prioritization
- Provide acceptance criteria to **Developers** and **QA/Testing Leads**
- Collaborate with **Technical Architects** on feasibility and trade-offs
- Work with **Release Managers** on feature rollout and go-to-market timing

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

### Interactions with Other Roles
- Work with **Developers** and **Technical Architects** to manage task schedules and technical dependencies
- Partner with **Product Managers** on scope and prioritization decisions
- Coordinate with **QA/Testing Leads** on quality gates and release readiness
- Escalate risks and blockers to **Sponsors** and maintain stakeholder alignment
- Work with **Release Managers** on deployment planning and coordination
- Partner with **Security Champions** to integrate security review gates into project timelines

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance strategy, test planning, and execution. They ensure features meet acceptance criteria and perform as expected in production.

### Responsibilities
- Develop and maintain test plans aligned with feature requirements
- Execute functional, integration, and end-to-end testing
- Identify and document defects with clear reproduction steps
- Collaborate with developers on test coverage and automation
- Perform smoke tests before release
- Validate acceptance criteria completion
- Work with the team to define Definition of Done

### Goals
- Ensure high-quality releases with minimal production issues
- Reduce escape defects through effective testing strategy
- Support continuous integration with automated test coverage

### Typical Communication
- Sprint planning and acceptance criteria review
- Defect logs and test status updates
- Release readiness sign-off

### Interactions with Other Roles
- Collaborate with **Developers** to design testable code and establish test coverage standards
- Review **Product Manager** acceptance criteria to ensure test completeness
- Report quality metrics to **Project Managers** for release readiness decisions
- Work with **Technical Architects** on testing strategy for complex features
- Coordinate with **Release Managers** on smoke tests and post-deployment verification
- Participate in security testing coordinated by **Security Champions**

---

## Technical Architect / Tech Lead

### Role Summary
Technical Architects design system solutions, guide technical decisions, and ensure scalability and maintainability of the codebase.

### Responsibilities
- Review technical designs and propose solutions for complex problems
- Identify technical risks and propose mitigations
- Guide code quality standards and architectural consistency
- Mentor developers and conduct technical design reviews
- Ensure alignment with platform scalability and security standards

### Goals
- Enable sustainable, scalable architecture
- Reduce technical debt and rework
- Share knowledge across the team

### Typical Communication
- Technical design docs and architecture reviews
- Code review participation and guidance
- Risk escalation for technical blockers

### Interactions with Other Roles
- Mentor and guide **Developers** on architectural decisions and code quality
- Collaborate with **Project Managers** on technical feasibility and timeline impact
- Review designs and constraints with **Product Managers** on trade-offs
- Work with **QA/Testing Leads** to design testable architectures
- Partner with **Security Champions** on secure-by-design principles
- Escalate architectural risks to **Project Managers** and **Sponsors**
- Coordinate with **Release Managers** on deployment architecture

---

## Release Manager

### Role Summary
Release Managers coordinate deployment activities, manage release schedules, and ensure smooth transitions to production.

### Responsibilities
- Schedule and coordinate release windows
- Verify pre-release requirements and checklists
- Manage deployment sequencing and rollback procedures
- Track release notes and communicate to stakeholders
- Monitor post-deployment verification
- Coordinate with DevOps and on-call teams

### Goals
- Execute zero-defect or low-risk releases
- Maintain predictable release cadence
- Minimize incident response time

### Typical Communication
- Release schedules and deployment plans
- Release notes and stakeholder announcements
- Post-deployment status and incident updates

### Interactions with Other Roles
- Work with **Developers** on build readiness and deployment verification
- Coordinate with **QA/Testing Leads** on smoke test execution and release sign-off
- Partner with **Project Managers** on release scheduling and stakeholder communication
- Align with **Product Managers** on feature rollout strategy and messaging
- Collaborate with **Technical Architects** on deployment architecture and rollback procedures
- Coordinate with **Security Champions** on security verification before release
- Brief **Sponsors** on release status and business impact

---

## Security Champion

### Role Summary
Security Champions embed security practices into the development lifecycle, advocate for secure coding, and coordinate security reviews.

### Responsibilities
- Conduct security threat modeling for new features
- Review code for security vulnerabilities
- Coordinate with Security team on scans and remediation
- Drive security awareness and training
- Escalate security issues following incident runbook
- Ensure compliance with security standards

### Goals
- Prevent security incidents and data breaches
- Embed security culture in development practices
- Maintain compliance with organizational policies

### Typical Communication
- Security review participation and design discussions
- Vulnerability reports and remediation tracking
- Security incident escalation and response

### Interactions with Other Roles
- Work with **Developers** to review code for security vulnerabilities and provide secure coding guidance
- Partner with **Technical Architects** on secure-by-design principles and threat modeling
- Collaborate with **QA/Testing Leads** on security testing and validation
- Inform **Project Managers** of security risks and remediation timelines
- Brief **Product Managers** on security trade-offs and compliance requirements
- Coordinate with **Release Managers** on security verification before deployment
- Escalate critical security issues to **Sponsors** and organizational security team

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors provide business context, funding, and executive oversight. They are ultimate decision-makers for go/no-go decisions and strategic direction.

### Responsibilities
- Define business objectives and success metrics
- Provide resources and remove organizational barriers
- Review and approve major decisions and trade-offs
- Communicate project progress to leadership
- Escalate risks with business impact

### Goals
- Ensure project alignment with business strategy
- Enable team success through timely decisions and support
- Deliver measurable business value

### Typical Communication
- Monthly stakeholder updates
- Milestone approvals and go/no-go decisions
- Risk escalation and barrier removal

### Interactions with Other Roles
- Receive status updates and escalations from **Project Managers**
- Set strategic direction and priorities with **Product Managers**
- Approve resource allocation and address organizational barriers for the delivery team
- Review high-level risks from **Technical Architects** and **Security Champions**
- Receive release updates and business impact assessments from **Release Managers**
- Make go/no-go decisions based on quality readiness from **QA/Testing Leads** and delivery status from **Project Managers**

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Interactions between personas demonstrate the collaborative nature of project execution and the importance of clear communication across roles.
