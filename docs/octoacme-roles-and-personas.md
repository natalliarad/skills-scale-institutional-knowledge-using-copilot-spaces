# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It serves as a central reference for understanding who does what, how roles interact, and what success looks like for each persona. Use this document to:
- Clarify role boundaries and handoffs
- Assign ownership for tasks and deliverables
- Define success metrics and KPIs for each role
- Onboard new team members to their responsibilities

For a standardized template to document additional roles or customize these personas, see the [Role Description Template](templates/role-description-template.md).

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

## Agile Coach

### Role Summary
The Agile Coach guides teams in adopting and improving agile practices, facilitates ceremonies, and helps remove impediments to flow. They work across teams to drive continuous improvement, coach team members on agile principles, and ensure alignment on processes and practices.

### Responsibilities
- Facilitate sprint planning, daily standups, retrospectives, and sprint reviews
- Coach Product Managers, Project Managers, and team members on agile principles
- Help teams identify and remove impediments or blockers
- Monitor team health metrics (velocity, cycle time, happiness/satisfaction)
- Recommend process improvements based on retrospective feedback
- Ensure consistent use of project boards and agile artifacts
- Train new team members on OctoAcme's agile processes

### Key Interactions
**Collaborates with:**
- **Project Managers:** Partners on planning, scheduling, and removing blockers; shares insights on team capacity and health
- **Product Managers:** Helps refine backlog, ensures stories meet Definition of Ready, coaches on effective acceptance criteria
- **Developers and QA:** Facilitates ceremonies, coaches on estimation and self-organization
- **Change Management Lead:** Aligns on adoption strategies for process changes

**Handoffs:**
- Retrospective action items to Project Managers for tracking
- Team health and velocity reports to leadership
- Process improvement recommendations to PMO or engineering leadership

### Typical Measurables / KPIs
- Team velocity trends (stable or improving over time)
- Cycle time and lead time improvements
- Retrospective action item completion rate (target: >80%)
- Team satisfaction scores (quarterly surveys)
- Adoption rate of agile practices across teams

---

## Data Steward

### Role Summary
The Data Steward ensures data quality, governance, and compliance across projects. They define data standards, manage data access policies, and collaborate with engineering and analytics teams to maintain trustworthy data assets.

### Responsibilities
- Define and enforce data quality standards and governance policies
- Manage data access controls and compliance with privacy regulations (GDPR, CCPA, etc.)
- Maintain data catalogues and documentation (schemas, lineage, definitions)
- Collaborate with engineering on data pipeline quality and monitoring
- Review data-related changes for compliance and quality impact
- Conduct data quality audits and remediation efforts
- Train teams on data handling best practices and policies

### Key Interactions
**Collaborates with:**
- **Developers:** Reviews data model changes, provides guidance on data quality checks and validation
- **Business Analysts:** Ensures data definitions align with business needs; clarifies data availability and lineage
- **Security Champion:** Coordinates on data access policies, encryption, and compliance requirements
- **Product Managers:** Advises on data-driven feature requirements and privacy considerations

**Handoffs:**
- Data quality reports to Product Managers and leadership
- Compliance documentation to Legal and Security teams
- Data catalogue updates to all teams

### Typical Measurables / KPIs
- Data quality score (completeness, accuracy, consistency targets: >95%)
- Number of data governance policy violations (target: zero critical violations)
- Data catalogue coverage (percentage of datasets documented: target >90%)
- Time to resolve data quality issues (target: <48 hours for critical issues)
- Compliance audit pass rate (target: 100%)

---

## Change Management Lead

### Role Summary
The Change Management Lead drives successful adoption of organizational, process, or technology changes. They assess impact, plan communications, coordinate training, and ensure stakeholders are prepared for transitions. They work to minimize resistance and maximize the effectiveness of changes.

### Responsibilities
- Assess impact of proposed changes on teams, processes, and systems
- Develop and execute change management and communications plans
- Coordinate training and support resources for affected teams
- Identify and engage change champions across the organization
- Monitor adoption metrics and address resistance or barriers
- Define rollback procedures and contingency plans
- Facilitate stakeholder sign-off and readiness assessments

