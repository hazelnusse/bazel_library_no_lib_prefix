cc_library(
    name = "foo",
    hdrs = ["foo.hpp"],
    srcs = ["foo.cpp"]
)

cc_binary(
    name = "foo.so",
    linkshared = 1,
    deps = [":foo"]
)
