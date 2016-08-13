boost_path = "upstream"

load("/tools/boost", "boost_library")

boost_library(
  name = "program_options",
  deps = [
    ":bind",
    ":throw_exception",
  ]
)

boost_library(
  name = "throw_exception",
)

boost_library(
  name = "bind",
)
