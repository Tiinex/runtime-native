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
  - Created At: 2026-09-09 16:51:13
  - Authors: Anchor
  - Why: Separate execution semantics from host/provider implementation before runtime code grows.
  - Summary: Host-neutral execution lifecycle for grounded Tiinex work.
  - Status: ready/local

---

# Runtime execution model and lifecycle

## Objective
Define the smallest host-neutral execution lifecycle for grounded Tiinex work before implementation.

## Scope
Role/Task activation, execution state transitions, suspension/resume, completion and failure semantics.

## Dependencies
Parent Runtime Native foundation Task and canonical Role/Task/Handoff semantics from their owning surfaces.

## Done Criteria
Lifecycle can be implemented and tested without naming a specific host, provider or external environment.

---

# Continuity Integrity

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: [001-runtime-native-foundation.trace.md](../001-runtime-native-foundation.trace.md)
  - Value: o-hRhdTEC2vQOhWYwhwwMDkcRa13QkPCnOqWp81F460

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: self
  - Value: VHg-Qbzv7I6f54L2BkYi-e0zU4cH998MO7R4GsOHCTI