# My Demo App

A simple app for demoing basic cargo-dist usage

The project was created with

```sh
cargo new my-app
```

with some basic Cargo.toml fields like "license" entered by hand, as well as README.md, LICENSE*, and RELEASES.md.

All cargo-dist config/CI was defined by:

```sh
cargo dist init --ci=github --installer=shell --installer=powershell
```

Releases are produced with:

```sh
cargo release 0.1.0 --no-publish
```