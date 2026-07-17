# Discovery Framework

## Purpose

The Discovery Framework defines the standard methodology for understanding business problems and transforming them into complete, implementation-ready requirements.

The purpose of discovery is not simply to gather information—it is to build a shared understanding of the business problem before proposing or documenting solutions.

Successful discovery reduces ambiguity, identifies risks early, uncovers hidden business rules, and enables informed decision making across Product Management, Engineering, QA, and other stakeholders.

---

# Guiding Principles

Discovery should always:

- Understand the problem before discussing solutions.
- Seek facts before opinions.
- Separate facts from assumptions.
- Challenge assumptions respectfully.
- Reduce ambiguity.
- Identify business rules.
- Discover risks early.
- Validate understanding continuously.
- Document decisions rather than make them.
- Recognize that discovery is iterative.

Discovery is complete only when the team understands the business problem well enough to produce implementation-ready requirements.

---

# Discovery Mindset

The Business Analyst is an objective investigator.

During discovery the Business Analyst should:

- Be curious.
- Listen more than they speak.
- Ask follow-up questions.
- Avoid leading stakeholders toward predetermined solutions.
- Challenge assumptions professionally.
- Seek evidence rather than opinions.
- Remain neutral when multiple solutions exist.

The objective is understanding—not agreement.

---

# Discovery Lifecycle

Discovery is an iterative process.

New information may require revisiting previous phases.

The Business Analyst should continue refining understanding until the Definition of Ready can be satisfied.

---

# Phase 1 — Problem Discovery

Objective:

Understand the underlying business problem.

Questions include:

- What problem are we trying to solve?
- Why does this problem exist?
- What business value will solving it provide?
- Who identified the problem?
- What happens if nothing changes?
- Are we solving the root cause or only a symptom?

Deliverables:

- Problem Statement
- Business Objective
- Success Metrics

---

# Phase 2 — Stakeholder Discovery

Objective:

Identify everyone affected by the problem or solution.

Discover:

- Business owner
- Product owner
- Subject matter experts
- Primary users
- Secondary users
- Administrators
- Support teams
- Decision makers

Questions:

Who performs the work?

Who approves it?

Who supports it?

Who maintains it?

Who is impacted?

Deliverables:

- Stakeholder Map
- Decision Owner List

---

# Phase 3 — Current State Discovery

Objective:

Understand how the process works today.

Document:

- Current workflow
- Existing systems
- Manual activities
- Pain points
- Bottlenecks
- Existing workarounds
- Existing reports

Questions:

What works well?

What doesn't?

Where do failures occur?

Deliverables:

- Current State Workflow
- Pain Point Analysis

---

# Phase 4 — Future State Discovery

Objective:

Understand the desired outcome.

Document:

- Desired workflow
- Desired automation
- Desired user experience
- Expected business outcomes

Questions:

What should success look like?

What should change?

What should remain unchanged?

Deliverables:

- Future State Workflow

---

# Phase 5 — Business Rule Discovery

Objective:

Identify every business rule that governs behavior.

Examples:

Who can...

When can...

Under what conditions...

What exceptions exist...

Every business rule should include:

- Rule
- Owner
- Source
- Exceptions

Deliverables:

- Business Rule Catalog

---

# Phase 6 — Data Discovery

Objective:

Understand the information being managed.

Discover:

- Inputs
- Outputs
- Required fields
- Optional fields
- Validation rules
- Ownership
- Retention
- Data sensitivity

Deliverables:

- Data Requirements

---

# Phase 7 — Workflow Discovery

Every workflow should document:

- Normal flow
- Alternate flow
- Error flow
- Exception flow

Questions:

What happens next?

What if this fails?

Can the user recover?

Deliverables:

- Workflow Diagrams

---

# Phase 8 — Integration Discovery

Document:

- Systems involved
- APIs
- File exchanges
- Authentication
- Timing
- Retry behavior
- Failure handling
- Monitoring

Deliverables:

- Integration Requirements

---

# Phase 9 — Security Discovery

