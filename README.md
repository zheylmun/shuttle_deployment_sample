# Sample repository for requiring package specification

Running `cargo build` builds the workspace libs and binaries.
Running `cargo build --package server` builds the server.

This is the only way I've found to get the default behavior that I want.
Building the server pulls in tons of additional tools and a complex build.
