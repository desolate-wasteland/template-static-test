load("@genrules//gcs:index.bzl", "gcs_deploy")

gcs_deploy(
    name = "deploy",
    bucket_name = "my-really-cool-static-bucket-82",
    deps = [":static"],
)

filegroup(
    name = "static",
    srcs = glob([
        "static/**",
    ]),
)
