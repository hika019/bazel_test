cc_library(
    name = "greet",
    srcs = ["greet.cc"],
    hdrs = ["greet.h"],
)

cc_binary(
    name = "helloworld",
    srcs = ["helloworld.cc"],
    deps = [":greet", "//lib:time",],
)