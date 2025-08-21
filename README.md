# cname

## Dependencies

- [rust/cargo](https://www.rust-lang.org/learn/get-started)
- [rustfmt](https://github.com/rust-lang/rustfmt)
- [clippy](https://github.com/rust-lang/rust-clippy)

## Develop

To build:

```console
cargo build
```

To run:

```console
cargo run
```

To fix formatting/linting errors:

```console
cargo fmt
cargo clippy --fix --allow-dirty -- -W clippy::pedantic
```
