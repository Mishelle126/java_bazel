
load("@rules_java//java:defs.bzl", "java_test")

java_test(
    name = "app_test",
    srcs = glob(["*Test.java"]),
    test_class = "com.ejemplo.app.MainTest",
    deps = [
        "//app1/src/main/java/com/ejemplo/app:app_lib",
        "@maven//:junit_junit",
    ],
)