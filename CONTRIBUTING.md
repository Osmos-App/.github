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

Open a new issue and select the **Bug Report** template from the issue tracker of the relevant repository:

- [osmos-core](https://github.com/Osmos-App/osmos-core/issues/new/choose)
- [osmos-macos](https://github.com/Osmos-App/osmos-macos/issues/new/choose)
- [osmos-android](https://github.com/Osmos-App/osmos-android/issues/new/choose)
- [osmos-website](https://github.com/Osmos-App/osmos-website/issues/new/choose)

## Security Issues

Do **not** open a public issue for security vulnerabilities.
See [SECURITY.md](https://github.com/Osmos-App/.github/blob/main/SECURITY.md) for responsible disclosure.

## Contact

- General contributor questions and research inquiries: **hello@useosmos.com**
- Community and collaboration inquiries: **social@useosmos.com**
- User support: **support@useosmos.com**
- Security vulnerabilities: **security@useosmos.com**
