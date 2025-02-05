# Installation

Cairo can be installed by simply downloading [Scarb](https://docs.swmansion.com/scarb/docs). Scarb bundles the Cairo compiler and the Cairo language server together in an easy-to-install package so that you can start writing Cairo code right away.

Scarb is also Cairo's package manager and is heavily inspired by [Cargo](https://doc.rust-lang.org/cargo/), Rust’s build system and package manager.

Scarb handles a lot of tasks for you, such as building your code (either pure Cairo or Starknet contracts), downloading the libraries your code depends on, building those libraries, and provides LSP support for the VSCode Cairo 1 extension.

As you write more complex Cairo programs, you might add dependencies, and if you start a project using Scarb, managing external code and dependencies will be a lot easier to do.

Let's start by installing Scarb.

## Installing Scarb

### Requirements

Scarb requires a Git executable to be available in the `PATH` environment variable.

### Installation

To install Scarb, please refer to the [installation instructions](https://docs.swmansion.com/scarb/download).
You can simply run the following command in your terminal, then follow the onscreen instructions. This will install the latest stable release.

```bash
curl --proto '=https' --tlsv1.2 -sSf https://docs.swmansion.com/scarb/install.sh | sh
```

- Verify installation by running the following command in new terminal session, it should print both Scarb and Cairo language versions, e.g:

  ```bash
  $ scarb --version
    scarb 0.6.0 (532d8e349 2023-08-07)
    cairo: 2.1.0 (https://crates.io/crates/cairo-lang-compiler/2.1.0)
  ```
