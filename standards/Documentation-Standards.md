# Documentation Standards

## Purpose

This document establishes the documentation standards for all artifacts produced within the organization.

The goals of these standards are to:

- Improve clarity
- Eliminate ambiguity
- Increase consistency
- Improve maintainability
- Reduce implementation risk
- Enable effective collaboration across all teams

These standards apply to all agents and all documentation unless a more specific standard overrides them.

---

# Core Principles

## Principle 1 — Clarity Over Brevity

Documentation should be easy to understand.

Never sacrifice clarity simply to make documentation shorter.

---

## Principle 2 — Write for the Reader

Documentation should be written for the intended audience.

Consider:

- Business stakeholders
- Product Management
- Engineering
- QA
- Operations
- Technical Writers

Use terminology appropriate for the audience.

---

## Principle 3 — One Source of Truth

Every fact should exist in one authoritative location.

Avoid duplicating information.

Reference existing documentation whenever possible.

---

## Principle 4 — Separate Facts from Opinions

Documentation should clearly distinguish:

- Facts
- Assumptions
- Recommendations
- Decisions
- Open Questions

Readers should never have to determine which statements have been verified.

---

## Principle 5 — Document Decisions

Whenever significant decisions are made, document:

- Decision
- Decision owner
- Decision date
- Alternatives considered
- Rationale
- Business impact

---

## Principle 6 — Be Complete

Incomplete documentation creates project risk.

If information is unknown, document that it is unknown.

Never silently omit information.

---

## Principle 7 — Be Traceable

Every artifact should be traceable to its source.

Examples:

Business Goal

↓

Initiative

↓

Epic

↓

Feature

↓

User Story

↓

Acceptance Criteria

↓

Test Case

↓

Release

---

# Writing Standards

## Use Clear Language

Prefer simple language.

Avoid unnecessary jargon.

Avoid vague wording.

Examples of vague words:

- Fast
- Easy
- User-friendly
- Flexible
- Robust
- Appropriate

Instead, describe measurable behavior.

---

## Use Active Voice

Prefer:

"The system sends an email."

Instead of:

"An email is sent."

---

## Be Specific

Instead of:

"The page loads quickly."

Write:

"The page loads within two seconds for 95% of users."

---

## Avoid Ambiguity

Avoid words such as:

- Usually
- Normally
- Sometimes
- Maybe
- Etc.
- And so on

Describe exact behavior whenever possible.

---

# Document Structure

Unless another template specifies otherwise, documents should contain appropriate sections from the following.

- Purpose
- Scope
- Business Objective
- Background
- Stakeholders
- Requirements
- Business Rules
- Workflows
- Assumptions
- Risks
- Dependencies
- Open Questions
- Decisions
- References

Only include sections that are applicable.

---

# Formatting Standards

## Headings

Use consistent heading hierarchy.

Example:

```
# Title

## Section

### Subsection
```

---

## Lists

Use bullet lists for:

- Requirements
- Rules
- Risks
- Dependencies
- Assumptions

Use numbered lists only when order matters.

---

## Tables

Use tables when comparing:

- Options
- Decisions
- Roles
- Permissions
- Responsibilities

---

## Emphasis

Use **bold** sparingly to highlight important concepts.

Avoid excessive emphasis.

---

# Requirement Language

Requirements should:

- Describe expected behavior.
- Be measurable.
- Be testable.
- Be implementation-independent.

Preferred wording:

"The system shall..."

or

"The application must..."

Avoid:

"The developer should..."

"The application might..."

---

# Business Rules

Business rules should:

- Be uniquely identifiable.
- Be reusable.
- Be independent of implementation.

Each business rule should include:

- Rule ID
- Description
- Owner
- Source
- Exceptions

---

# Assumptions

Assumptions should always include:

- Description
- Owner
- Validation status
- Impact if incorrect

Assumptions must never become requirements until validated.

---

# Risks

Every documented risk should include:

- Description
- Likelihood
- Impact
- Mitigation
- Owner

---

# Dependencies

Every dependency should include:

- Description
- Type
- Owner
- Blocking status
- Due date

---

# Open Questions

Open questions should include:

- Question
- Owner
- Date identified
- Current status

---

# Decision Log

Document decisions separately from requirements.

Each decision should include:

- Decision
- Owner
- Date
- Reasoning
- Alternatives considered

---

# Versioning

Significant documentation updates should record:

- Date
- Author
- Summary of changes

Documentation should evolve rather than be rewritten whenever possible.

---

# Cross References

Rather than duplicating information, reference existing documentation.

Example:

See:

- Definition of Ready
- Business Rule Catalog
- Risk Register

---

# Documentation Quality Checklist

Before publishing documentation, verify:

- Purpose is clear.
- Scope is defined.
- Audience is appropriate.
- Terminology is consistent.
- Requirements are testable.
- Risks are documented.
- Dependencies are documented.
- Assumptions are documented.
- Open questions are tracked.
- Decisions are documented.
- References are accurate.
- Formatting is consistent.
- No conflicting information exists.

---

# Documentation Principles for AI Agents

Every agent should strive to produce documentation that is:

- Accurate
- Complete
- Consistent
- Objective
- Traceable
- Testable
- Maintainable

When information is missing:

Ask.

When assumptions exist:

Document them.

When risks exist:

Highlight them.

When decisions are needed:

Identify the decision owner.

When ambiguity exists:

Reduce it before proceeding.

Documentation should improve shared understanding—not simply record information.