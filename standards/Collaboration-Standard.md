# Collaboration Standard

## Purpose

The Collaboration Framework establishes the standard operating model for how roles collaborate throughout the product lifecycle.

Its purpose is to:

- Define how work moves between roles.
- Clarify ownership and accountability.
- Standardize collaboration across departments.
- Improve communication quality.
- Reduce ambiguity.
- Prevent duplicate work.
- Ensure decisions are made by the appropriate authority.
- Produce higher-quality outcomes through structured collaboration.

Collaboration exists to improve decision quality—not to distribute decision ownership.

---

# Guiding Principles

## Principle 1 — Collaborate Through Artifacts

Collaboration should occur through well-defined artifacts rather than assumptions, verbal agreements, or undocumented conversations.

Examples include:

- Product Vision
- Features
- Feature Specifications
- Requirements
- Business Rules
- User Stories
- Acceptance Criteria
- Technical Designs
- Test Cases
- Bug Reports
- Risk Registers
- Release Notes

Artifacts are the organization's shared language.

---

## Principle 2 — Respect Decision Authority

Every role contributes expertise.

Every role has defined decision authority.

Recommendations do not replace decisions.

Decision ownership remains with the designated role defined in the Decision Authority Standard.

---

## Principle 3 — Improve the Work

Each role is responsible for improving artifacts before handing them to the next role.

Artifacts should become:

- More complete
- More accurate
- Less ambiguous
- More testable
- Better documented

No role should simply forward incomplete work.

---

## Principle 4 — Challenge Ideas, Not People

Constructive disagreement improves products.

Roles should respectfully challenge:

- Assumptions
- Risks
- Requirements
- Scope
- Architecture
- Testability
- Operational readiness

Challenges should focus on improving the work—not assigning blame.

---

## Principle 5 — One Owner, Many Contributors

Every artifact has one owner.

Many roles may contribute.

The owner remains accountable for:

- Quality
- Completeness
- Accuracy
- Currency

---

## Principle 6 — Decisions Are Informed by Collaboration

Collaboration exists to provide information to the decision owner.

Collaboration does not replace accountability.

---

# Collaboration Levels

Every collaboration should occur at one of the following levels.

---

## Inform

Purpose:

Share information.

No response or approval required.

Examples:

- Release completed
- Documentation updated
- Bug resolved

---

## Consult

Purpose:

Obtain expertise before making a decision.

The consulted role provides information but does not make the decision.

Examples:

- Ask QA about testability.
- Ask Architecture about feasibility.
- Ask Security about compliance.

---

## Review

Purpose:

Evaluate work against organizational standards.

The reviewing role identifies improvements.

The owner remains responsible for updating the artifact.

Examples:

- Story review
- Architecture review
- Documentation review

---

## Recommend

Purpose:

Provide professional guidance to the decision owner.

Recommendations should include:

- Supporting evidence
- Risks
- Alternatives
- Rationale

The decision owner determines the outcome.

---

## Approve

Purpose:

Exercise formal decision authority.

Only the designated decision owner may approve.

Approval should be documented.

---

# Collaboration Contracts

Collaboration contracts define the expectations between roles.

---

## Chief Product Officer ↔ Product Manager

### Purpose

Translate organizational strategy into executable product direction.

### Chief Product Officer Provides

- Product Vision
- Strategic Direction
- Business Outcomes
- Investment Priorities

### Product Manager Provides

- Product Roadmap
- Initiative Planning
- Product Backlog
- Product Status

### Shared Responsibility

Maintain alignment between strategy and execution.

---

## Product Manager ↔ Business Analyst

### Purpose

Transform Features into implementation-ready requirements.

### Product Manager Provides

- Feature Definition
- Scope
- Priority
- Business Decisions
- Success Criteria

### Business Analyst Provides

- Discovery
- Requirements
- Business Rules
- User Stories
- Acceptance Criteria
- Risks
- Dependencies

### Shared Responsibility

Maintain a complete and accurate understanding of expected business behavior.

---

## Business Analyst ↔ UX Designer

### Purpose

Ensure workflows satisfy both business and user needs.

### Business Analyst Provides

- Business Processes
- User Requirements
- Business Rules

### UX Designer Provides

- User Flows
- Wireframes
- Interaction Design

### Shared Responsibility

Produce an intuitive user experience that satisfies business objectives.

---

## Business Analyst ↔ Software Architect

### Purpose

Validate technical feasibility.

### Business Analyst Provides

- Requirements
- Constraints
- Business Rules
- Acceptance Criteria

### Software Architect Provides

- Technical Feasibility
- Architectural Risks
- Design Guidance

### Shared Responsibility

Ensure business requirements are technically achievable.

---

## Software Architect ↔ Software Engineer

### Purpose

Transform architecture into implementation.

### Software Architect Provides

- Technical Design
- Standards
- Architectural Guidance

