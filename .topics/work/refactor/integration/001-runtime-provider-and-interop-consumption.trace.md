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
  - Why: Keep source providers and external-environment integrations independently diagnosable and replaceable.
  - Summary: Explicit dependency direction from runtime orchestration to Provider/Interop capabilities.
  - Status: ready/local

---

# Runtime Provider and Interop consumption

## Objective
Define the dependency direction between runtime orchestration, source Providers and external-environment Interop.

## Scope
Provider material access, Interop capability invocation, injected registries/adapters and boundary failure handling.

## Dependencies
Parent Runtime Native foundation Task; provider-native/provider-github and interop-native/interop-openai frontiers.

## Done Criteria
Provider and Interop implementations can evolve independently without becoming runtime semantic authority.

---

# Continuity Integrity

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: [001-runtime-native-foundation.trace.md](../001-runtime-native-foundation.trace.md)
  - Value: KMZyfB6WLTYSwAdUob_gU8tEp6xJ0ocEBWw7MH1S9ig

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: self
  - Value: RDPegOpDOAljmb2F7rby7N-nhbF9l3_gvKeKRJKP1-4