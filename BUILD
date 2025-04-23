load("@io_bazel_rules_kotlin//kotlin:core.bzl", "define_kt_toolchain")
load("@io_bazel_rules_kotlin//kotlin:android.bzl", "kt_android_library")

define_kt_toolchain(
    name = "kotlin_toolchain",
    api_version = "1.9",
    language_version = "1.9",
)

kt_android_library(
    name = "kotlin",
    srcs = ["Cat.kt"],
)

