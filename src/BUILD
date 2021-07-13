cc_binary(
  name = "main",
  srcs = ["main.cpp"]
)

cc_library(
  name = "add",
  hdrs = ["add.hpp"],
  srcs = ["add.cpp"]
)

cc_test(
  name = "test_add",
  srcs = ["add_test.cpp"],
  deps = [
    ":add",
    "@com_google_googletest//:gtest_main",
  ],
)
