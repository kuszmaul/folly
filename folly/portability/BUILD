cc_library(
    name = "Builtins",
    hdrs = ["Builtins.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Config",
    hdrs = ["Config.h"],
    visibility = ["//visibility:public"],
    deps = ["//folly:folly-config"],
)

cc_library(
    name = "Constexpr",
    hdrs = ["Constexpr.h"],
    deps = [
        "//folly:CPortability",
        "//folly:Portability",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Malloc",
    hdrs = ["Malloc.h"],
    visibility = ["//visibility:public"],
    deps = [
        "//folly:CPortability",
        ":Config"
    ],
)

cc_library(
    name = "SysTypes",
    hdrs = ["SysTypes.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Windows",
    hdrs = ["Windows.h"],
    visibility = ["//visibility:public"],
)
