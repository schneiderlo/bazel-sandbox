load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

# Catch2 is a testing library.
http_archive(
    name = "com_github_catch2",
    strip_prefix = "Catch2-2.13.4",
    urls = ["https://github.com/catchorg/Catch2/archive/v2.13.4.tar.gz"],
    sha256 = "e7eb70b3d0ac2ed7dcf14563ad808740c29e628edde99e973adad373a2b5e4df"
)

# {fmt} is a formatting library. 
http_archive(
    name = "com_github_fmt",
    strip_prefix = "fmt-7.1.3",
    urls = ["https://github.com/fmtlib/fmt/releases/download/7.1.3/fmt-7.1.3.zip"],
    sha256 = "5d98c504d0205f912e22449ecdea776b78ce0bb096927334f80781e720084c9f",
    build_file = "@//bazel/external:fmtlib.BUILD",
)

# spdlog is logging library.
http_archive(
    name = "com_github_spdlog",
    strip_prefix = "spdlog-1.8.2",
    urls = ["https://github.com/gabime/spdlog/archive/v1.8.2.tar.gz"],
    sha256 = "e20e6bd8f57e866eaf25a5417f0a38a116e537f1a77ac7b5409ca2b180cec0d5",
    build_file = "@//bazel/external:spdlog.BUILD",
)