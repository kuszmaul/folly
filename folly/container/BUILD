cc_library(
    name = "F14Set",
    hdrs = ["F14Set.h"],
    visibility = ["//visibility:public"],
    deps = [
        ":F14Set-fwd",
        "//folly/container/detail:F14Policy",
        "//folly/container/detail:F14Table",
        "//folly/container/detail:Util",
        "//folly/container/detail:F14SetFallback",
        ":View",
    ],
)

cc_library(
    name = "F14Set-fwd",
    hdrs = ["F14Set-fwd.h"],
    deps = ["//folly/memory:MemoryResource",
            "//folly/container/detail:F14Policy",],
)

cc_library(
    name = "HeterogeneousAccess-fwd",
    hdrs = ["HeterogeneousAccess-fwd.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "HeterogeneousAccess",
    hdrs = ["HeterogeneousAccess.h"],
    deps = [
        "//folly:Range",
        "//folly:Traits",
        "//folly/container:HeterogeneousAccess-fwd",
        "//folly/hash:Hash",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "SparseByteSet",
    hdrs = ["SparseByteSet.h"],
    deps = ["//folly:CPortability",],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "View",
    hdrs = ["View.h"],
    deps = ["//folly/functional:Invoke",
            "//folly/lang:CustomizationPoint"],
)
