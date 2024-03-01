# Medifax ![openFDA](https://img.shields.io/badge/powered%20by-openFDA-blue?link=%22https://open.fda.gov/%22) ![Version](https://img.shields.io/badge/version-v0.1.0-green)

Convenient tool to pull detailed statistics on drugs and their generics from the openFDA database.

# Installation

- From [binstall](https://github.com/cargo-bins/cargo-binstall) (for quick, binary installation):

```
cargo binstall medifax
```

# Compilation

Platform Requirements:

- **Only macOS 14.0 and Windows 11 have been used to test. Linux distros & any distribution that supports Tauri should work.**
- **Both x86_64-apple-darwin and aarch64-apple-darwin have been tested. On Windows, x86_64-pc-windows-msvc has been tested.**
- **The tauri API is required**

```
npm install
cargo tauri build
```
# Usage

- Medifax is a UI-based tool so you can simply run the executable and open the Generics tab to run queries.
- There is also a homescreen where you can see new changes etc.

# MSRV

- The Minimum Supported Rust Version for compiling this executable is 1.70.0
