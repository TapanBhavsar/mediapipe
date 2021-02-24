cc_library(
    name = "dlib",
    hdrs = glob(["dlib-*/dlib/**/*.h"]),
    srcs = glob(["dlib-*/dlib/all/source.cpp"]),
    includes = ["."],
    linkstatic = 1,
    strip_include_prefix = glob(["dlib-*/.gitignore"])[0].split("/", 1)[0],
    visibility = ["//visibility:public"],
)