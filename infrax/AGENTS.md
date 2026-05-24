# Agent Instructions

## Increment Structure

This subproject uses `_increments/` for spec-driven engineering work.

- `_increments/_templates/` contains the canonical document templates for new increments.
- `_increments/EXAMPLE-001-bootstrap/` shows the expected package shape and level of detail.
- Each real increment should live in `_increments/<ID>-<short-slug>/`.
- Each increment package should include:
  - `README.md`
  - `spec.md`
  - `plan.md`
  - `risks.md`
  - `test-plan.md`
  - `implementation-notes.md`

## Required Workflow

All feature-related changes in this subproject must be packaged as an increment and adhere to this structure unless the user explicitly states otherwise.

Before implementing a feature, create or update the relevant increment package. Keep the spec, plan, risks, test plan, and implementation notes aligned with the actual change.
