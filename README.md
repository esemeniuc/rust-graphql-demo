# rust-graphql-demo
A minimal example for using GraphQL with Rust using [Rocket](https://rocket.rs/) webserver and [Juniper](https://github.com/graphql-rust/juniper)

## Setup
Requires rust-nightly for [Rocket](https://rocket.rs/)

```bash
rustup toolchain install nightly
rustup default nightly
```

## Run
```bash
cargo run
```
Access GraphQL Playground from http://localhost:8000/

## Notes
We do not make use of context in this example for simplicity