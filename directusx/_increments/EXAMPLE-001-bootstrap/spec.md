# EXAMPLE-001 Specification

## Behaviour

- Future `directusx` increments use a consistent markdown document set before implementation starts.

## Contracts

- Increment folders are named with a stable identifier and short slug.
- Directus promotion, environment, and schema changes document expected contracts before code changes.

## Inputs / Outputs

- Inputs:
  - Directus environment assumptions, schema state, and promotion requirements.
- Outputs:
  - Reviewable engineering documents for AI-assisted and human review.

## Invariants

- Existing Directus project files are not overwritten.
- Promotion semantics must be explicit before implementation.

## Edge Cases

- Source and target Directus instances may diverge in schema, permissions, or extensions.

## Failure Semantics

- Partial promotion failure must be documented with rollback or recovery expectations.
