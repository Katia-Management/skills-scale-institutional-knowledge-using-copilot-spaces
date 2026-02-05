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

## QA Engineers / Testers

### Role Summary
QA Engineers validate quality and ensure features meet acceptance criteria before release. They design test strategies, execute testing, and advocate for quality standards throughout the development lifecycle.

### Responsibilities
- Create and maintain test plans and test cases
- Execute manual and automated tests (unit, integration, end-to-end)
- Validate acceptance criteria and Definition of Done
- Report and track defects with clear reproduction steps
- Participate in sprint planning to identify testability concerns
- Conduct smoke tests before and after deployments
- Collaborate with developers on test automation strategies

### Goals
- Ensure features meet quality standards before release
- Reduce production defects and post-release issues
- Improve test coverage and automation efficiency
- Shorten feedback loops between development and testing

### Typical Communication
- Daily standups to report testing progress and blockers
- Bug reports and test results in project tracking tools
- Test plans and QA sign-off for releases
- Participation in release planning and retrospectives

### Interactions with Other Roles
- **With Developers**: Collaborate on testability, automation, and bug fixes
- **With Product Managers**: Clarify acceptance criteria and edge cases
- **With Project Managers**: Report testing status and risks to timelines
- **With Stakeholders**: Provide quality assurance for release readiness

---

## Stakeholders

### Role Summary
Stakeholders are individuals or groups with vested interest in project outcomes. They provide input, make decisions, and receive project benefits. Stakeholders can include executives, customers, partner teams, sales, support, and other impacted groups.

### Responsibilities
- Provide requirements, constraints, and business context
- Review and approve key project decisions and deliverables
- Participate in project reviews and milestone demonstrations
- Communicate impact to their respective areas
- Escalate concerns or changing priorities
- Provide feedback on delivered features

### Goals
- Ensure project delivers expected business value
- Protect interests of their represented group
- Stay informed of progress and changes
- Enable project success through timely decisions and support

### Typical Communication
- Monthly stakeholder updates and milestone reviews
- Ad-hoc consultations for decision-making
- Demo sessions and acceptance reviews
- Feedback channels and surveys

### Interactions with Other Roles
- **With Project Managers**: Receive status updates, provide input on priorities
- **With Product Managers**: Share business requirements and validate solutions
- **With Developers**: Attend demos, provide domain expertise when needed
- **With QA Engineers**: Participate in user acceptance testing

---

## Engineering Lead / Technical Lead

### Role Summary
Engineering Leads provide technical direction and architectural guidance for projects. They ensure technical quality, mentor developers, and make key design decisions that affect scalability, maintainability, and performance.

### Responsibilities
- Define technical architecture and design patterns
- Review and approve technical designs and major implementation approaches
- Mentor and support developers on technical challenges
- Ensure code quality through architecture reviews and standards
- Identify and mitigate technical risks and debt
- Make technology and tooling decisions
- Facilitate technical discussions and resolve design conflicts

### Goals
- Ensure technical solutions are scalable, maintainable, and aligned with standards
- Build team technical capabilities through mentorship
- Balance short-term delivery needs with long-term technical health
- Minimize technical debt and architectural risks

### Typical Communication
- Architecture design reviews and technical specifications
- Code reviews with focus on design and patterns
- Weekly technical syncs with PM and Product Manager
- Technical retrospectives and improvement planning

### Interactions with Other Roles
- **With Developers**: Mentor, review designs, resolve technical blockers
- **With Product Managers**: Advise on technical feasibility and trade-offs
- **With Project Managers**: Communicate technical risks and dependencies
- **With QA Engineers**: Collaborate on test strategy and quality standards

---

## Release Manager

### Role Summary
Release Managers coordinate and execute software releases to production. They ensure deployments are safe, well-communicated, and properly documented, minimizing risk and downtime.

### Responsibilities
- Plan and schedule release windows
- Coordinate release activities across teams
- Maintain release checklists and run books
- Execute deployment procedures and verification steps
- Manage rollback procedures if issues occur
- Communicate release status to stakeholders
- Document release notes and migration guides
- Ensure compliance with release policies and approvals

### Goals
- Achieve zero-downtime deployments
- Minimize production incidents from releases
- Increase deployment frequency while maintaining stability
- Improve release process efficiency through automation

### Typical Communication
- Release schedules and deployment notifications
- Go/no-go decision meetings
- Incident reports and post-deployment summaries
- Release notes and change communications

### Interactions with Other Roles
- **With Developers**: Coordinate code freeze, merge schedules, and hotfixes
- **With QA Engineers**: Validate pre-release testing completion
- **With Project Managers**: Align release timing with project milestones
- **With Stakeholders**: Announce releases and communicate impacts

---

## Security Engineer

### Role Summary
Security Engineers ensure that projects meet security standards and best practices. They conduct security reviews, manage vulnerability scanning, and provide guidance on secure development practices.

### Responsibilities
- Conduct security reviews of designs and implementations
- Configure and monitor security scanning in CI/CD pipelines
- Triage and prioritize security vulnerabilities
- Provide security training and guidance to development teams
- Participate in incident response for security issues
- Maintain security documentation and runbooks
- Ensure compliance with security policies and standards

### Goals
- Prevent security vulnerabilities from reaching production
- Minimize security incident response time
- Build security awareness across engineering teams
- Balance security requirements with delivery timelines

### Typical Communication
- Security review findings and recommendations
- Vulnerability reports and remediation tracking
- Security incident communications
- Security training sessions and documentation

### Interactions with Other Roles
- **With Developers**: Review code for security issues, provide secure coding guidance
- **With Engineering Lead**: Consult on architecture security implications
- **With Project Managers**: Report security risks and remediation timelines
- **With Release Manager**: Validate security compliance before releases

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The interaction sections show how roles collaborate, helping teams understand dependencies and communication patterns.
- These personas represent the complete ecosystem of roles involved in successful project delivery at OctoAcme.

