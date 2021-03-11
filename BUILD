load("@rules_proto//proto:defs.bzl", "proto_library")

proto_library(
    name = "a",
    srcs = ["a.proto"],
)

proto_library(
    name = "b",
    srcs = ["b.proto"],
    deps = ["a"],
)

proto_library(
    name = "main",
    srcs = ["main.proto"],
    deps = ["b"],
)
