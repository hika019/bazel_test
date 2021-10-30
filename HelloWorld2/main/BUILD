cc_library(
    name = "greet",
    srcs = ["hello-greet.cc"],
    hdrs = ["greet.h"]
)

cc_binary(
    name = "helloworld",
    srcs = ["hello-world.cc"],
    deps = [
        ":greet",
    ],
)