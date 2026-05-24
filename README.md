# maklabs

`maklabs` is my personal collection of independent apps, tools, and platform experiments for exploring useful or interesting stuff.

This is not a single monorepo product. Each top-level folder is a self-contained subproject with its own domain, workflow, and implementation assumptions.

## Subprojects

- `directusx/`: Directus experiments, migration tooling, and promotion workflows.
- `infrax/`: Infrastructure practice and cloud automation, including AWS-focused work.

## Agent Guidance

- Read that subproject's `AGENTS.md` before making changes.
- Use that subproject's `_increments/` directory for feature-related work.
- Package feature changes as an increment unless the user explicitly states otherwise.
- Do not assume shared runtime, deployment, or release boundaries across subprojects.
