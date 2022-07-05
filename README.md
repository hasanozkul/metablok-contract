## Install rustup
First, install rustupopen in new window. Once installed, make sure you have the wasm32 target. This is an important step before running any contract to ensure that you are running Rust 1.51.0+ with wasm32-unknown-unknown target installed.


$ cargo --version

$ rustup --version
$ rustup default stable
$ rustup target add wasm32-unknown-unknown
$ rustup target list --installed

## Running this contract

You will need Rust 1.44.1+ with `wasm32-unknown-unknown` target installed.

You can run unit tests on this via: 

`cargo test`

Once you are happy with the content, you can compile it to wasm via:




