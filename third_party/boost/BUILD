licenses(["notice"])

boost_path = "upstream"

load("/tools/boost", "boost_library")

boost_library(
  name = "program_options",
  deps = [
    ":throw_exception",
    ":bind",
    ":detail",
    ":config",
    ":type_traits",
    ":iterator",
  ]
)

boost_library(
  name = "throw_exception",
)

boost_library(
  name = "bind",
)

boost_library(
  name = "detail"
)

boost_library(
  name = "config",
)

boost_library(
  name = "type_traits",
  deps = [
    ":core",
    ":mpl",
    ":static_assert",
  ]
)

boost_library(
  name = "core",
)

boost_library(
  name = "mpl",
  deps = [
    ":preprocessor",
    ":move",
  ]
)

boost_library(
  name = "preprocessor",
)

boost_library(
  name = "move",
)

boost_library(
  name = "static_assert",
)

boost_library(
  name = "iterator",
  deps = [
    ":detail",
    ":static_assert",
  ],
)
