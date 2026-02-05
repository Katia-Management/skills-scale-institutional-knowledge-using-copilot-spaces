# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

These personas represent the complete ecosystem of roles involved in successful project delivery. They cover development, product management, operations, quality assurance, research, and knowledge management.

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

## Data Analyst / Metrics Lead

### Role Summary
Data Analysts provide visibility into product health and team performance through metrics, dashboards, and data analysis. They enable data-informed decision-making by collecting, analyzing, and interpreting key signals across the product lifecycle.

### Responsibilities
- Define and track key success metrics (KPIs, OKRs)
- Build and maintain dashboards for product health (errors, latency, usage, adoption)
- Set up instrumentation and monitoring for new features
- Analyze trends and provide insights to Product Managers and stakeholders
- Support A/B testing and experiment analysis
- Create data reports for retrospectives and decision-making
- Ensure data quality and consistency across systems

### Goals
- Provide real-time visibility into product performance
- Enable data-driven prioritization and decision-making
- Identify issues and opportunities through trend analysis
- Reduce time-to-insight for product questions

### Typical Communication
- Weekly metrics reviews with Product Managers
- Dashboard updates and metric alerts
- Data insights reports for stakeholders
- Retrospective data summaries

### Interactions with Other Roles
- **With Product Managers**: Collaborate on success metrics definition and outcome measurement
- **With Developers**: Work on instrumentation implementation and data collection
- **With Project Managers**: Provide data for status reports and decision-making
- **With Stakeholders**: Present insights and trends through visualizations

---

## UX Researcher / Customer Insights Specialist

### Role Summary
UX Researchers ensure customer-first thinking by conducting user research, gathering feedback, and validating product solutions. They bridge the gap between customer needs and product decisions through structured research and insights.

### Responsibilities
- Conduct user interviews, surveys, and usability testing
- Collect and synthesize customer feedback from multiple channels
- Create user personas and journey maps
- Validate product-market fit for new features
- Run competitive analysis and market research
- Present research findings and recommendations
- Establish feedback loops with customers and support teams
- Track customer satisfaction and Net Promoter Score (NPS)

### Goals
- Ensure features solve real customer problems
- Reduce rework by validating solutions before development
- Increase customer satisfaction and adoption
- Build deep understanding of user needs and behaviors

### Typical Communication
- Research findings and insights presentations
- User testing reports and recommendations
- Customer feedback summaries
- Collaboration sessions with Product Managers and designers

### Interactions with Other Roles
- **With Product Managers**: Validate problem statements and solution approaches
- **With Developers**: Share customer context and edge cases
- **With QA Engineers**: Collaborate on acceptance criteria from user perspective
- **With Stakeholders**: Present customer insights and market trends

---

## DevOps Engineer

### Role Summary
DevOps Engineers own infrastructure, CI/CD pipelines, and deployment automation. They enable reliable, frequent deployments while maintaining system observability and operational excellence.

### Responsibilities
- Build and maintain CI/CD pipelines
- Manage infrastructure and cloud resources
- Configure automated testing, linting, and security scanning in CI
- Set up monitoring, logging, and alerting infrastructure
- Implement deployment automation and infrastructure-as-code
- Support incident response and troubleshooting
- Optimize build and deployment performance
- Ensure infrastructure security and compliance

### Goals
- Enable zero-downtime deployments
- Increase deployment frequency while maintaining stability
- Reduce mean time to recovery (MTTR) for incidents
- Automate manual operational tasks

### Typical Communication
- Infrastructure change notifications
- Pipeline and deployment status updates
- Incident response coordination
- Technical documentation for runbooks and procedures

### Interactions with Other Roles
- **With Developers**: Provide CI/CD support and infrastructure guidance
- **With Release Managers**: Coordinate deployment procedures and automation
- **With Security Engineers**: Implement security scanning and compliance checks
- **With Data Analysts**: Support metrics infrastructure and observability

---

## Business Analyst / Requirements Analyst

### Role Summary
Business Analysts bridge stakeholders and delivery teams by gathering, documenting, and clarifying requirements. They ensure clear understanding of business needs, dependencies, and constraints before development begins.

### Responsibilities
- Gather and document business requirements
- Identify dependencies and integration points across systems
- Translate stakeholder needs into clear, actionable specifications
- Facilitate requirements workshops and stakeholder interviews
- Create process flows, use cases, and acceptance criteria
- Manage requirements traceability and change control
- Coordinate cross-functional alignment on scope
- Document business rules and domain knowledge

### Goals
- Prevent scope creep and misalignment
- Reduce rework from unclear requirements
- Ensure all stakeholders have shared understanding
- Identify risks and dependencies early

### Typical Communication
- Requirements documents and specifications
- Stakeholder workshops and alignment meetings
- Scope clarification discussions
- Dependency mapping and impact analysis

### Interactions with Other Roles
- **With Stakeholders**: Gather needs, clarify constraints, validate requirements
- **With Product Managers**: Collaborate on feature definition and prioritization
- **With Project Managers**: Identify dependencies and scope changes
- **With Developers**: Clarify requirements and acceptance criteria

---

## Knowledge Manager / Documentation Lead

### Role Summary
Knowledge Managers ensure institutional knowledge is captured, organized, and accessible. They maintain process documentation, onboarding materials, and learning resources to reduce dependency on individual team members and accelerate onboarding.

### Responsibilities
- Maintain and update process documentation
- Capture learnings from retrospectives and convert to process improvements
- Create and update onboarding materials and runbooks
- Organize knowledge repositories and wikis
- Facilitate knowledge-sharing sessions and training
- Ensure documentation consistency and accessibility
- Track documentation gaps and improvement opportunities
- Support Copilot Spaces integration and knowledge indexing

### Goals
- Reduce onboarding time for new team members
- Minimize single-person knowledge dependency
- Ensure process consistency across teams
- Make institutional knowledge easily searchable and actionable

### Typical Communication
- Documentation update notifications
- Training sessions and knowledge-sharing workshops
- Process improvement proposals from retrospective learnings
- Onboarding guides and reference materials

### Interactions with Other Roles
- **With Project Managers**: Document project processes and retrospective learnings
- **With All Roles**: Gather and organize role-specific knowledge
- **With New Team Members**: Provide onboarding support and guidance
- **With Stakeholders**: Ensure accessible documentation for decision-making

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The interaction sections show how roles collaborate, helping teams understand dependencies and communication patterns.
- These personas represent the complete ecosystem of roles involved in successful project delivery at OctoAcme, from development and operations to research, analysis, and knowledge management.
- The expanded role set addresses gaps in data-driven decision-making, customer insights, infrastructure automation, requirements clarity, and knowledge preservation.

