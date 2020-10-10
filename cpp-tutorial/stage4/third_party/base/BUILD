load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "hello-time",
    srcs = ["hello-time.cc"],
    hdrs = ["hello-time.h"],
    copts = ["-Ithird_party/base"],
    visibility = ["//main:__pkg__"],
)
