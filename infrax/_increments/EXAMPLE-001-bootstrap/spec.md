# EXAMPLE-001 Specification

## Behaviour

- Future `infrax` increments use a consistent markdown document set before implementation starts.

## Contracts

- Increment folders are named with a stable identifier and short slug.
- Infrastructure changes document resource, permission, and operational contracts before implementation.

## Inputs / Outputs

- Inputs:
  - Infrastructure goals, AWS account assumptions, and operational constraints.
- Outputs:
  - Reviewable engineering documents for AI-assisted and human review.

## Invariants

- Existing infrastructure docs are not overwritten.
- Changes to cloud resources must state rollout and recovery behaviour.

## Edge Cases

- Multi-account, multi-region, or permission-limited execution must be called out explicitly.

## Failure Semantics

- Failed provisioning, drift, or rollback expectations must be documented before implementation.
