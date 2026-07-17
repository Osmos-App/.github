<p align="center">
  <img src="./assets/readme/hero.svg" width="100%" alt="Osmos: local-first version control that keeps history close to the files you create">
</p>

# Osmos

Osmos is a local-first version-control project for people who create with files: designers, writers, editors, and developers. It is being built to replace version-name chaos with a private, local history that is easy to return to.

> **Project status:** the Rust core provides local versioning, content-addressable blob storage, SQLite metadata, and a local daemon API. The desktop experience and device-to-device transport are still in development.

## The idea

Most creative work starts as a folder, not a Git repository. Osmos is designed around that reality:

```text
working folder → local history → choose an earlier version when you need it
```

The goal is simple: keep the history beside the work, so you can focus on making it.

## What exists today

| Area | Current state |
| --- | --- |
| [Osmos Core](https://github.com/Osmos-App/osmos-core) | Rust workspace with directory tracking, BLAKE3-addressed blobs, SQLite metadata, commits and branches, plus a Unix socket daemon. |
| [Osmos Desktop](https://github.com/Osmos-App/osmos-ts) | Tauri + React + TypeScript client foundation; product screens are in progress. |
| [Osmos Website](https://github.com/Osmos-App/osmos-website) | Product site and waitlist, built with Vite, custom CSS tokens, and Firebase. |

## Where it is going

- A calm desktop interface for reviewing changes, creating snapshots, and moving between branches.
- Device discovery and peer-to-peer transport, planned in the core workspace.
- A workflow that keeps local history understandable without requiring Git vocabulary.

## Get involved

The best place to start is the repository closest to your interest:

- [Explore the core engine](https://github.com/Osmos-App/osmos-core)
- [See the desktop client foundation](https://github.com/Osmos-App/osmos-ts)
- [Browse the product site](https://github.com/Osmos-App/osmos-website)
- [Read the contribution guide](https://github.com/Osmos-App/.github/blob/main/CONTRIBUTING.md)

## Security and contact

Please report vulnerabilities privately at **security@useosmos.com**; do not open a public issue. See the [security policy](https://github.com/Osmos-App/.github/blob/main/SECURITY.md) for details.

For general questions, reach us at **hello@useosmos.com**.
