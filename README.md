# folder with work version - Original see [![alt text][1]](https://github.com/MathiasStadler/one)
<!-- keep the format -->
cd ~/workspace_codium/one/egui_plot/demo
export RUSTC_WRAPPER=sccache
RUST_LOG=trace trunk serve

// wrong RUST_LOG=info trunk serve --port 9080

RUST_LOG=info trunk serve --port 8090

// w log
RUST_LOG=debug trunk serve --port 8090

For further steps, see Project path [![alt text][1]](project_path.md)
<!-- make folder and download the link sign vai curl -->
<!-- mkdir -p img && curl --create-dirs --output-dir img -O  "https://raw.githubusercontent.com/MathiasStadler/link_symbol_svg/refs/heads/main/link_symbol.svg"-->
<!-- Link sign - Don't Found a better way :-( - You know a better method? - **send me a email** -->
[1]: ./img/link_symbol.svg
<!-- keep the format -->