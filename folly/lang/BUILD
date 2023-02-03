cc_library(
    name = "Assume",
    hdrs = ["Assume.h"],
    deps = [
        "//folly:Portability",
        ":Hint",
    ],
    visibility = ["//visibility:public"],
)


cc_library(
    name = "Align",
    hdrs = ["Align.h"],
    deps = [
        "//folly:Portability",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Bits",
    hdrs = ["Bits.h"],
    deps = [
        "//folly:ConstexprMath",
        "//folly:Portability",
        "//folly:Traits",
        "//folly:Utility",
        "//folly/lang:Assume",
        "//folly/portability:Builtins",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Builtin",
    hdrs = ["Builtin.h"],
    deps = [
        "//folly:Portability",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "CArray",
    hdrs = ["CArray.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "CString",
    hdrs = ["CString.h"],
    srcs = ["CString.cpp"],
    deps = [
        "//folly:CppAttributes",
        "//folly/functional:Invoke",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "CustomizationPoint",
    hdrs = ["CustomizationPoint.h"],
    deps = [":staticconst"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Exception",
    hdrs = ["Exception.h"],
    deps = [
        "//folly:CPortability",
        "//folly:CppAttributes",
        "//folly:Likely",
        "//folly:Portability",
        "//folly:Traits",
        "//folly:Utility",
        ":SafeAssert",
        ":TypeInfo",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Hint",
    hdrs = ["Hint.h"],
    deps = [
        ":Hint-inl",
        "//folly:Portability",
        "//folly:Traits",
        "//folly/lang:SafeAssert",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Hint-inl",
    hdrs = ["Hint-inl.h"],
)

cc_library(
    name = "Launder",
    hdrs = ["Launder.h"],
    deps = [
        "//folly:CPortability",
        "//folly:Portability",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Pretty",
    hdrs = ["Pretty.h"],
    deps = [
        "//folly:Portability",
        "//folly/lang:CArray",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "SafeAssert",
    hdrs = ["SafeAssert.h"],
    srcs = ["SafeAssert.cpp"],
    deps = [
        "//folly:CppAttributes",
        "//folly:Portability",
        "//folly:Preprocessor",
        "//folly/lang:CArray",
        "//folly/detail:FileUtilDetail",
        "//folly/lang:ToAscii",
        "//folly/portability:SysTypes",
        "//folly/portability:Windows",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "staticconst",
    hdrs = ["StaticConst.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Thunk",
    hdrs = ["Thunk.h"],
    deps = [
        "//folly:Utility",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "ToAscii",
    hdrs = ["ToAscii.h"],
    srcs = ["ToAscii.cpp"],
    deps = [
        "//folly:ConstexprMath",
        "//folly:Likely",
        "//folly:Portability",
        "//folly:Utility",
        "//folly/lang:Align",
        "//folly/lang:CArray",
        "//folly/portability:Builtins",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "TypeInfo",
    hdrs = ["TypeInfo.h"],
    deps = [
        "//folly:CppAttributes",
        "//folly:Portability",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "UncaughtExceptions",
    hdrs = ["UncaughtExceptions.h"],
    srcs = ["UncaughtExceptions.cpp"],
    deps = [
        "//folly:CppAttributes",
        "//folly/functional:Invoke",
    ],
    visibility = ["//visibility:public"],
)
