# Function Builder

AI-powered toolkit for building [Nango](https://nango.dev) functions. See details on prpm[nango-function-builder](https://prpm.dev/collections/nango-function-builder)

## What's Included

| Package | Type | Description |
|---------|------|-------------|
| `action-builder-skill` | Skill | Patterns for thin API wrapper actions |
| `sync-builder-skill` | Skill | Patterns for pagination, batch saving, deletion detection |
| `integration-patterns-skill` | Skill | Shared patterns (private dependency) |
| `build-function` | Command | TDD workflow: generates code, tests, and validates |

## Install

```bash
prpm install collections/nango-function-builder
```

## Publishing Changes

Uses [prpm](https://prpm.dev) for cross-platform distribution (Claude, Cursor, Copilot, Gemini, etc).

```bash
prpm login
# bump version in prpm.json
prpm publish --dry-run  # preview
prpm publish            # publish
```
