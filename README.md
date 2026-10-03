# runtime-native

First-party native Tiinex runtime — portable headless orchestration of grounded roles, tasks, capabilities, execution state and Handoff-aware workflows over Tiinex Core and Interop contracts.

## Fresh-start boundary

This repository establishes the first-party provider- and environment-agnostic runtime frontier. Major 017 reduced the earlier runtime/refactor execution lineage, so no historical Task is current by default. The runtime remains intentionally minimal: future execution-model work must start from a new explicit bounded Task and public contracts before implementation is allowed to absorb provider, interop, extension or host-specific behavior.

A host may execute this runtime; the runtime may consume provider and Interop capabilities. The host, provider and external environment are not the runtime itself.

## Distribution

- npm: `@tiinex/runtime-native`
- branch: `master`
- release policy: `.github/release-policy.json`
- bootstrap command after repository/package qualification: `npm run publish:bootstrap`

Publication remains separate from source readiness and technical qualification.