### Key Interactions
**Collaborates with:**
- **Project Managers:** Aligns on change timelines, coordinates communication and training with project milestones
- **Agile Coach:** Partners on adoption strategies for agile process changes
- **Business Analysts:** Gathers requirements for training materials and user documentation
- **Leadership/Sponsors:** Obtains sign-off and communicates change impact to executives

**Handoffs:**
- Change impact assessments to project stakeholders and sponsors
- Communications plans and materials to marketing or internal comms teams
- Training materials to HR or learning and development teams
- Post-implementation review reports to leadership

### Typical Measurables / KPIs
- Adoption rate of new processes or tools (target: >85% within 30 days)
- Stakeholder readiness score (measured via surveys, target: >4/5)
- Training completion rate (target: >90% of affected users)
- Number of escalations or issues related to change (target: minimize)
- Post-implementation satisfaction score (target: >4/5)

---

## QA Lead

### Role Summary
The QA Lead owns the quality strategy and testing practices for projects. They define test plans, coordinate testing efforts, manage defect triage, and ensure that acceptance criteria are validated before releases. They balance manual and automated testing to deliver high-quality, reliable software.

### Responsibilities
- Define test strategy, test plans, and coverage goals for projects
- Coordinate manual and automated testing efforts across the team
- Review acceptance criteria and ensure testability of user stories
- Lead defect triage and prioritization with Product and Project Managers
- Maintain and improve test automation frameworks and CI/CD test suites
- Monitor quality metrics (defect rates, test coverage, flakiness)
- Advocate for quality throughout the development lifecycle

### Key Interactions
**Collaborates with:**
- **Developers:** Reviews test coverage, pairs on test automation, clarifies defect reproduction steps
- **Product Managers:** Validates acceptance criteria, provides input on quality risks and trade-offs
- **DevOps/Release Engineer:** Integrates automated tests into CI/CD pipelines, coordinates release validation
- **Project Managers:** Reports on testing progress, quality metrics, and release readiness

**Handoffs:**
- Test plans and coverage reports to Project Managers
- Defect reports and prioritization to Product Managers
- Release sign-off (or no-go recommendation) to Release Engineer and stakeholders

### Typical Measurables / KPIs
- Test coverage (target: >80% code coverage, 100% of critical paths)
- Defect escape rate (defects found in production, target: <5% of total defects)
- Test automation rate (percentage of tests automated, target: >70%)
- Mean time to detect (MTTD) defects (target: <1 day)
- Release confidence score (internal team assessment, target: >4/5)

---

## DevOps/Release Engineer

### Role Summary
The DevOps/Release Engineer manages CI/CD pipelines, infrastructure automation, and release processes. They ensure that code moves from development to production reliably, securely, and efficiently. They collaborate with developers, QA, and operations teams to maintain platform stability and deployment velocity.

### Responsibilities
- Build and maintain CI/CD pipelines (build, test, deploy automation)
- Manage infrastructure as code (IaC) and cloud resource provisioning
- Coordinate release planning, scheduling, and deployment activities
- Monitor deployment success rates, rollback procedures, and incident response
- Implement security scanning and compliance checks in pipelines
- Maintain observability and monitoring for production systems
- Provide on-call support for deployment and infrastructure issues

### Key Interactions
**Collaborates with:**
- **Developers:** Assists with pipeline configuration, troubleshoots build/deploy issues, implements deployment best practices
- **QA Lead:** Integrates automated tests into pipelines, coordinates release validation and smoke tests
- **Security Champion:** Implements security scanning tools, remediates vulnerabilities in dependencies and infrastructure
- **Project Managers:** Communicates release schedules, deployment windows, and rollback plans

**Handoffs:**
- Release notes and deployment runbooks to operations and support teams
- Incident post-mortems and performance metrics to leadership
- Infrastructure change logs to Security and Compliance teams

### Typical Measurables / KPIs
- Deployment frequency (target: daily or per sprint)
- Deployment success rate (target: >95%)
- Mean time to recovery (MTTR) from failed deployments (target: <30 minutes)
- CI/CD pipeline reliability (target: <5% flaky test rate)
- Infrastructure uptime (target: >99.9%)

---

## Business Analyst

### Role Summary
The Business Analyst bridges the gap between business stakeholders and technical teams. They gather and document requirements, model processes, and ensure that solutions align with business objectives. They translate business needs into clear, actionable specifications for development teams.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Create process flows, user stories, and functional specifications
- Analyze and model business processes to identify improvement opportunities
- Validate that delivered solutions meet business requirements
- Facilitate workshops and requirement review sessions
- Maintain traceability between requirements and deliverables
- Support User Acceptance Testing (UAT) coordination

