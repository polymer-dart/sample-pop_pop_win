# Automatically generated by "pub global run bazel:bazelify".
# DO NOT MODIFY BY HAND

# Include the Dart SDK and language extensions for Bazel.
git_repository(
    name = "io_bazel_rules_dart",
    remote = "https://github.com/dart-lang/rules_dart",
    # Corresponds to https://github.com/dart-lang/rules_dart at branch - raw_ppw_fun
    commit = "4bdd101f5a669d132bfde72b527825db4bcf8479",
)
load(
    "@io_bazel_rules_dart//dart/build_rules:repositories.bzl",
    "dart_repositories",
)
dart_repositories()

# Pub package dependencies that are needed by the Dart BUILD rules.
load(
    "@io_bazel_rules_dart//dart/build_rules:pub.bzl",
    "pub_repositories",
)
pub_repositories()

# Include the packages resolved from pubspec.yaml.
load(
    "//:packages.bzl",
    "bazelify",
)
bazelify()
