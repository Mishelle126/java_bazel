load("@rules_java//java:defs.bzl", "java_test")

java_test(
    name = "app2_test",
    srcs = ["MainTest.java"],
    test_class = "java_bazel.app2.test.java.com.ejemplo.app2.MainTest",
    deps = [
        "//app2/src/main/java/com/ejemplo/app2:app2_lib",
        "@maven//:junit_junit",
        "@maven//:org_hamcrest_hamcrest_core",
    ],
)
