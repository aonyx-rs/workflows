FROM rust:1.84.1

# Install Clippy and rustfmt
RUN rustup component add clippy rustfmt

# Build and test all feature flag combinations for a crate
# https://github.com/frewsxcv/cargo-all-features
RUN cargo install cargo-all-features
