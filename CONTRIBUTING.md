# Contributing

Thanks for contributing to this pilot repository.

## Goals

This repo is used to validate Forge's end-to-end flow in a low-risk environment.
Prefer small, reviewable changes.

## Development Workflow

1. Create a branch from `main`.
2. Make focused changes with clear commit messages.
3. Run local checks before opening a PR.
4. Open a PR with context and a simple test plan.

## Branch Naming

Use one of these prefixes:

- `docs/<short-description>`
- `chore/<short-description>`
- `fix/<short-description>`

## Pull Request Expectations

- Keep PRs scoped and easy to review.
- Explain what changed and why.
- Include a test plan, even for docs-only changes.
- Link related tickets/issues where relevant.

## Local Checks

Run these before pushing:

- Markdown lint (if docs changed)
- Any project-specific checks in CI

## Markdown style guardrails

To keep CI green, follow these conventions in markdown files:

- Use a single top-level heading (`#`) as the first heading in each file.
- Keep one blank line around headings and lists.
- Avoid trailing punctuation in headings.

## Code of Conduct

Be respectful, clear, and collaborative in reviews and discussions.
