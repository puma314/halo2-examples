# Halo2 Examples

This repo includes a few simple examples to illustrate how to write circuit in Halo2.

## Instruction

Compile the repo

```
cargo build
```

Run examples
```
cargo test -- --nocapture test_example1
cargo test -- --nocapture test_example2
cargo test -- --nocapture test_example3
```

Plot the circuit layout
```
cargo test --all-features -- --nocapture plot_fibo1
cargo test --all-features -- --nocapture plot_fibo2
```

Wasm shenanigans
```
wasm-pack build --target web
python3 -m http.server
```

cargo build --target x86_64-unknown-linux-gnu