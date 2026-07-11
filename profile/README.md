# Provenant

**The open-source ecosystem for software provenance, license & copyright compliance, and SBOMs.**

This organization is the home of Provenant — open-source tooling for understanding what is really inside your software and its supply chain: the licenses, copyrights, package metadata, dependencies, and provenance behind everything you ship.

At its heart is a fast, Rust-based scanner, with the pieces built around it to run the same scans everywhere — on your machine, in CI, in containers, and through your package manager. Everything here follows one principle: results should be accurate, explainable, safely bounded, and fast enough to run anywhere.

## In this organization

- **[provenant](https://github.com/getprovenant/provenant)** — the core scanner: a CLI, an HTTP service, and an embeddable Rust library. Apache-2.0.
- **[provenant-action](https://github.com/getprovenant/provenant-action)** — the official GitHub Action for running Provenant scans in your CI workflows.
- **[homebrew-tap](https://github.com/getprovenant/homebrew-tap)** — the Homebrew tap for installing Provenant on macOS and Linux.

## Install & run

| Channel        | Get started                                                                                  |
| -------------- | -------------------------------------------------------------------------------------------- |
| Cargo          | `cargo install provenant-cli`                                                                |
| Homebrew       | `brew install getprovenant/tap/provenant`                                                    |
| Container      | `docker run ghcr.io/getprovenant/provenant scan .`                                           |
| GitHub Actions | `uses: getprovenant/provenant-action@v1`                                                     |
| Binaries       | Prebuilt archives on the [releases page](https://github.com/getprovenant/provenant/releases) |

Start with the [main repository](https://github.com/getprovenant/provenant) for documentation, usage, and the output schema.
