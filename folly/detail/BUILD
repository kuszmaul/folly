cc_library(
    name = "FileUtilDetail",
    hdrs = ["FileUtilDetail.h",],
    srcs = ["FileUtilDetail.cpp",],
    deps = [
        "//folly/portability:SysTypes",
    ],
    visibility = ["//visibility:public"],
)


cc_library(
    name = "RangeCommon",
    hdrs = ["RangeCommon.h"],
    srcs = ["RangeCommon.cpp"],
    deps = [
        "//folly:Likely",
        "//folly/container:SparseByteSet",
    ],
    visibility = ["//visibility:public"],
)

cc_library(
    name = "RangeSse42",
    hdrs = ["RangeSse42.h"],
    srcs = ["RangeSse42.cpp"],
    deps = [
        "//folly:Portability",
        ":RangeCommon",
    ],
    visibility = ["//visibility:public"],
)
