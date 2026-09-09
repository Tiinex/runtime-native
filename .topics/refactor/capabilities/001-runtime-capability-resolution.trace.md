# Continuity Context

- Envelope Schema: tiinex.root.v1
- Parent
  - Parent Schema: [tiinex.task.v1](https://github.com/Tiinex/docs/blob/053d46ce082d4ec261b82abc44ecca403d61e240/.topics/.schemas/core/task/tiinex.task.v1.schema.md)
  - Created At: 2026-09-09 16:50:32
  - Trace: [001-runtime-native-foundation.trace.md](../001-runtime-native-foundation.trace.md)
  - Origin:
    - [relative](../001-runtime-native-foundation.trace.md)
- Current
  - Current Schema: [tiinex.task.v1](https://github.com/Tiinex/docs/blob/053d46ce082d4ec261b82abc44ecca403d61e240/.topics/.schemas/core/task/tiinex.task.v1.schema.md)
  - Created At: 2026-09-09 16:51:14
  - Authors: Anchor
  - Why: Prevent runtime implementation from accumulating provider/host switches.
  - Summary: Provider- and environment-neutral capability discovery and resolution.
  - Status: ready/local

---

# Runtime capability resolution

## Objective
Define how runtime work requests capabilities without hardcoding the implementation that satisfies them.

## Scope
Capability discovery, selection, availability, refusal/degradation and explicit execution boundaries.

## Dependencies
Parent Runtime Native foundation Task; Provider and Interop contract frontiers.

## Done Criteria
Runtime code can request capabilities without `if GitHub`, `if OpenAI`, `if VS Code` or equivalent provider/host branching.

---

# Continuity Integrity

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: [001-runtime-native-foundation.trace.md](../001-runtime-native-foundation.trace.md)
  - Value: o-hRhdTEC2vQOhWYwhwwMDkcRa13QkPCnOqWp81F460

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: self
  - Value: gTypn_QYxoZPmCMSUTfKzjSFWNG62aV9PAl9F8F_Z3U