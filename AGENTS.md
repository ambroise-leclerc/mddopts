# mddOpts contributor guide

This file is the canonical, tool-neutral guidance for contributors and coding agents.

## Published project state

The published `main` branch is currently a documentation and licensing scaffold: it contains no
build system, source tree, examples, or tests. Treat the short `README.md` as the complete public
project description and do not claim that an API, compiler matrix, compliance feature, or build
command exists until the corresponding files are committed.

## Working rules

- Preserve the licensing and contribution terms in `LICENSE`, `LICENSING.md`, `CLA.md`, and
  `CONTRIBUTING.md`.
- When implementation first lands, add exact configure/build/test commands here from the committed
  build system and keep them synchronized with CI.
- Keep generated build output outside version control.
- Keep tool-specific assistant settings local and ignored. Commit messages, PR descriptions, and
  code comments contain no assistant attribution.
