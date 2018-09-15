# bazel_issue_5978
Repro for https://github.com/bazelbuild/bazel/issues/5978

Both fail:
```
$ bazel version
Build label: 0.17.1
Build target: bazel-out/darwin-opt/bin/src/main/java/com/google/devtools/build/lib/bazel/BazelServer_deploy.jar
Build time: Fri Sep 14 10:38:52 2018 (1536921532)
Build timestamp: 1536921532
Build timestamp as int: 1536921532
```

```
$ bazel build //:sample
$ bazel build //:sample --config jdk8
```
