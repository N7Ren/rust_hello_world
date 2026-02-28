# Copilot Instructions

## Build & Run

```sh
cargo build          # debug build
cargo build --release
cargo run            # build + run
```

## Test

```sh
cargo test                        # run all tests
cargo test <test_name>            # run a single test by name
cargo test -- --nocapture         # show println! output during tests
```

## Lint & Format

```sh
cargo clippy         # lint
cargo fmt            # format
cargo fmt --check    # check formatting without modifying files
```
