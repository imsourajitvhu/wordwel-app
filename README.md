# wordwel-app

Fast line/byte counter written in Rust

Started as a weekend hack, grew on me.

## How to use

```bash
./target/release/wordwel-app src/*.rs
cat README.md | ./target/release/wordwel-app
```

## What it does

- Zero dependencies outside std
- Counts lines, words and bytes like wc
- Parallel over files with std threads
- Reads stdin or multiple files

## Getting started

```bash
cargo build --release
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── src/
│   └── main.rs
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── Cargo.toml
├── LICENSE
└── SECURITY.md
```

## Development

```bash
cargo build
cargo clippy -- -D warnings
```
