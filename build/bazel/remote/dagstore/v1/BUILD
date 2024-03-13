package(default_visibility = ["//visibility:public"])

load("@rules_proto//proto:defs.bzl", "proto_library")

licenses(["notice"])

proto_library(
    name = "dagstore_proto",
    srcs = ["dagstore.proto"],
    deps = [
        "@com_google_protobuf//:any_proto",
        "@googleapis//google/rpc:status_proto",
    ],
)
