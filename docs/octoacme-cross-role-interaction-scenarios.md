# OctoAcme — Cross-Role Interaction Scenarios

## Purpose
Provide practical examples of how different roles collaborate throughout the project lifecycle. These scenarios illustrate communication patterns, decision-making, and problem-solving across roles.

---

## Scenario 1: New Feature Development

### Situation
A customer-requested feature needs to be evaluated, designed, and delivered.

### Role Flow and Interactions

**1. Initial Discovery (Product Manager + Support Engineer)**
- Support Engineer reports trend of customer requests for feature X
- Product Manager reviews support data and customer feedback
- PM schedules stakeholder interviews to validate need
- **Output:** Feature proposal added to backlog

**2. Requirements Definition (Product Manager + Business Analyst)**
- Business Analyst conducts requirements workshops with stakeholders
- BA documents detailed requirements, process flows, and business rules
- Product Manager reviews and prioritizes against roadmap
- **Output:** Requirements document with acceptance criteria

**3. Design Phase (UX Designer + Business Analyst + Developer)**
- UX Designer reviews requirements and creates wireframes
- BA validates designs meet business requirements
- Developer provides feedback on technical feasibility
- UX Designer iterates based on feedback
- **Output:** Approved design specifications

**4. Planning (Project Manager + All Roles)**
- Project Manager facilitates planning meeting
- Developer provides effort estimates
- QA Engineer defines test strategy
- DevOps Engineer identifies infrastructure needs
- **Output:** Sprint plan with assigned work

**5. Implementation (Developer + UX Designer + QA Engineer)**
- Developer implements feature following design specs
- UX Designer reviews implementation for design compliance
- Developer writes unit tests
- QA Engineer prepares test cases
- **Output:** Feature implementation ready for QA

**6. Testing (QA Engineer + Developer)**
- QA Engineer executes test plan
- Issues are logged and assigned to Developer
- Developer fixes bugs and requests re-verification
- **Output:** Feature verified and approved

**7. Deployment (DevOps Engineer + Developer + QA Engineer)**
- DevOps Engineer prepares deployment pipeline
- Developer provides deployment instructions
- QA Engineer verifies in staging environment
- DevOps Engineer deploys to production
- **Output:** Feature live in production

**8. Support Handoff (All Roles → Support Engineer)**
- Product Manager provides feature description for release notes
- Developer documents technical details and troubleshooting steps
- Support Engineer updates knowledge base
- Training session held for support team
- **Output:** Support team ready to assist customers

**9. Post-Launch (Support Engineer → Product Manager)**
- Support Engineer monitors customer feedback and issues
- Trend reports shared with Product Manager
- Product Manager evaluates success against metrics
- **Output:** Insights for future iterations

---

## Scenario 2: Production Incident Response

### Situation
A critical bug is discovered in production affecting multiple users.

### Role Flow and Interactions

**1. Incident Detection (DevOps Engineer or Support Engineer)**
- Monitoring alerts trigger or customers report issue
- Support Engineer or DevOps Engineer confirms impact
- Incident declared and on-call notified
- **Output:** Incident ticket created with severity level

**2. Initial Triage (DevOps Engineer + Developer + Support Engineer)**
- DevOps Engineer checks system logs and metrics
- Developer reviews recent changes and code
- Support Engineer provides user impact details
- Root cause hypothesis formed
- **Output:** Initial assessment and mitigation plan

**3. Communication (Project Manager + Product Manager)**
- Project Manager activates incident communication plan
- Product Manager assesses customer impact
- Status updates provided to stakeholders
- **Output:** Stakeholders informed of situation and ETA

**4. Resolution (Developer + DevOps Engineer)**
- Developer implements fix or hotfix
- DevOps Engineer tests in staging
- Fix deployed to production
- Monitoring confirms resolution
- **Output:** Issue resolved

**5. Verification (QA Engineer + Support Engineer)**
- QA Engineer verifies fix in production
- Support Engineer confirms with affected customers
- **Output:** Resolution confirmed

**6. Post-Incident Review (All Roles)**
- Project Manager facilitates blameless postmortem
- Root cause, timeline, and response documented
- Action items identified to prevent recurrence
- **Output:** Postmortem report and improvement backlog

---

## Scenario 3: Requirements Clarification During Development

### Situation
A developer encounters ambiguous requirements while implementing a feature.

### Role Flow and Interactions

**1. Developer Identifies Issue**
- Developer finds acceptance criteria unclear or contradictory
- Developer reviews existing documentation and designs
- Issue still unclear after review

**2. Developer → Business Analyst or Product Manager**
- Developer documents specific questions with context
- Posts question in ticket or team chat
- Business Analyst or PM responds with clarification
- **Output:** Requirements clarified inline

**3. If Design Impact (UX Designer involved)**
- Business Analyst determines design changes needed
- UX Designer creates updated mockup or specification
- Developer reviews and confirms understanding
- **Output:** Updated design approved

