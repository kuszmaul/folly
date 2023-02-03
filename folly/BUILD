cc_library(
    name = "cportability",
    hdrs = ["CPortability.h"],
    visibility = ["//visibility:public"],
)


cc_library(
    name = "cppattributes",
    hdrs = ["CppAttributes.h"],
    deps = [":portability"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "folly-config",
    hdrs = ["folly-config.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "portability",
    hdrs = ["Portability.h"],
    deps = ["//folly/portability:config", ":cportability"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "preprocessor",
    hdrs = ["Preprocessor.h"],
    deps = [":cportability"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "traits",
    hdrs = ["Traits.h"],
    deps = [":portability"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "utility",
    hdrs = ["Utility.h"],
    deps = [":cportability", ":portability", ":traits"],
    visibility = ["//visibility:public"],
)
