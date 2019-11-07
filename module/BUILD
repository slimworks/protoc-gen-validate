load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "go_default_library",
    srcs = [
        "checker.go",
        "validate.go",
    ],
    importpath = "github.com/envoyproxy/protoc-gen-validate/module",
    visibility = ["//visibility:public"],
    deps = [
        "@com_envoyproxy_protoc_gen_validate//templates:go_default_library",
        "@com_envoyproxy_protoc_gen_validate//templates/java:go_default_library",
        "@com_envoyproxy_protoc_gen_validate//validate:go_default_library",
        "@com_envoyproxy_protoc_gen_validate//vendor/github.com/lyft/protoc-gen-star:go_default_library",
        "@com_envoyproxy_protoc_gen_validate//vendor/github.com/lyft/protoc-gen-star/lang/go:go_default_library",
        "@com_github_golang_protobuf//proto:go_default_library",
        "@com_github_golang_protobuf//ptypes:go_default_library",
        "@com_github_golang_protobuf//ptypes/duration:go_default_library",
        "@com_github_golang_protobuf//ptypes/timestamp:go_default_library",
    ],
)
