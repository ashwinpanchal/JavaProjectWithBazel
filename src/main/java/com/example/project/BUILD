java_binary(
    name = "hello_world",
    srcs = ["HelloWorld.java"],
    main_class = "main.java.com.example.project.HelloWorld",
    deps = [
        ":util_lib",
    ],
)

java_library(
    name = "util_lib",
    srcs = glob(["util/*.java"]),
    visibility = ["//visibility:public"],
)