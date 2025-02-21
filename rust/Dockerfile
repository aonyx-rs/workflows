FROM rust:1.85.0

# Install Clippy and rustfmt
RUN rustup component add clippy rustfmt

# Build and test all feature flag combinations for a crate
# https://github.com/frewsxcv/cargo-all-features
RUN cargo install cargo-all-features
