load("@rules_java//java:defs.bzl", "java_library")

java_library(
    name = "stringtemplate4",
    srcs = glob([
        "src/**/*.java",
        "target/generated-sources/antlr3/**/*.java",
    ]),
    javacopts = ["-Xep:ChainingConstructorIgnoresParameter:OFF"],
    visibility = ["//visibility:public"],
    deps = [
        "@maven//:org_antlr_antlr_runtime",
    ],
)
