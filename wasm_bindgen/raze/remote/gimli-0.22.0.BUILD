"""
@generated
cargo-raze crate build file.

DO NOT EDIT! Replaced on runs of cargo-raze
"""

# buildifier: disable=load
load(
    "@io_bazel_rules_rust//rust:rust.bzl",
    "rust_binary",
    "rust_library",
    "rust_test",
)

# buildifier: disable=load
load("@bazel_skylib//lib:selects.bzl", "selects")

package(default_visibility = [
    # Public for visibility by "@raze__crate__version//" targets.
    #
    # Prefer access through "//wasm_bindgen/raze", which limits external
    # visibility to explicit Cargo.toml dependencies.
    "//visibility:public",
])

licenses([
    "notice",  # Apache-2.0 from expression "Apache-2.0 OR MIT"
])

# Generated targets
# Unsupported target "bench" with type "bench" omitted
# Unsupported target "convert_self" with type "test" omitted
# Unsupported target "dwarf-validate" with type "example" omitted
# Unsupported target "dwarfdump" with type "example" omitted

# buildifier: leave-alone
rust_library(
    name = "gimli",
    crate_type = "lib",
    deps = [
    ],
    srcs = glob(["**/*.rs"]),
    crate_root = "src/lib.rs",
    edition = "2018",
    rustc_flags = [
        "--cap-lints=allow",
    ],
    version = "0.22.0",
    tags = [
        "cargo-raze",
        "manual",
    ],
    crate_features = [
        "read",
    ],
)
# Unsupported target "parse_self" with type "test" omitted
# Unsupported target "simple" with type "example" omitted
# Unsupported target "simple_line" with type "example" omitted