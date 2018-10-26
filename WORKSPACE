git_repository(
    name = "io_bazel_rules_python",
    remote = "https://github.com/bazelbuild/rules_python.git",
    commit = "8b5d0683a7d878b28fffe464779c8a53659fc645",
)

load("@io_bazel_rules_python//python:pip.bzl", "pip_import", "pip_repositories")
#pip_repositories()
pip_import(
    name="iris_deps",
    requirements="//zoltar_tests/training/iris:requirements.txt"
)
load("@iris_deps//:requirements.bzl", "pip_install")
pip_install()
