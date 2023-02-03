cc_library(
    name = "Bits",
    hdrs = ["Bits.h"],
    deps = [
        "//folly/lang:Bits",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "CPortability",
    hdrs = ["CPortability.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "CppAttributes",
    hdrs = ["CppAttributes.h"],
    visibility = ["//visibility:public"],
    deps = [":Portability"],
)

cc_library(
    name = "CpuId",
    hdrs = ["CpuId.h"],
    visibility = ["//visibility:public"],
    deps = [":Portability"],
)

cc_library(
    name = "folly-config",
    hdrs = ["folly-config.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Portability",
    hdrs = ["Portability.h"],
    visibility = ["//visibility:public"],
    deps = [
        ":CPortability",
        "//folly/portability:Config",
    ],
)

cc_library(
    name = "Preprocessor",
    hdrs = ["Preprocessor.h"],
    visibility = ["//visibility:public"],
    deps = [":CPortability"],
)

cc_library(
    name = "ScopeGuard",
    hdrs = ["ScopeGuard.h"],
    srcs = ["ScopeGuard.cpp"],
    visibility = ["//visibility:public"],
    deps = [
        "//folly:Portability",
        "//folly:Preprocessor",
        "//folly:Utility",
        "//folly/lang:Exception",
        "//folly/lang:UncaughtExceptions",
    ],
)

cc_library(
    name = "Traits",
    hdrs = ["Traits.h"],
    visibility = ["//visibility:public"],
    deps = [":Portability"],
)

cc_library(
    name = "Utility",
    hdrs = ["Utility.h"],
    visibility = ["//visibility:public"],
    deps = [
        ":CPortability",
        ":Portability",
        ":Traits",
    ],
)

cc_library(
    name = "Memory",
    hdrs = ["Memory.h"],
    deps = [
        ":ConstexprMath",
        ":Likely",
        ":Portability",
        ":Traits",
        ":Utility",
        "//folly/functional:Invoke",
        "//folly/lang:Align",
        "//folly/lang:Exception",
        "//folly/lang:Thunk",
        "//folly/memory:Malloc",
        "//folly/portability:Config",
        "//folly/portability:Malloc",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "ConstexprMath",
    hdrs = ["ConstexprMath.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Likely",
    hdrs = ["Likely.h"],
    deps = [
        "//folly/lang:Builtin",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Range",
    hdrs = ["Range.h"],
    deps = [
        "//folly:Portability",
        "//folly/hash:SpookyHashV2",
        "//folly/lang:CString",
        "//folly/lang:Exception",
        "//folly/portability:Constexpr",
        "//folly:CpuId",
        "//folly:Likely",
        "//folly:Traits",
        "//folly/detail:RangeCommon",
        "//folly/detail:RangeSse42",
    ],
    visibility = ["//visibility:public"],
)


cc_library(
    name = "Unit",
    hdrs = ["Unit.h"],
    visibility = ["//visibility:public"],
)
