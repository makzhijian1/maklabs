# EXAMPLE-001 Risks

## Unsafe Assumptions

- Assuming source and target Directus instances have identical capabilities may be unsafe.

## Failure Modes

- Promotion tooling may create partial state if interrupted.

## Operational Risks

- Compose environments may drift from production assumptions.

## Security Concerns

- Directus admin tokens, database credentials, and environment variables must not be committed.

## Recovery / Mitigation

- Require test plans to include retry, idempotency, and rollback checks for promotion work.
