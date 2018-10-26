load("@io_bazel_rules_python//python:python.bzl", "py_binary", "py_library", "py_test")
load("@iris_deps//:requirements.bzl", "requirement")

py_binary(
  name = "train_iris_tensorflow",
  srcs = ["train_iris_tensorflow.py"],
  deps = [
      requirement("tensorflow"),
      requirement("spotify_tensorflow")
  ]
)

py_binary(
  name = "train_iris_xgboost",
  srcs = ["train_iris_xgboost.py"],
  deps = [
      requirement("numpy"),
      requirement("xgboost"),
      requirement("tensorflow"),
      requirement("spotify_tensorflow")
  ]
)
