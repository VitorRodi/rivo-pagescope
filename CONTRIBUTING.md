# Contributing

## Start with the project context

- [README.md](README.md)
- [DESIGN.md](DESIGN.md)

Include browser/OS, PageScope build, report source (local Lighthouse, PageSpeed or import), Lighthouse version, device and settings. Remove private URLs and request data; use a synthetic or sanitized report. Lab metrics are not real-user measurements.

## Issues and pull requests

Search existing issues and PRs before opening one. Use the maintenance form for documentation, test or tooling work, and include the concrete problem, evidence, scope and verifiable acceptance criteria. Keep one coherent change per branch/PR.

Describe the final result and link the issue with `Closes #<number>` only when all acceptance criteria are met; use `Refs #<number>` for partial work. GitHub closes the linked issue when the PR merges into the default branch. Do not create empty changes just to generate activity.

## Verification

Use `npm ci`, `npm test`, `npm run build` and `npm run test:e2e` (with the Playwright browser installed as in CI). For comparison changes, exercise baseline/import and mismatch warnings under equivalent settings. Do not run audits against third-party sites just to validate documentation. Record separately any external API or local Chrome check.

For documentation-only work, inspect the entire diff and verify links and form structure. Record the actual checks and their limits; do not claim runtime validation from a documentation review. Existing project instructions and CI gates still apply.

Review the diff before publishing. Keep credentials and private data out of issues, logs and examples. Changes can be reverted with a follow-up PR; describe any operational rollback separately.
