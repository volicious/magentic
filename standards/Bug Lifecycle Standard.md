# Bug Lifecycle Standard

## Purpose

The Bug Lifecycle defines how software defects progress from initial report through final closure.

It establishes ownership, responsibilities, required artifacts, transition criteria, and service level objectives (SLOs) for every lifecycle state.

The objective is to provide a consistent, transparent process for managing defects across Product Management, Business Analysis, Engineering, QA, and Operations.

---

# Guiding Principles

- Every defect has a single owner at any point in time.
- Every lifecycle state has clearly defined exit criteria.
- Ownership transfers explicitly.
- Decisions are documented.
- Defects are validated before closure.
- Service Level Objectives help prioritize organizational responsiveness but do not replace Product Manager prioritization.

---

# Bug Lifecycle

New

↓

Triaged

↓

Needs Information

↓

Ready for Engineering

↓

In Development

↓

Ready for QA

↓

In Validation

↓

Accepted

↓

Closed

---

# Lifecycle Status Definitions

## New

**Owner:** Business Analyst

### Purpose

A defect has been reported but has not yet been investigated.

### Required Information

- Reporter
- Summary
- Initial description

### Exit Criteria

- Initial review completed
- Assigned to a Business Analyst

---

## Triaged

**Owner:** Business Analyst

### Purpose

Determine whether the issue is understood well enough for Product Management to prioritize.

### Required Information

- Expected behavior
- Actual behavior
- Reproduction steps
- Environment
- Business impact
- Severity
- Classification
- Supporting evidence

### Exit Criteria

- Product Manager has enough information to assign priority.

---

## Needs Information

**Owner:** Business Analyst

### Purpose

Additional information is required before the defect can proceed.

Examples include:

- Unable to reproduce
- Missing logs
- Missing screenshots
- Missing business context
- Missing reproduction steps

### Exit Criteria

Outstanding information has been received or the issue has been determined to be invalid.

---

## Ready for Engineering

**Owner:** Engineering

### Purpose

Engineering has sufficient information to begin investigation.

### Required Information

- Complete defect report
- Priority assigned
- Supporting evidence
- Reproduction steps
- Business impact

### Exit Criteria

Engineering begins investigation.

---

## In Development

**Owner:** Engineering

### Purpose

Engineering is investigating and implementing a solution.

### Exit Criteria

- Code complete
- Peer review complete (if applicable)
- Ready for QA

---

## Ready for QA

**Owner:** QA

### Purpose

Engineering believes the defect has been resolved.

### Required Information

- Deployable build
- Root cause documented (when applicable)
- Release notes updated (when applicable)

### Exit Criteria

QA begins validation.

---

## In Validation

**Owner:** QA

### Purpose

QA validates that the defect has been resolved.

Validation includes:

- Original defect resolved
- No regressions introduced
- Acceptance criteria satisfied

### Exit Criteria

QA approves the fix.

---

## Accepted

**Owner:** Product Manager

### Purpose

Business confirms that the implemented solution satisfies the intended outcome.

### Exit Criteria

Business acceptance received.

---

## Closed

**Owner:** Business Analyst

### Purpose

Administrative closure of the defect.

Activities include:

- Updating documentation
- Updating traceability
- Recording lessons learned (when applicable)
- Closing related work items

---

# Ownership Matrix

| Lifecycle State | Primary Owner |
|-----------------|---------------|
| New | Business Analyst |
| Triaged | Business Analyst |
| Needs Information | Business Analyst |
| Ready for Engineering | Engineering |
| In Development | Engineering |
| Ready for QA | QA |
| In Validation | QA |
| Accepted | Product Manager |
| Closed | Business Analyst |

---

# Bug Service Level Objectives (SLOs)

Service Level Objectives establish target response times for handling defects.

These objectives measure organizational responsiveness and help identify process bottlenecks.

SLOs are organizational goals—not contractual commitments.

| Severity | Time to Triage | Time to Start | Target Resolution |
|----------|----------------|---------------|-------------------|
| Critical | 1 hour | 2 hours | 24 hours |
| High | 4 hours | 1 Business Day | 3 Business Days |
| Medium | 1 Business Day | 3 Business Days | Next Planned Release |
| Low | 3 Business Days | Product Manager Discretion | Product Manager Discretion |

---

## SLO Definitions

### Time to Triage

Measured from:

Defect Reported

↓

Business Analyst completes triage.

---

### Time to Start

Measured from:

Ready for Engineering

↓

Engineering begins investigation.

---

### Target Resolution

Measured from:

Engineering begins investigation

↓

Fix is completed and ready for QA validation.

---

## SLO Exceptions

SLOs may be exceeded when:

- Required information is unavailable.
- Third-party vendors block progress.
- Product Manager approves deferral.
- Executive leadership reprioritizes work.
- Business accepts an interim workaround.

Exceptions should be documented.

---

## Escalation

Immediately escalate defects when:

- No viable workaround exists.
- Customer-facing functionality is unavailable.
- Revenue generation is impacted.
- Data loss or corruption occurs.
- Security vulnerabilities are identified.
- Regulatory or compliance obligations are affected.
- A Critical or High severity defect is at risk of missing its SLO.

Escalations should include:

- Current status
- Business impact
- Blocking issues
- Required decisions
- Recommended next steps

---

# Transition Criteria

A defect may advance only when:

- Required documentation is complete.
- Exit criteria have been satisfied.
- Ownership has been transferred.
- Required approvals have been received.

---

# Reopening Defects

Closed defects may be reopened when:

- The original issue still exists.
- A regression has been introduced.
- The implemented solution does not satisfy the approved requirements.
- New evidence materially changes the understanding of the defect.

Unless otherwise directed, reopened defects return to:

**Triaged**

---

# Operational Metrics

Organizations should monitor:

- Time to Triage
- Time to Start
- Time to Resolution
- Time in QA
- Time to Closure
- Reopen Rate
- Defect Escape Rate
- Defects by Severity
- Defects by Classification
- Defects by Product Area
- Percentage of SLOs Met

These metrics should be reviewed regularly to identify trends and opportunities for continuous improvement.

---

# Continuous Improvement

Following closure, evaluate:

- Could Discovery have prevented the defect?
- Were requirements incomplete or ambiguous?
- Were business rules misunderstood?
- Were edge cases overlooked?
- Were standards followed?
- Should organizational standards be updated?
- Should templates or checklists be improved?

Capture lessons learned and incorporate them into future discovery, requirements, and testing practices.

---

# Guiding Principle

A defect is not complete simply because code has changed.

A defect is complete when:

- The problem is understood.
- The business impact has been assessed.
- The solution has been implemented.
- The fix has been validated.
- The business has accepted the outcome.
- Documentation accurately reflects the implemented behavior.

The Bug Lifecycle exists to ensure defects move through the organization predictably, transparently, and with clear ownership at every stage.