**4. If Scope Impact (Project Manager involved)**
- Clarification reveals scope creep or new requirement
- Developer raises concern to Project Manager
- PM evaluates impact on timeline and resources
- PM facilitates decision with Product Manager
- **Output:** Scope adjusted or requirement deferred

**Best Practice:** Encourage developers to ask questions early to avoid rework.

---

## Scenario 4: Infrastructure Scaling Need

### Situation
Performance metrics indicate need for infrastructure upgrades.

### Role Flow and Interactions

**1. Performance Issue Detected (DevOps Engineer or Developer)**
- Monitoring shows degraded performance
- DevOps Engineer analyzes metrics and logs
- Scaling need identified

**2. Impact Assessment (DevOps Engineer + Product Manager + Project Manager)**
- DevOps Engineer estimates performance improvement and cost
- Product Manager evaluates customer impact
- Project Manager assesses timeline and resource availability
- **Output:** Recommendation to proceed or defer

**3. Planning (DevOps Engineer + Developer)**
- DevOps Engineer designs scaling solution
- Developer reviews for application changes needed
- Migration or deployment plan created
- **Output:** Implementation plan approved

**4. Implementation (DevOps Engineer + QA Engineer)**
- DevOps Engineer implements infrastructure changes
- QA Engineer validates performance improvements
- Load testing conducted
- **Output:** Infrastructure scaled and validated

**5. Monitoring (DevOps Engineer + Support Engineer)**
- DevOps Engineer monitors post-deployment metrics
- Support Engineer tracks any customer-reported issues
- Success metrics reported to stakeholders
- **Output:** Scaling successful

---

## Scenario 5: User Feedback Driving Design Changes

### Situation
User research reveals usability issues with an existing feature.

### Role Flow and Interactions

**1. Feedback Collection (UX Designer or Support Engineer)**
- UX Designer conducts usability study, OR
- Support Engineer aggregates customer complaints
- Issues documented with user quotes and data

**2. Analysis (UX Designer + Product Manager)**
- UX Designer synthesizes findings
- Product Manager evaluates business impact
- Decision made to redesign feature

**3. Design Iteration (UX Designer + Business Analyst)**
- UX Designer creates improved design
- Business Analyst validates against requirements
- Alternative solutions explored
- **Output:** New design proposal

**4. Validation (UX Designer + Product Manager + QA Engineer)**
- UX Designer tests new design with users
- Product Manager approves based on feedback
- QA Engineer reviews for testability
- **Output:** Design approved for development

**5. Implementation (Standard feature flow)**
- Follows Scenario 1 feature development process
- Emphasis on QA validation of usability improvements

---

## Scenario 6: Release Planning and Coordination

### Situation
Preparing for a major release with multiple features and teams.

### Role Flow and Interactions

**1. Release Kickoff (Project Manager + Product Manager)**
- Product Manager defines release goals and features
- Project Manager creates release timeline
- Stakeholders identified and notified

**2. Readiness Assessment (All Roles)**
- Developer confirms feature completion
- QA Engineer confirms test coverage and pass rate
- UX Designer confirms design implementation
- DevOps Engineer confirms infrastructure readiness
- Support Engineer confirms documentation and training complete
- Business Analyst confirms requirements validated
- **Output:** Release readiness report

**3. Pre-Release (DevOps Engineer + Project Manager)**
- DevOps Engineer deploys to staging
- Project Manager coordinates final stakeholder review
- QA Engineer executes smoke tests
- Go/no-go decision made

**4. Release Execution (DevOps Engineer + All Roles)**
- DevOps Engineer executes deployment
- Project Manager monitors progress
- Support Engineer on standby
- Developer available for issues

**5. Post-Release (Support Engineer + Product Manager)**
- Support Engineer monitors customer feedback
- Product Manager tracks success metrics
- Team retrospective scheduled
- **Output:** Release completed, learnings captured

---

## Communication Best Practices

### For All Roles

1. **Be Proactive:** Don't wait for others to ask. Share status and blockers early.
2. **Use Written Communication:** Document decisions and context in shared tools.
3. **Respond Promptly:** Delays in one role impact the entire team.
4. **Ask Questions:** Better to clarify than to assume.
5. **Show Respect:** Everyone's role is critical to project success.

### For Project Managers

- Facilitate introductions between roles
- Create communication channels for specific workstreams
- Document decision-making frameworks
- Escalate blockers that span multiple roles

### For Product Managers

- Ensure requirements are clear before handoff
- Make prioritization decisions transparently
- Provide context on business value and customer impact
- Be available for clarification questions

### Tools and Channels

- **Synchronous:** Standups, planning meetings, quick syncs
- **Asynchronous:** Tickets, documentation, status updates
- **Escalation:** Defined paths for urgent issues
- **Knowledge Sharing:** Wikis, retrospectives, brown bags
