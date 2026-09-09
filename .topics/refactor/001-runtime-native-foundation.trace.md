# Continuity Context

- Envelope Schema: tiinex.root.v1
- Parent
  - Parent Schema: [tiinex.topic.v1](https://github.com/Tiinex/docs/blob/053d46ce082d4ec261b82abc44ecca403d61e240/.topics/.schemas/core/topic/tiinex.topic.v1.schema.md)
  - Created At: 2026-09-09 16:47:25
  - Trace: [001-portable-tiinex-runtime.trace.md](../../business::.topics/initiatives/refactor/runtime/001-portable-tiinex-runtime.trace.md)
  - Origin:
    - [relative](../../business::.topics/initiatives/refactor/runtime/001-portable-tiinex-runtime.trace.md)
- Current
  - Current Schema: [tiinex.task.v1](https://github.com/Tiinex/docs/blob/053d46ce082d4ec261b82abc44ecca403d61e240/.topics/.schemas/core/task/tiinex.task.v1.schema.md)
  - Created At: 2026-09-09 16:50:32
  - Authors: Anchor
  - Why: Create a decomposed repo-local runtime work frontier tied to the Business runtime initiative before implementation begins.
  - Summary: Portable host-neutral runtime execution, capability, recovery and Handoff foundation.
  - Status: ready/local

---

# Runtime Native foundation

## Objective

Establish the portable Tiinex execution runtime as a headless first-party engine that hosts can invoke without embedding host, provider or environment-specific behavior.

## Scope

- execution model and lifecycle
- grounded Role/Task loading
- execution state and interruption/recovery
- capability discovery/resolution
- Provider and Interop consumption boundaries
- Handoff-aware transitions
- trace/evidence production
- host-neutral qualification

## Non-goals for this frontier

- no large orchestration implementation merely to populate the package
- no VS Code-, Chrome-, GitHub- or OpenAI-specific branches
- no new semantic authority

## Done Criteria

- public runtime contract is small and host-neutral
- provider/environment capabilities are injected/resolved through their owning layers
- same runtime can be hosted by at least two conceptually distinct hosts without contract forks
- recovery and evidence behavior are fail-closed where source/authority cannot be established

## Dependencies

- Controlling Business Portable Tiinex Runtime frontier.
- Public Core contracts for grounded artifacts, Handoffs and lineage mechanics.
- Provider and Interop capability contracts as they stabilize.

---

# Continuity Integrity

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: [001-portable-tiinex-runtime.trace.md](../../business::.topics/initiatives/refactor/runtime/001-portable-tiinex-runtime.trace.md)
  - Value: J4YII_DXdQ1anoBAkyui3bUot3tX6ClP5IFJVtBxILY

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: self
  - Value: o-hRhdTEC2vQOhWYwhwwMDkcRa13QkPCnOqWp81F460