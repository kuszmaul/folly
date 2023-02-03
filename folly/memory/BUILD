cc_library(
    name = "MemoryResource",
    hdrs = ["MemoryResource.h"],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "Malloc",
    hdrs = ["Malloc.h"],
    deps = [
        "//folly:Portability",
        "//folly/lang:Bits",
        "//folly/lang:Exception",
        "//folly/memory/detail:MallocImpl",
        "//folly/portability:Malloc",
    ],
    visibility = ["//visibility:public"],
)
