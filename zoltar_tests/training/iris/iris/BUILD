load("@io_bazel_rules_python//python:python.bzl", "py_binary", "py_library", "py_test")
load("@iris_deps//:requirements.bzl", "requirement")

py_binary(
  name = "tensorflow",
  srcs = ["tensorflow.py"],
  deps = [
      requirement("tensorflow"),
      requirement("spotify_tensorflow")
  ]
)
