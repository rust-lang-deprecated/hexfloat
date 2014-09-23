# hexfloat

A Rust syntax extension to create floating point literals from hexadecimal strings.

## Usage

Add this to your `Cargo.toml`:

```toml
[dependencies.hexfloat]

git = "https://github.com/rust-lang/hexfloat"
```

and this to your crate root:

```rust
#![feature(phase)]
#[phase(plugin)]
extern crate hexfloat;
```