Discover:

- Authentication
- Authorization
- Permissions
- Audit requirements
- Compliance
- Sensitive information

Deliverables:

- Security Requirements

---

# Phase 10 — Reporting Discovery

Identify:

- Reports
- Dashboards
- KPIs
- Exports
- Audit reporting

Deliverables:

- Reporting Requirements

---

# Phase 11 — Risk Discovery

Identify:

- Business risks
- Operational risks
- Technical risks
- Vendor risks
- Security risks
- Compliance risks

Each risk should include:

- Description
- Likelihood
- Impact
- Mitigation
- Owner

Deliverables:

- Risk Register

---

# Phase 12 — Dependency Discovery

Identify:

- Business dependencies
- Technical dependencies
- Third-party dependencies
- Vendor dependencies
- Data dependencies

Deliverables:

- Dependency Register

---

# Phase 13 — Edge Case Discovery

Review:

- Missing data
- Invalid data
- Duplicate records
- Deleted records
- Concurrent updates
- Permission failures
- Timeouts
- Network failures
- Browser refresh
- Session expiration
- Imports
- Exports
- Large datasets
- Time zones
- Offline behavior

Deliverables:

- Edge Case Analysis

---

# Phase 14 — Decision Discovery

Identify:

- Decisions already made
- Decisions still required
- Decision owner
- Decision deadline
- Alternatives considered

Deliverables:

- Decision Log

---

# Phase 15 — Validation

Validate:

- Business objectives
- Requirements
- Business rules
- Workflows
- Risks
- Assumptions
- Dependencies
- Stakeholder agreement

Discovery is complete only when stakeholders agree the documented understanding accurately reflects the business need.

Deliverables:

- Validated Requirements
- Updated Decision Log
- Definition of Ready Assessment

---

# Discovery Outputs

A completed discovery effort should produce, as appropriate:

- Problem Statement
- Business Objectives
- Stakeholder Map
- Current State Analysis
- Future State Analysis
- Business Rule Catalog
- Functional Requirements
- Non-functional Requirements
- Data Requirements
- Workflow Diagrams
- Integration Requirements
- Security Requirements
- Reporting Requirements
- Risk Register
- Dependency Register
- Decision Log
- User Stories
- Acceptance Criteria
- Traceability Matrix
- Open Question Log

---

# Discovery Anti-Patterns

Avoid the following:

- Jumping to solutions before understanding the problem.
- Treating assumptions as facts.
- Asking leading questions that bias stakeholder responses.
- Ignoring edge cases because they are uncommon.
- Documenting requests without understanding the business objective.
- Accepting "that's how we've always done it" as sufficient justification.
- Ending discovery with unresolved decision ownership.
- Writing requirements before validating stakeholder understanding.
- Allowing one stakeholder to speak for all affected users without validation.
- Stopping discovery after the first acceptable answer instead of probing for underlying causes.

---

# Discovery Quality Checklist

Before concluding discovery, verify:

- Is the business problem clearly understood?
- Have all relevant stakeholders been identified?
- Have current and future state workflows been documented?
- Have business rules been captured?
- Have assumptions been identified separately from facts?
- Have risks been documented?
- Have dependencies been documented?
- Have integrations been identified?
- Have reporting requirements been documented?
- Have security requirements been considered?
- Have edge cases been explored?
- Are remaining open questions assigned to an owner?
- Is every significant decision documented with an owner?
- Can Product Management confidently make product decisions?
- Can Engineering estimate and implement the work?
- Can QA derive meaningful test cases?
- Does the work satisfy the Definition of Ready?

---

# Continuous Improvement

After each completed feature, review the discovery process.

Identify:

- Which questions should have been asked earlier?
- Which assumptions proved incorrect?
- Which business rules were missed?
- Which stakeholders should have been involved sooner?
- Which risks materialized unexpectedly?
- Which defects originated from incomplete discovery?
- How should the Discovery Framework be improved?

The Discovery Framework is a living standard and should evolve as new lessons are learned.