### Key Interactions
**Collaborates with:**
- **Product Managers:** Partners on roadmap priorities, translates product vision into detailed requirements
- **Developers:** Clarifies requirements, reviews technical designs for business alignment, answers questions during implementation
- **QA Lead:** Defines acceptance criteria, participates in test planning and UAT
- **UX Researcher:** Shares user insights to inform requirements and validates that designs meet business needs

**Handoffs:**
- Business requirements documents (BRDs) and user stories to development teams
- Process maps and workflow diagrams to Product Managers and stakeholders
- UAT plans and results to Project Managers and Product Managers

### Typical Measurables / KPIs
- Requirements clarity score (measured via developer surveys, target: >4/5)
- Requirement change rate (target: <10% post-sprint commitment)
- UAT pass rate (target: >90% on first attempt)
- Stakeholder satisfaction with requirements documentation (target: >4/5)
- Time to finalize requirements (target: <2 weeks per epic)

---

## UX Researcher

### Role Summary
The UX Researcher conducts user research to inform product decisions, validate design hypotheses, and ensure that solutions meet user needs. They employ qualitative and quantitative research methods to uncover insights about user behavior, pain points, and preferences.

### Responsibilities
- Plan and conduct user research studies (interviews, surveys, usability tests)
- Synthesize research findings into actionable insights and recommendations
- Create user personas, journey maps, and research reports
- Collaborate with designers and Product Managers to validate design concepts
- Maintain a research repository and share insights across teams
- Advocate for user-centered design throughout the product lifecycle
- Define and track UX metrics (e.g., task success rate, satisfaction scores)

### Key Interactions
**Collaborates with:**
- **Product Managers:** Provides user insights to inform roadmap and feature prioritization decisions
- **Business Analysts:** Shares research findings to validate business requirements and user needs alignment
- **Developers:** Communicates usability findings and design rationale to guide implementation
- **QA Lead:** Coordinates on usability testing and accessibility validation

**Handoffs:**
- Research reports and personas to Product Managers and design teams
- Usability test results and recommendations to developers and QA
- UX metrics dashboards to leadership and stakeholders

### Typical Measurables / KPIs
- Research study completion rate (target: 100% of planned studies on time)
- User satisfaction score (e.g., NPS, CSAT; target: >70 NPS or >4/5 CSAT)
- Task success rate in usability tests (target: >80%)
- Insight adoption rate (percentage of recommendations implemented, target: >60%)
- Research velocity (number of studies completed per quarter, target: varies by team size)

---

## Security Champion

### Role Summary
The Security Champion embeds security practices within development teams. They advocate for secure coding, conduct security reviews, coordinate vulnerability remediation, and ensure compliance with security policies. They act as the bridge between the security team and development teams.

### Responsibilities
- Promote secure coding practices and conduct secure code reviews
- Coordinate security testing (SAST, DAST, dependency scanning) in CI/CD pipelines
- Triage and prioritize security vulnerabilities and coordinate remediation
- Facilitate threat modeling sessions for new features or architectures
- Provide security training and awareness to development teams
- Monitor security metrics and report on security posture
- Ensure compliance with security policies and regulatory requirements

### Key Interactions
**Collaborates with:**
- **Developers:** Reviews code for security vulnerabilities, provides guidance on secure coding and remediation
- **DevOps/Release Engineer:** Integrates security scanning tools into CI/CD pipelines, reviews infrastructure security configurations
- **Data Steward:** Coordinates on data encryption, access controls, and privacy compliance
- **Project Managers:** Communicates security risks, timelines for remediation, and release blockers

**Handoffs:**
- Security vulnerability reports and remediation plans to development teams
- Threat models and security assessments to Product Managers and architects
- Security metrics and compliance reports to leadership and auditors

### Typical Measurables / KPIs
- Time to remediate critical vulnerabilities (target: <7 days)
- Number of open security vulnerabilities by severity (target: zero critical/high >30 days old)
- Security training completion rate (target: 100% of developers annually)
- Secure code review coverage (target: 100% of PRs for sensitive areas)
- Security incident response time (target: <1 hour for critical incidents)

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

