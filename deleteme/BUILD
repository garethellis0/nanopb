load("//:nanopb.bzl", "nanopb_proto_library")

proto_library(
    name = "control_proto",
    srcs = ["control.proto"],
    deps = [],
)

nanopb_proto_library(
    name = "c_proto",
    deps = [
        ":control_proto",
    ],
)
