# Changelog

All notable changes to `cel-brief` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Pre-1.0 releases were developed privately before the first public crates.io
line at `0.1.5`.

## [Unreleased]

## [0.2.0] — 2026-06-25

### Changed
- Optional `memory` feature depends on `cel-memory` **0.2.0** from crates.io.
- MSRV raised to **1.76** (`rust-version` in `Cargo.toml`).

## [0.1.7] — 2026-06-25

### Changed
- Added crates.io metadata, README badges, and Clippy in CI.
- Depends on `cel-memory` 0.1.7 from crates.io (optional `memory` feature).
- Removed orphan MIT license file; Apache-2.0 only.

## [0.1.6] — 2026-06-25

### Added
- Standalone GitHub repository at `https://github.com/dimpagk92/cel-brief`.
- Examples: `standalone`, `with_memory`, and `governance`.
- Published as a standalone crate on crates.io.

### Changed
- Depends on `cel-memory` 0.1.6 from crates.io (optional `memory` feature).

## [0.1.0-pre] — 2026-05-23

### Added
- Initial crate scaffolding: `types`, `source`, `builder`, `governance`,
  `budget`, `tokenizer`, `error`, and `receipt` modules.
- `BriefError` type with `Result` alias.
- `memory` feature — opt-in dependency on `cel-memory`.
- `perception` feature — enables `PerceptionSource` over downstream perception backends.

### Notes
- Imports only `cel-memory` (and only behind the `memory` feature) from
  crates.io.
