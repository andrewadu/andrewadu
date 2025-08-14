# Contributing
Thanks for your interest! Please:
1. Open an issue first for any non‑trivial change.
2. Fork the repo; create a feature branch: `feat/concise-name`.
3. Write tests and docs; keep PRs focused.
4. Run the checks below before pushing.

## Local checks
- Lint: `ruff check .` and `black --check .`
- Types: `mypy .` (if configured)
- Tests: `pytest -q`

## Commit style
Conventional Commits (e.g., `feat: add idempotency key to charge API`).
