# Risk Management Standard

## Purpose

This document establishes the organization's standard for identifying, assessing, documenting, communicating, mitigating, monitoring, and reviewing risks throughout the product lifecycle.

Risk management exists to reduce uncertainty before it becomes an issue.

The objective is not to eliminate all risk.

The objective is to ensure risks are identified early, understood, communicated, assigned clear ownership, and considered when making product and technical decisions.

Risk management is a shared organizational responsibility.

---

# Guiding Principles

## Principle 1 — Risk Exists Throughout the Product Lifecycle

Risk identification begins during Discovery and continues throughout planning, implementation, testing, release, and production.

Risk should be reassessed whenever significant information changes.

---

## Principle 2 — Risks Are Future Uncertainty

A risk is a potential future event.

An issue is an event that has already occurred.

An assumption is something believed to be true.

A dependency is something required for success.

These concepts should never be confused.

---

## Principle 3 — Every Risk Has One Owner

Every identified risk must have a single accountable owner.

The owner is responsible for:

- Monitoring
- Communicating
- Coordinating mitigation
- Reassessing

Ownership does not necessarily imply responsibility for implementation.

---

## Principle 4 — Decisions Should Consider Risk

Risks exist to inform decisions.

Risks should influence:

- Prioritization
- Scope
- Architecture
- Release planning
- Testing strategy
- Operational readiness

---

## Principle 5 — Accepted Risk Is Still Managed

Choosing to accept a risk is a decision—not the absence of one.

Accepted risks should remain documented, monitored, and periodically reviewed.

---

# Definitions

## Risk

A potential future event that could positively or negatively affect objectives.

---

## Issue

A problem that has already occurred.

---

## Assumption

Information believed to be true but not yet verified.

---

## Dependency

A relationship that must exist for successful completion of work.

---

## Mitigation

Actions intended to reduce likelihood or impact.

---

## Contingency

Actions performed if the risk becomes an issue.

---

## Trigger

An observable condition indicating that a risk is becoming more likely or has materialized.

---

# Risk Categories

Examples include:

- Business
- Product
- Requirements
- Technical
- Architecture
- Security
- Compliance
- Operational
- Infrastructure
- Vendor
- Data
- Integration
- Performance
- Scalability
- Financial
- Schedule
- Resource
- Customer Experience

A risk may belong to multiple categories.

---

# Risk Lifecycle

Identified

↓

Analyzed

↓

Mitigation Planned

↓

Monitoring

↓

Resolved

or

↓

Accepted

or

↓

Realized (Issue)

Risk status should be reviewed regularly.

---

# Risk Assessment

Every risk should include:

## Description

What uncertainty exists?

---

## Cause

Why might this occur?

---

## Consequence

What happens if it occurs?

---

## Likelihood

Suggested scale:

- Very Low
- Low
- Medium
- High
- Very High

---

## Impact

Suggested scale:

- Negligible
- Minor
- Moderate
- Major
- Critical

Impact should consider:

- Customers
- Revenue
- Operations
- Security
- Compliance
- Reputation

---

## Overall Risk Rating

Derived from:

Likelihood × Impact

Suggested values:

- Low
- Medium
- High
- Critical

---

## Risk Heat Matrix

| Likelihood ↓ / Impact → | Negligible | Minor | Moderate | Major | Critical |
|--------------------------|------------|--------|----------|-------|----------|
| **Very High** | Medium | High | High | Critical | Critical |
| **High** | Medium | Medium | High | High | Critical |
| **Medium** | Low | Medium | Medium | High | High |
| **Low** | Low | Low | Medium | Medium | High |
| **Very Low** | Low | Low | Low | Medium | Medium |

The Heat Matrix provides a consistent organizational approach for determining overall risk ratings.

---

# Risk Response Strategies

Typical strategies include:

## Avoid

Change plans to eliminate the risk.

---

## Reduce

Reduce likelihood or impact.

---

## Transfer

Transfer responsibility.

Examples:

- Vendor
- Insurance
- Contractual agreement

---

## Accept

Consciously accept the risk.

Document:

- Decision Owner
- Rationale
- Review Date

---

# Risk Register

Every initiative, epic, feature, or project should maintain a Risk Register.

Each risk should include:

- Risk ID
- Description
- Category
- Owner
- Likelihood
- Impact
- Overall Rating
- Mitigation Strategy
- Contingency Plan
- Trigger
- Status
- Date Identified
- Last Reviewed

---

# Organizational Ownership

| Risk Category | Typical Owner |
|---------------|---------------|
| Business | Product Manager |
| Product | Product Manager |
| Requirements | Business Analyst |
| Technical | Software Architect |
| Security | Security & Compliance Manager |
| Infrastructure | CIO |
| Cloud | Cloud Architect |
| Database | Database Engineer |
| Testing | QA Engineer |
| Release | Release Manager |
| Vendor | Product Manager or CIO |

Ownership may vary depending on organizational context.

---

# Risk Reviews

Review risks:

- During Discovery
- During Backlog Refinement
- Before Sprint Planning
- Before Development
- Before Release
- After Major Scope Changes
- After Production Incidents
- During Retrospectives

---

# Traceability

Risks should be traceable to related organizational artifacts.

Examples include:

Business Goal

↓

Initiative

↓

Epic

↓

Feature

↓

Requirement

↓

Risk

↓

Mitigation Requirement

↓

User Story

↓

Acceptance Criteria

↓

Test Cases

↓

Release

↓

Production

↓

Issue (if realized)

Every significant risk should identify:

- Related Business Goal
- Related Feature
- Related Requirements
- Related User Stories
- Related Test Cases
- Related Releases

Traceability improves:

- Impact Analysis
- Change Management
- Root Cause Analysis
- Lessons Learned

---

# Risk Review Checklist

Before approving work, verify:

✓ Risks identified

✓ Risks categorized

✓ Owners assigned

✓ Likelihood assessed

✓ Impact assessed

✓ Heat Matrix applied

✓ Mitigation documented

✓ Contingency documented

✓ Trigger identified

✓ Review date assigned

✓ Accepted risks documented

✓ Traceability maintained

---

# Common Anti-Patterns

Avoid:

- Treating issues as risks.
- Treating assumptions as risks.
- Risks without owners.
- Risks without mitigation.
- Risks reviewed only once.
- Ignoring accepted risks.
- Ignoring low-probability, high-impact risks.
- Removing risks after implementation without validation.
- Creating duplicate risks rather than updating existing ones.

---

# Continuous Improvement

Regularly review:

- Risks that became issues
- Frequently recurring risks
- Mitigations that proved ineffective
- Accepted risks that should have been avoided
- Missed opportunities to identify risks earlier

Update organizational standards and playbooks based on lessons learned.

---

# Guiding Principle

Risk management is not about predicting the future.

It is about making better decisions under uncertainty.

Well-managed risks improve planning, prioritization, architecture, implementation, testing, release quality, and operational readiness.

The organization's goal is not zero risk.

The goal is that every significant risk is understood, owned, communicated, traceable, and intentionally managed throughout the product lifecycle.