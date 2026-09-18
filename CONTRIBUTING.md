# Contributing to Kitewell Contract

Rust / Soroban builder check-in registry.

## Local setup

```bash
rustup target add wasm32v1-none
cargo test --manifest-path kitewell/Cargo.toml
stellar contract build --manifest-path kitewell/Cargo.toml
```

## PR guidelines

1. One issue per PR when possible
2. Prefix titles with `[contract]`
3. Include unit tests for storage / auth changes
4. Keep Testnet as the documented deploy target

Sibling layers: [frontend](https://github.com/Kitewell-lab/frontend), [backend](https://github.com/Kitewell-lab/backend).

## Code of conduct

See [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md).
