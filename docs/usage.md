# Usage

The README covers the basics. This page collects the
longer examples and the notes that did not fit up front.

## Basic

```bash
./target/release/wordwel-app src/*.rs
cat README.md | ./target/release/wordwel-app
```

## Notes

- Reads stdin or multiple files
- Zero dependencies outside std
