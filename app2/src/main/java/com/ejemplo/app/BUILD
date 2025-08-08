load("@rules_java//java:defs.bzl", "java_binary", "java_library")

java_library(
    name = "app2_lib",
    srcs = ["Main.java", "Area.java"],
    visibility = ["//visibility:public"],
)

java_binary(
    name = "app2",
    main_class = "main.java.com.ejemplo.app2.Main",
    runtime_deps = [":app2_lib"],
)
