load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "hello-time",
    srcs = ["hello-time.cc"],
    hdrs = ["include/hello-time.h"],
    copts = ["-Ithird_party/base/include"],
    visibility = ["//main:__pkg__"],
)
