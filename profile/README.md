# Provenant

**The open-source ecosystem for software provenance, license & copyright compliance, and SBOMs.**

This organization is the home of Provenant — open-source tooling for understanding what is really inside your software and its supply chain: the licenses, copyrights, package metadata, dependencies, and provenance behind everything you ship.

At its heart is a fast, Rust-based scanner, with the pieces built around it to run the same scans everywhere — in CI, in containers, and through your package manager. Everything here follows one principle: results should be accurate, explainable, safely bounded, and fast enough to run anywhere.

## In this organization

- **[provenant](https://github.com/getprovenant/provenant)** — the core scanner: a CLI, an HTTP service, and an embeddable Rust library. Apache-2.0.

Alongside it live the pieces that package and run Provenant — a container image, a GitHub Action for CI, and a Homebrew formula — added here as each rolls out.

---

*Provenant is an independent open-source project and is not affiliated with, endorsed by, or sponsored by ScanCode Toolkit, AboutCode, or nexB Inc.*
