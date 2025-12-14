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

## Project Sponsors

### Role Summary
Project Sponsors are senior leaders who champion the project, provide strategic direction, secure resources, and remove organizational barriers. They own the business case and ensure the project aligns with organizational goals.

### Responsibilities
- Approve project initiation and authorize funding
- Define success criteria at the strategic level
- Remove organizational blockers and secure cross-functional resources
- Review major milestones and approve scope changes
- Advocate for the project with executive leadership

### Goals
- Ensure project delivers measurable business value
- Maintain alignment with organizational strategy
- Enable the team to succeed with appropriate resources and authority

### Typical Communication
- Monthly steering committee updates
- Approval gates at major milestones
- Escalation point for significant risks or scope changes

### Interaction Points
- **With Project Managers**: Receives status reports, approves major decisions, escalates blockers
- **With Product Managers**: Aligns on strategic priorities and business outcomes
- **With Stakeholder Engagement Lead**: Reviews stakeholder satisfaction and alignment

---

## Quality Assurance Leads

### Role Summary
Quality Assurance Leads define and enforce quality standards, coordinate testing activities, and ensure products meet acceptance criteria before release. They partner with developers and product teams to build quality into every stage.

### Responsibilities
- Define test strategy and quality gates for each project
- Coordinate manual and automated testing efforts
- Review acceptance criteria and ensure testability
- Track defects and coordinate resolution priorities
- Report on quality metrics and release readiness

### Goals
- Ensure products meet functional and non-functional requirements
- Catch defects early in the development cycle
- Maintain high customer satisfaction through quality delivery

### Typical Communication
- Daily coordination with development team during testing cycles
- Weekly quality reports to Project Manager
- Release readiness reviews with Product Manager and Project Manager

### Interaction Points
- **With Developers**: Collaborates on test coverage, reviews PRs for testability, coordinates bug fixes
- **With Project Managers**: Reports on testing progress, flags quality risks, confirms readiness
- **With Product Managers**: Validates acceptance criteria, provides quality metrics for decision-making
- **With Change Manager**: Ensures quality validation of changes before deployment

---

## Change Managers

### Role Summary
Change Managers guide the organization through transitions, ensuring users are prepared, trained, and supported as new features or processes are introduced. They minimize disruption and maximize adoption.

### Responsibilities
- Assess change impact on users and processes
- Develop change management and communication plans
- Coordinate training and documentation for end users
- Monitor adoption metrics and user feedback
- Identify and mitigate resistance to change

### Goals
- Achieve high adoption rates for new features and processes
- Minimize disruption to business operations
- Build organizational capability to embrace future changes

### Typical Communication
- Change impact assessments and readiness reports
- Training sessions and user documentation
- Post-launch adoption tracking and feedback collection

### Interaction Points
- **With Product Managers**: Aligns on user impact and adoption goals
- **With Project Managers**: Coordinates change activities in project timeline
- **With Stakeholder Engagement Lead**: Ensures stakeholders are prepared for changes
- **With Data Steward**: Coordinates data migration and data quality messaging to users

---

## Stakeholder Engagement Leads

### Role Summary
Stakeholder Engagement Leads identify, analyze, and manage relationships with all project stakeholders. They ensure stakeholders remain informed, engaged, and aligned throughout the project lifecycle.

### Responsibilities
- Map and analyze stakeholder interests, influence, and requirements
- Develop stakeholder communication and engagement plans
- Facilitate stakeholder meetings and gather feedback
- Manage expectations and resolve stakeholder concerns
- Track stakeholder satisfaction and engagement metrics

### Goals
- Maintain strong stakeholder alignment and support
- Ensure stakeholder needs are understood and addressed
- Prevent late-stage surprises or misalignment

### Typical Communication
- Regular stakeholder briefings and feedback sessions
- Monthly stakeholder satisfaction surveys
- Ad-hoc engagement for high-priority stakeholder issues

### Interaction Points
- **With Project Managers**: Provides stakeholder feedback, coordinates communication plans
- **With Product Managers**: Shares stakeholder insights that inform prioritization
- **With Project Sponsor**: Reports on stakeholder sentiment and major concerns
- **With Change Manager**: Coordinates stakeholder readiness for changes

---

## Data Stewards

### Role Summary
Data Stewards ensure data quality, governance, and compliance throughout the project. They define data standards, manage data migrations, and protect data privacy and security.

