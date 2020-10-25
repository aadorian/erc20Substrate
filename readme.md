rustup component add rust-src --toolchain nightly
rustup target add wasm32-unknown-unknown --toolchain stable
rustup install nightly-2020-10-06
rustup target add wasm32-unknown-unknown --toolchain nightly-2020-10-06

rustup default +nigtly2020-10-06 

cargo +nightly-2020-10-06 install canvas-node --git https://github.com/paritytech/canvas-node.git --tag v0.1.0 --force

cargo +nightly-2020-10-06  build
cargo +nightly-2020-10-06  test

cargo +nightly-2020-10-06  contract generate-metadata

Open 
Canvas 
https://paritytech.github.io/canvas-ui

Video 
[![](http://img.youtube.com/vi/2z8Ypldwj1Y/0.jpg)](http://www.youtube.com/watch?v=2z8Ypldwj1Y "Video Explain")
