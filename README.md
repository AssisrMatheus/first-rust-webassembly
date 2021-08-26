# first-rust-webassembly
My first rust/webassembly experiment

Done following https://developer.mozilla.org/en-US/docs/WebAssembly/Rust_to_wasm

- Make sure [rust](https://www.rust-lang.org/install.html) is installed
- Make sure `wasm-pack` is installed from cargo
    - If on windows also make sure to install https://strawberryperl.com/
- `wasm-pack build --target web` compiles it
- `npx http-server` runs it
