# Bug Analysis Framework

## Purpose

The Bug Analysis Framework defines the standard methodology for investigating, documenting, analyzing, and communicating software defects.

The objective of bug analysis is to eliminate uncertainty by ensuring Product Management, Engineering, QA, and stakeholders have sufficient information to understand the problem before discussing potential solutions.

The Business Analyst investigates defects, gathers evidence, assesses business impact, and documents findings.

The Business Analyst does not determine technical root causes or implementation solutions.

---

# Guiding Principles

## Investigate Before Concluding

Understand the problem before discussing solutions.

Gather evidence.

Validate observations.

Avoid speculation.

---

## Describe Behavior

Document:

- Expected behavior
- Actual behavior

Do not prescribe implementation.

---

## Separate Facts from Assumptions

Clearly distinguish:

- Facts
- Assumptions
- Suspected causes
- Engineering conclusions

---

## Business Impact Drives Priority

Technical severity alone does not determine priority.

Understand:

- Customer impact
- Operational impact
- Revenue impact
- Regulatory impact

---

## Workarounds Matter

Every investigation should determine:

- Current workaround
- Potential workaround
- Business acceptability
- Operational limitations
- Risks introduced
- Validation status

---

# Investigation Lifecycle

## Phase 1 — Intake

Capture:

- Summary
- Reporter
- Date reported
- Environment
- Product Version
- Related Feature
- Related User Story

Deliverable:

Initial Defect Record

---

## Phase 2 — Problem Definition

Document:

- Business Objective
- Expected Behavior
- Actual Behavior
- Affected Workflow

Deliverable:

Problem Statement

---

## Phase 3 — Reproduction

Attempt reproduction.

Document:

- Steps
- Preconditions
- Test Data
- Frequency
- Timing
- Environment

Status:

- Reproduced
- Partially Reproduced
- Unable to Reproduce

Deliverable:

Reproduction Record

---

## Phase 4 — Business Impact Analysis

Identify:

- Affected Users
- Customer Impact
- Operational Impact
- Financial Impact
- Compliance Impact

Deliverable:

Business Impact Assessment

---

## Phase 5 — Classification

Document:

- Classification
- Severity
- Business Impact
- Supporting Evidence

Do not assign Priority.

Priority belongs to the Product Manager.

Deliverable:

Defect Classification

---

## Phase 6 — Workaround Analysis

Document:

- Current Workaround
- Potential Workaround
- Validation Status
- Risks Introduced

---

## Phase 7 — Root Cause Status

Engineering owns root cause analysis.

The Business Analyst records:

- Unknown
- Under Investigation
- Identified
- Confirmed
- Resolved

---

## Phase 8 — Evidence Collection

Collect:

- Screenshots
- Videos
- Logs
- Error Messages
- API Responses
- Payloads
- Related Tickets

Deliverable:

Evidence Package

---

# Defect Report

Every defect should contain:

- Summary
- Business Objective
- Expected Behavior
- Actual Behavior
- Reproduction Steps
- Environment
- Classification
- Severity
- Business Impact
- Current Workaround
- Potential Workaround
- Risks
- Dependencies
- Root Cause Status
- Supporting Evidence
- Decision Log

---

# Defect Triage Matrix

| Attribute | Owner | Purpose |
|-----------|-------|----------|
| Business Impact | Business Analyst | Describe business consequences |
| Severity | Business Analyst / QA | Describe technical seriousness |
| Priority | Product Manager | Determine implementation order |
| Root Cause | Engineering | Explain why the defect occurred |

---

# Quality Checklist

Before escalating:

- Business objective understood
- Expected behavior documented
- Actual behavior documented
- Reproduction steps complete
- Environment documented
- Business impact documented
- Severity assigned
- Evidence attached
- Workarounds documented
- Risks documented
- Dependencies documented

---

# Anti-Patterns

Avoid:

- Suggesting implementation fixes
- Assuming root cause
- Confusing Severity with Priority
- Confusing Business Impact with Severity
- Escalating without evidence
- Omitting reproduction steps
- Ignoring intermittent behavior

---

# Guiding Principle

Engineering should spend their time solving problems—not trying to understand what the problem is.