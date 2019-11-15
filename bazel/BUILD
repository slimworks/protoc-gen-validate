package(default_visibility = ["//visibility:public"])
load("@io_bazel_rules_go//proto:compiler.bzl", "go_proto_compiler")


config_setting(
    name = "windows_x86_64",
    values = {"cpu": "x64_windows"},
    visibility = ["//visibility:public"],
)

go_proto_compiler(
    name = "pgv_plugin_go",
    suffix = ".pb.validate.go",
    valid_archive = False,
    plugin = "@com_envoyproxy_protoc_gen_validate//:protoc-gen-validate",
    options = ["lang=go"],
)