### Responsibilities
- Define data quality standards and validation rules
- Coordinate data migration and integration activities
- Ensure compliance with data privacy regulations (GDPR, CCPA, etc.)
- Document data lineage and data dictionary
- Monitor data quality metrics and address data issues

### Goals
- Maintain high data quality and integrity
- Ensure regulatory compliance and data security
- Enable data-driven decision making with trustworthy data

### Typical Communication
- Data quality reports to Project Manager
- Compliance reviews with legal and security teams
- Data architecture discussions with developers

### Interaction Points
- **With Developers**: Defines data schemas, reviews data handling code, coordinates migrations
- **With Quality Assurance Lead**: Collaborates on data validation testing
- **With Product Managers**: Ensures data requirements support product goals
- **With Change Manager**: Coordinates data migration communication to users

---

## Cross-Role Collaboration and Handoff Points

### Project Initiation Handoffs
1. **Project Sponsor → Project Manager**: Approves project, delegates delivery coordination
2. **Project Manager → Stakeholder Engagement Lead**: Shares stakeholder list for mapping
3. **Product Manager → Quality Assurance Lead**: Provides initial success criteria for test planning

### Planning Phase Handoffs
1. **Product Manager → Developers**: Delivers prioritized backlog with acceptance criteria
2. **Project Manager → Change Manager**: Shares project plan for change impact assessment
3. **Developers → Data Steward**: Identifies data requirements and migration needs
4. **Quality Assurance Lead → Project Manager**: Delivers test strategy and quality gates

### Execution Handoffs
1. **Developers → Quality Assurance Lead**: Submits builds for testing with test notes
2. **Quality Assurance Lead → Developers**: Reports defects with reproduction steps
3. **Data Steward → Quality Assurance Lead**: Validates data migration for testing
4. **Change Manager → Stakeholder Engagement Lead**: Coordinates training rollout with stakeholders

### Release Handoffs
1. **Quality Assurance Lead → Project Manager**: Confirms release readiness
2. **Change Manager → Product Manager**: Reports adoption readiness
3. **Project Manager → Project Sponsor**: Requests final approval for release
4. **Stakeholder Engagement Lead → Project Sponsor**: Reports stakeholder readiness

---

## How New Personas Improve Project Outcomes

### Enhanced Clarity and Accountability
- **Project Sponsor** provides clear strategic direction and decision authority, eliminating ambiguity about priorities and resource allocation
- **Quality Assurance Lead** centralizes quality ownership, preventing defects from slipping through due to unclear testing responsibilities
- **Data Steward** ensures data-related tasks have a clear owner, reducing data quality issues and compliance risks

### Improved Project Success Rates
- **Stakeholder Engagement Lead** prevents late-stage stakeholder misalignment that often derails projects or requires expensive rework
- **Change Manager** increases adoption rates, ensuring delivered features actually create the intended business value
- **Project Sponsor** removes organizational barriers faster, preventing delays and keeping projects on track

### Better Risk Management
- **Quality Assurance Lead** identifies quality risks early when they're cheaper to fix
- **Data Steward** proactively addresses data compliance and security risks
- **Change Manager** anticipates and mitigates adoption resistance before it becomes a project risk

### Stronger Cross-Team Collaboration
- Clear handoff points between roles (outlined above) reduce miscommunication and rework
- Explicit interaction points ensure all roles know when and how to collaborate
- Distributed responsibilities prevent bottlenecks on individual contributors

### Example Scenario: E-commerce Platform Migration

**Without New Roles**: A team launches a new e-commerce platform with technical success but faces low adoption due to poor user preparation, data quality issues in migrated customer records, and stakeholder concerns that weren't addressed earlier.

**With New Roles**:
- **Stakeholder Engagement Lead** identifies concerns from the sales team early, allowing Product Manager to address them in sprint planning
- **Change Manager** delivers training videos and documentation, achieving 80% user readiness before launch
- **Data Steward** validates migrated customer data, catching and fixing 15,000 duplicate records before go-live
- **Quality Assurance Lead** runs end-to-end transaction tests, finding a payment gateway edge case missed by unit tests
- **Project Sponsor** removes a legal blocker on payment processing by escalating to the General Counsel

**Result**: On-time launch with 85% adoption in first month, zero data incidents, and high stakeholder satisfaction.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

