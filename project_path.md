# project path
<!-- keep the format -->
## start the demo
<!-- keep the format -->
- change to folder **egui_plot/demo**
- export RUSTC_WRAPPER=sccache
- trunk serve --port 9080
<!-- keep the format -->
## test out flamegraph
<!-- keep the format -->
-- install
  -- folder **egui_plot** NOT DEMO
-- enable without reboot
-- set
sysctl -w kernel/perf_event_paranoid=1
-- check
sysctl --all |grep perf_event_paranoid
-- show current settings
sudo sysctl --all |grep perf_event_paranoid
cargo flamegraph
<!-- keep the format -->
RUST_LOG=trace cargo flamegraph
<!-- keep the format -->
ERROR MESSAGE =>
The platform you're compiling for is not supported by winit cargo flamegraph

## FOUND HERE [![alt text][1]](https://stackoverflow.com/questions/74633209/im-unable-to-run-rust-winit-application-on-alpine-wayland)

## Which target already installed

sudo apt install librust-winit-dev

rustup target list |grep installed

- ~/.cargo/config.toml

[target.x86_64-unknown-linux-musl]
rustflags = [ "-C", "target-feature=-crt-static" ]

x86_64-unknown-linux-gnu

wasm32-unknown-unknown

## used platform

wmctrl -m
Name: GNOME Shell
Class: N/A
PID: N/A
Window manager's "showing the desktop" mode: OFF

<!-- keep the format -->
For further steps, see Project path [![alt text][1]](project_path.md)
<!-- make folder and download the link sign vai curl -->
<!-- mkdir -p img && curl --create-dirs --output-dir img -O  "https://raw.githubusercontent.com/MathiasStadler/link_symbol_svg/refs/heads/main/link_symbol.svg"-->
<!-- Link sign - Don't Found a better way :-( - You know a better method? - **send me a email** -->
[1]: ./img/link_symbol.svg
<!-- keep the format -->