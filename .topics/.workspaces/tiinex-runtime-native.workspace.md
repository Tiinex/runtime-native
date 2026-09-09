# Continuity Context

- Envelope Schema: tiinex.root.v1
- Current
  - Current Schema: tiinex.workspace.v1
  - Created At: 2026-09-09 16:49:03
  - Authors: Anchor
  - Why: Establish durable source identity before runtime implementation is decomposed and delegated.
  - Summary: Portable Workspace entrypoint for the first-party host-neutral runtime frontier.
  - Status: ready/local

---

# Tiinex Runtime Native

## Schema Origins

- Tiinex Docs canonical schemas
  - Kind: github-tree
  - Repository: Tiinex/docs
  - Ref: master
  - Root Path: .topics/.schemas
  - Trust Role: canonical-core

## Workspace Entrypoints

### Runtime Native source

- Source Kind: local-directory
- Repository: Tiinex/runtime-native
- Root Path: .
- Repo Files Discovery: on

## Workspace Boundary

- First-party provider- and environment-agnostic headless Tiinex runtime frontier.
- Hosts execute the runtime; Providers resolve source/material; Interop exposes external environment capabilities.
- No host/provider/environment-specific implementation is implied by this initial Workspace.

---

# Continuity Integrity

- [sha256-base64url-c14n-v2](https://github.com/Tiinex/docs/blob/3988951208eb9a8926e84ab42625d4b42fa00c2d/.topics/.validators/sha256-base64url-c14n-v2.validator.md)
  - Towards: self
  - Value: p6vjwuQl48tBUIYhRjp-ToI9-gsh5MRFU2jRsw7RMgA