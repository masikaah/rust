# rust
SETTING UP THE FRONTEND PART
install rust in the workspace
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

install webasembly target
rustup target add wasm32-unknown-unknown

install trunk
cargo install --locked trunk

install cargo generate 
 cargo install cargo-generate  


installing wasm-bidgen-cli
cargo install --locked wasm-bindgen-cli

checkout and generate starter template
cargo generate yewstack/yew-trunk-minimal-template

run the project in the root project
trunk serve


