# EXAMPLE-001 Test Plan

## Happy Path Tests

- Verify all expected increment documents exist.

## Invalid Input Tests

- Verify incomplete increment proposals are flagged during review.

## Partial Failure Tests

- Verify Directus promotion increments describe interrupted source-to-target workflows.

## Retry / Idempotency Tests

- Verify rerunning scaffolding does not overwrite existing docs.

## Concurrency Tests

- Verify parallel increment proposals use unique identifiers.

## Regression Coverage

- Verify existing Directus README and compose files remain unchanged.
