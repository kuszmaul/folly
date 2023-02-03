cc_library(
    name = "F14Defaults",
    hdrs = ["F14Defaults.h"],
    deps = ["//folly/container:HeterogeneousAccess-fwd"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "F14IntrinsicsAvailability",
    hdrs = ["F14IntrinsicsAvailability.h"],
    deps = [
        "//folly:Portability",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "F14Mask",
    hdrs = ["F14Mask.h"],
    deps = [
        "//folly:Bits",
        "//folly:ConstexprMath",
        "//folly:Likely",
        "//folly:Portability",
        "//folly/lang:Assume",
        "//folly/lang:SafeAssert",
    ],
    visibility = ["//visibility:public"],
)


cc_library(
    name = "F14Policy",
    hdrs = ["F14Policy.h"],
    deps = [
        "//folly:Memory",
        "//folly:Portability",
        "//folly:Traits",
        "//folly:Unit",
        "//folly/container:HeterogeneousAccess",
        "//folly/container/detail:F14Table",
        "//folly/hash:Hash",
        "//folly/lang:Align",
        "//folly/lang:SafeAssert",
        "//folly/memory:Malloc",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "F14SetFallback",
    hdrs = ["F14SetFallback.h"],
    deps = [":F14Table", ":Util"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "F14Table",
    hdrs = ["F14Table.h"],
    srcs = ["F14Table.cpp"],
    deps = [
        "//folly:Bits",
        "//folly:ConstexprMath",
        "//folly:Likely",
        "//folly:Portability",
        "//folly:ScopeGuard",
        "//folly:Traits",
        "//folly/functional:Invoke",
        "//folly/lang:Align",
        "//folly/lang:Assume",
        "//folly/lang:Exception",
        "//folly/lang:Launder",
        "//folly/lang:Pretty",
        "//folly/lang:SafeAssert",
        "//folly/portability:Builtins",
        "//folly/container:HeterogeneousAccess",
        "//folly/container/detail:F14Defaults",
        "//folly/container/detail:F14IntrinsicsAvailability",
        "//folly/container/detail:F14Mask",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Util",
    hdrs = ["Util.h"],
    deps = [
        "//folly:Traits",
        "//folly/functional:ApplyTuple",
    ],
    visibility = ["//visibility:public"],
)
