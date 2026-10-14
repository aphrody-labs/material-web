# Repository rules

Use Bun's native `bun check`, `bun lint`, `bun fmt` and `bun n2b` commands directly for type checking, linting, formatting and migration. Do not install or invoke external backends for these commands.

This repository is private. Preserve upstream licenses and public package APIs.
Use the pinned Bun toolchain and dependency lockfile.
Run `bun check` and the scoped package tests before publishing.
Commit as `aphrody-dev <contact@aphrody.com>` without assistant attribution.
Never commit credentials or environment files.
