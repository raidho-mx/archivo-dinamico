# CLAUDE.md — Archivo Dinámico

This file provides guidance for AI assistants (Claude Code and similar tools) working in this repository.

## Project Overview

**Archivo Dinámico** ("Dynamic Archive/File") is a project currently in its initial state. The repository has a single placeholder README and no source code yet.

- **Repository:** raidho-mx/archivo-dinamico
- **Primary language:** TBD (not yet established)
- **Framework:** TBD (not yet established)

> **Note for AI assistants:** Since this project has no source code yet, update this file as the codebase grows. Document frameworks, conventions, and workflows as they are introduced.

---

## Repository Structure

```
archivo-dinamico/
├── README.md          # Project description (currently minimal)
└── CLAUDE.md          # This file
```

As the project grows, expect directories such as:

```
src/           # Application source code
tests/         # Test files
docs/          # Additional documentation
```

---

## Development Workflow

### Branching

- **main/master** — stable, production-ready code
- **Feature branches** — use descriptive names: `feature/<short-description>`
- **Fix branches** — `fix/<short-description>`
- **Claude-managed branches** — prefixed with `claude/` (e.g., `claude/claude-md-mmcih56mp0s6pjly-foXO7`)

### Commits

Write clear, imperative commit messages:

```
Add user authentication module
Fix file upload size validation
Refactor archive search to use index
```

- Keep the subject line under 72 characters
- Use the body to explain *why*, not *what*

### Git Push

Always push with tracking:

```bash
git push -u origin <branch-name>
```

---

## Code Conventions

Since no language or framework has been chosen yet, these are the expected defaults to follow unless the project establishes otherwise:

- **Clarity over cleverness** — write readable, maintainable code
- **Small, focused functions** — each function does one thing
- **No premature abstraction** — add helpers only when patterns repeat 3+ times
- **Tests alongside code** — place tests near the code they test
- **No dead code** — remove unused variables, imports, and functions

When a language/framework is adopted, add a dedicated section here with language-specific conventions.

---

## Testing

No testing framework is configured yet. When one is added:

1. Document the test command here (e.g., `npm test`, `pytest`, `go test ./...`)
2. Describe how to run a single test vs. the full suite
3. Note coverage requirements if any

---

## Environment Setup

No setup steps are required yet. When dependencies are introduced, document them here:

```bash
# Example (fill in when applicable)
# npm install
# cp .env.example .env
```

---

## Key Decisions Log

| Date       | Decision                        | Reason |
|------------|---------------------------------|--------|
| 2026-03-04 | Repository initialized          | Project start |
| 2026-03-04 | CLAUDE.md created               | Baseline guidance for AI assistants |

Add entries here when significant architectural or tooling decisions are made.

---

## Notes for AI Assistants

- This codebase is **new and empty** — do not assume any existing patterns
- Update this CLAUDE.md whenever frameworks, conventions, or tools are adopted
- Do not generate boilerplate code speculatively — wait for explicit requirements
- Prefer editing existing files over creating new ones unless a new file is clearly needed
- When in doubt about scope, ask before acting
