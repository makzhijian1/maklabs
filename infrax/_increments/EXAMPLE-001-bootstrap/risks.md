# EXAMPLE-001 Risks

## Unsafe Assumptions

- Assuming AWS permissions, regions, and account boundaries are stable may be unsafe.

## Failure Modes

- Infrastructure changes may partially apply or drift from declared state.

## Operational Risks

- Rollout without observability or rollback notes can increase incident recovery time.

## Security Concerns

- Cloud credentials, account IDs, IAM policies, and secrets require careful handling.

## Recovery / Mitigation

- Require rollback, drift detection, and access review notes for infrastructure increments.
