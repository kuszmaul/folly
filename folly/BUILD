cc_library(
    name = "cportability",
    hdrs = ["CPortability.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "cppattributes",
    hdrs = ["CppAttributes.h"],
    visibility = ["//visibility:public"],
    deps = [":portability"],
)

cc_library(
    name = "folly-config",
    hdrs = ["folly-config.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "portability",
    hdrs = ["Portability.h"],
    visibility = ["//visibility:public"],
    deps = [
        ":cportability",
        "//folly/portability:config",
    ],
)

cc_library(
    name = "preprocessor",
    hdrs = ["Preprocessor.h"],
    visibility = ["//visibility:public"],
    deps = [":cportability"],
)

cc_library(
    name = "traits",
    hdrs = ["Traits.h"],
    visibility = ["//visibility:public"],
    deps = [":portability"],
)

cc_library(
    name = "utility",
    hdrs = ["Utility.h"],
    visibility = ["//visibility:public"],
    deps = [
        ":cportability",
        ":portability",
        ":traits",
    ],
)
