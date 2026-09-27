# Agent handoff: godot

Godot Engine – Multi-platform 2D and 3D game engine

## Start here

Repository: https://github.com/nihitkaul/godot. Inspected default branch: `master`. Handoff prepared September 27, 2026 from checked-in sources.

This is a fork. Preserve upstream contribution instructions and licenses. This sweep adds documentation only; it does not synchronize upstream branches or release anything.

Read [README.md](README.md), [thirdparty/README.md](thirdparty/README.md) before running the app. Those documents carry project-specific setup details and known limitations.

## Architecture map

- `core/`: tracked project subtree; inspect its source and local documentation before edits.
- `doc/`: tracked project subtree; inspect its source and local documentation before edits.
- `drivers/`: tracked project subtree; inspect its source and local documentation before edits.
- `editor/`: tracked project subtree; inspect its source and local documentation before edits.
- `main/`: tracked project subtree; inspect its source and local documentation before edits.
- `misc/`: tracked project subtree; inspect its source and local documentation before edits.
- `modules/`: tracked project subtree; inspect its source and local documentation before edits.
- `platform/`: tracked project subtree; inspect its source and local documentation before edits.
- `scene/`: tracked project subtree; inspect its source and local documentation before edits.
- `servers/`: tracked project subtree; inspect its source and local documentation before edits.
- `tests/`: automated checks.
- `thirdparty/`: tracked project subtree; inspect its source and local documentation before edits.

Entry points and runtime definitions: [SConstruct](SConstruct).

## Install, run and validate

Python packaging is defined in [pyproject.toml](pyproject.toml). Follow the README/contributor installation instructions and declared Python version; GUI/native dependencies can require platform-specific packages.

## Configuration, data and service plumbing


Tracked data/database assets exist. Check provenance and whether they are fixtures, migration input or historical snapshots before editing; do not assume they are disposable runtime state.

Never commit provider credentials, OAuth secrets, personal records, local browser profiles or dependency directories. Deployment is a separate operation from pushing source: a git push does not prove the app is live.

## Existing design and operations references

- [AUTHORS.md](AUTHORS.md)
- [CHANGELOG.md](CHANGELOG.md)
- [CONTRIBUTING.md](CONTRIBUTING.md)
- [DONORS.md](DONORS.md)

## Handoff and next-change checklist

This sweep checked repository structure, documentation and command/configuration declarations. It did not certify a fresh install, live credentials, every deployment or every test suite. Treat existing verification notes as dated evidence, not a current production guarantee.

For the next change: read local AGENTS.md rules; inspect git status and branch; reproduce the relevant behavior; update source and focused tests; run the declared relevant checks; update README/architecture/runbook with changed commands, data flow and limitations; commit only reviewed files; push and verify the remote commit. Record any unresolved setup dependency or test failure explicitly. Preserve repository visibility and unrelated work.
