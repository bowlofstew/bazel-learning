load("@io_bazel_rules_scala//scala:scala.bzl", "scala_specs2_junit_test")

scala_specs2_junit_test(
    name = "scala_example_test",
    size = "small",
    srcs = ["ExampleTest.scala"],
    deps = ["//m0/src/main/scala/com/example:scala_example"],
    suffixes = ["Test"],
)