load("@bazel_latex//:latex.bzl", "latex_document")

latex_document(
    name = "resume",
    main = "resume.tex",
    srcs = [
        "@bazel_latex//packages:geometry",
        "@bazel_latex//packages:array",
        "@bazel_latex//packages:graphicx",
        "@bazel_latex//packages:hyperref",
        "@bazel_latex//packages:xcolor",
        "@bazel_latex//packages:tabularx",
        "@bazel_latex//packages:verbatim",
    ],
)
