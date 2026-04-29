# Contributing to Crosscheck

Thanks for your interest in contributing to Crosscheck. This guide covers how to file issues, propose changes, and submit pull requests across our repositories.

## Ways to contribute

- **Report a bug.** Use the [bug report template](.github/ISSUE_TEMPLATE/bug_report.md) when opening an issue.
- **Request a feature.** Use the [feature request template](.github/ISSUE_TEMPLATE/feature_request.md).
- **Improve documentation.** Typos, clarifications, and examples are all welcome.
- **Submit a pull request.** See the workflow below.

## Before you start

1. Check existing [issues](https://github.com/crosscheck-cloud) and pull requests to avoid duplicates.
2. For non-trivial changes, please open an issue first to discuss the approach. This saves both your time and ours.
3. Read the repository-specific `README.md` and `CONTRIBUTING.md` if one exists — individual repos may have their own setup steps.

## Pull request workflow

1. **Fork** the repository and create a feature branch from `main` (or the repository's default branch).
   ```
   git checkout -b feat/short-description
   ```
2. **Make your changes** in small, focused commits with clear messages. We loosely follow [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `chore:`, `docs:`, `refactor:`, etc.).
3. **Test your changes** locally. Run any test suite or lint command the repository defines.
4. **Update documentation** when you change behavior or add new functionality.
5. **Open a pull request** against the upstream repository and fill out the PR template completely.

## Branch naming

- `feat/<short-description>` — new feature
- `fix/<short-description>` — bug fix
- `docs/<short-description>` — documentation only
- `chore/<short-description>` — tooling, deps, infra

## Commit messages

```
feat(extension): add public share link to submit panel
fix(backend): handle empty network capture payloads
docs(readme): clarify install steps for Firefox
```

Keep the subject line under ~70 characters. Use the body to explain *why* the change matters, not what the diff shows.

## Code style

Follow the conventions already established in the repository you're contributing to. Lint and format your code before opening a PR. Most repositories have these wired into pre-commit hooks.

## Reviews

A maintainer will review your PR within a few business days. We may ask for changes — please don't take it personally; we want your contribution to land cleanly. Once approved, a maintainer will merge.

## Code of Conduct

All contributors are expected to follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## Questions

Reach out at **info@crosscheck.cloud** for general questions, or open a discussion on the relevant repository.
