load("@io_bazel_rules_dotnet//dotnet:defs.bzl", "core_library")

core_library(
    name = "example",
    srcs = glob([
        "*.cs",
    ]),
    out = "ClassLibrary1.dll",
    dotnet_context_data = "@io_bazel_rules_dotnet//:core_context_data",
    visibility = ["//visibility:public"],
    deps = [
        "@io_bazel_rules_dotnet//dotnet/stdlib.core:system.dll",
    ],
)
