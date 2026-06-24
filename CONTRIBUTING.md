# Contributing to Osmos

Thank you for your interest in contributing! This guide will help you get started.

## Getting Started

1. Fork the repository you want to contribute to
2. Create a branch: `git checkout -b feature/your-feature`
3. Make your changes
4. Open a pull request against `main`

## Branch Naming

| Type | Format | Example |
|------|--------|---------|
| Feature | `feature/...` | `feature/mDNS-discovery` |
| Bug fix | `fix/...` | `fix/sync-deadlock` |
| Docs | `docs/...` | `docs/encryption-guide` |
| Chore | `chore/...` | `chore/update-deps` |

## Commit Messages

```
<type>: <short description>
```

Types: `feat`, `fix`, `refactor`, `docs`, `test`, `chore`, `perf`, `ci`

## Code Style

| Language | Standard |
|----------|----------|
| Rust | `cargo fmt` + `cargo clippy` |
| Swift | SwiftLint |
| Kotlin | ktlint |
| JavaScript | ESLint + Prettier |

## Pull Requests

- Fill out the PR template completely
- Link the related issue (if any)
- Make sure all CI checks pass
- Request a review — do not merge your own PR

## Reporting Bugs

Use the [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md) issue template.

## Security Issues

Do **not** open a public issue for security vulnerabilities.
See [SECURITY.md](SECURITY.md) for responsible disclosure.
