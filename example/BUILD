%%writefile /content/test/example/BUILD 
cc_binary(
    name = "EigenDemo",
    srcs = ["main.cpp"],
    copts = ["-Iexternal/eigen"],
    deps = [
        "@eigen",
    ],
)

