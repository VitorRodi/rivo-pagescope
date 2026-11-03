## Problem and result

Describe the concrete problem, scope and resulting behavior.

## Related issue

Use `Closes #<number>` only when all acceptance criteria are met; use `Refs #<number>` for partial work.

## Evidence

List commands/checks actually run, their results, and checks not run with reasons.

Use `npm ci`, `npm test`, `npm run build` and `npm run test:e2e` (with the Playwright browser installed as in CI). For comparison changes, exercise baseline/import and mismatch warnings under equivalent settings. Do not run audits against third-party sites just to validate documentation. Record separately any external API or local Chrome check.

## Limits and review

- [ ] The diff is limited to the stated scope.
- [ ] Evidence and examples contain no private data or credentials.
- [ ] Compatibility, behavior changes, limitations and rollback are described where applicable.

Include browser/OS, PageScope build, report source (local Lighthouse, PageSpeed or import), Lighthouse version, device and settings. Remove private URLs and request data; use a synthetic or sanitized report. Lab metrics are not real-user measurements.
