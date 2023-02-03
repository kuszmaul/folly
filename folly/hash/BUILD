cc_library(
    name = "Hash",
    hdrs = ["Hash.h"],
    visibility = ["//visibility:public"],
    deps = [
        "//folly:CPortability",
        "//folly:Traits",
        "//folly:Utility",
        "//folly/functional:ApplyTuple",
        "//folly/hash:SpookyHashV1",
        "//folly/hash:SpookyHashV2",
        "//folly/lang:Bits",
    ]
)

cc_library(
    name = "SpookyHashV1",
    hdrs = ["SpookyHashV1.h"],
    srcs = ["SpookyHashV1.cpp"],
    visibility = ["//visibility:public"],
    deps = [
        "//folly:CppAttributes",
    ],
)

cc_library(
    name = "SpookyHashV2",
    hdrs = ["SpookyHashV2.h"],
    srcs = ["SpookyHashV2.cpp"],
    visibility = ["//visibility:public"],
    deps = [
        "//folly:CppAttributes",
        "//folly:Portability",
    ],
)