### Software Engineer Provides

- Implementation
- Technical Feedback
- Code Quality

### Shared Responsibility

Maintain architectural integrity.

---

## Business Analyst ↔ QA Engineer

### Purpose

Ensure requirements are testable.

### Business Analyst Provides

- User Stories
- Acceptance Criteria
- Business Rules

### QA Engineer Provides

- Test Strategy
- Test Cases
- Coverage Analysis
- Testability Feedback

### Shared Responsibility

Ensure expected behavior can be objectively verified.

---

## Software Engineer ↔ QA Engineer

### Purpose

Validate implementation quality.

### Software Engineer Provides

- Completed Implementation
- Technical Notes

### QA Engineer Provides

- Validation Results
- Defect Reports
- Regression Results

### Shared Responsibility

Deliver production-ready software.

---

## QA Engineer ↔ Release Manager

### Purpose

Confirm release readiness.

### QA Engineer Provides

- Test Summary
- Known Issues
- Quality Assessment

### Release Manager Provides

- Release Planning
- Deployment Coordination
- Operational Readiness

### Shared Responsibility

Deliver stable software to production.

---

# Artifact Contracts

Every artifact has a producer, consumers, governing standards, and quality expectations.

---

## Feature

Producer:

Product Manager

Consumers:

- Business Analyst
- UX Designer
- Software Architect

Standards:

- Requirements Standards
- Definition of Ready

---

## Requirements

Producer:

Business Analyst

Consumers:

- Software Architect
- Engineering
- QA

Standards:

- Requirements Standards
- Documentation Standards

---

## User Story

Producer:

Business Analyst

Consumers:

- Engineering
- QA
- Product Manager

Standards:

- User Story Standards
- Definition of Ready

Traceability:

Feature

↓

User Story

↓

Acceptance Criteria

↓

Test Cases

---

## Technical Design

Producer:

Software Architect

Consumers:

- Engineering
- QA

Standards:

- Architecture Principles
- Security Standards

---

## Test Cases

Producer:

QA Engineer

Consumers:

- QA
- Engineering

Standards:

- Test Standards
- Definition of Done

---

## Release Notes

Producer:

Technical Writer

Consumers:

- Customers
- Operations
- Product Management

Standards:

- Documentation Standards

---

# Collaboration Failures

Collaboration occasionally breaks down.

The organization should recognize and resolve failures quickly.

---

## Missing Information

Symptoms:

- Required information unavailable.
- Artifact incomplete.
- Questions remain unanswered.

Resolution:

Return the artifact to its owner for refinement.

---

## Authority Conflict

Symptoms:

- Multiple roles attempt to make the same decision.
- Ownership unclear.

Resolution:

Consult the Decision Authority Standard.

---

## Quality Failure

Symptoms:

- Artifact does not satisfy organizational standards.
- Definition of Ready or Definition of Done not met.

Resolution:

Return the artifact for improvement.

---

## Scope Conflict

Symptoms:

- Scope changes after downstream work has begun.

Resolution:

Return the work to the Product Manager for evaluation and re-planning.

---

## Traceability Failure

Symptoms:

- Missing parent artifact.
- Broken relationships.
- Missing references.

Resolution:

Restore traceability before work proceeds.

---

## Communication Failure

Symptoms:

- Assumptions replace documented decisions.
- Stakeholders receive conflicting information.

Resolution:

Update the authoritative artifact and notify affected roles.

---

# Collaboration Review Checklist

Before handing work to another role, verify:

- Appropriate collaboration level identified.
- Artifact satisfies applicable standards.
- Artifact owner identified.
- Decision authority is clear.
- Required reviews completed.
- Risks documented.
- Dependencies documented.
- Open questions assigned.
- Traceability maintained.
- Definition of Ready or Definition of Done satisfied.

---

# Common Anti-Patterns

Avoid:

- Making decisions outside assigned authority.
- Collaborating through undocumented conversations.
- Skipping required reviews.
- Recreating artifacts owned by another role.
- Escalating questions instead of resolving them.
- Hiding risks or blockers.
- Assuming shared understanding.
- Treating collaboration as approval.
- Treating recommendations as decisions.

---

# Continuous Improvement

Following each major initiative or release, evaluate:

- Which collaboration patterns worked well?
- Where did communication break down?
- Which artifacts required excessive clarification?
- Which handoffs caused delays?
- Were responsibilities clearly understood?
- Were collaboration standards followed?
- Should collaboration contracts be updated?

Lessons learned should be incorporated into organizational standards and role playbooks.

---

# Guiding Principle

High-performing organizations collaborate through clearly defined artifacts, well-understood responsibilities, structured feedback, and explicit decision authority.

Every role contributes expertise.

Every artifact has one owner.

Every decision has one accountable decision maker.

The objective of collaboration is not consensus.

The objective is to ensure that every decision is informed by the right people, at the right time, using the right information.