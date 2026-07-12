# Rune Tools Desktop Agent Notes

## Scope

- This repo owns the BooneTools Electron desktop application, wallet/transaction services, bot experiments, and desktop-specific UX.
- The primary web/backend is `../website`; the legacy web line is `../RUNE-Tools`.
- `../../asgardex-desktop` is an independent upstream wallet, not this project's parent.

## Shared Context

- Read `../AGENTS.md`, `../../AGENTS.md`, and `../../knowledge/projects/boonetools.md`.
- Read `docs/CLAUDE.md` for the existing architecture, build commands, IPC patterns, and TypeScript DOM rules.
- Coordinate shared endpoint or protocol assumptions deliberately; do not copy desktop secrets, wallet handling, or IPC patterns into web clients.
