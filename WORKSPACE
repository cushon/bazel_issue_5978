load("@bazel_tools//tools/build_defs/repo:git.bzl", "git_repository")
git_repository(
    name = "com_google_protobuf_javalite",
    remote = "git@github.com:protocolbuffers/protobuf.git",
    commit = "5e8916e881c573c5d83980197a6f783c132d4276",  # javalite branch
)

android_sdk_repository(
    name = "androidsdk",
    api_level = 27,
)
