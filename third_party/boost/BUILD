licenses(["notice"])

boost_path = "upstream"

load("/tools/boost", "boost_library")

#boost_library(
#  name = "program_options",
#  deps = [
#    ":throw_exception",
#    ":bind",
#    ":detail",
#    ":config",
#    ":type_traits",
#    ":iterator",
#  ]
#)

cc_library(
  name = "program_options",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/program_options/include/",
  ],
  hdrs = glob([
    boost_path + "/program_options/include/boost/**/*.hpp",
  ]),
  srcs = glob([
    boost_path + "/program_options/src/*.cpp",
  ]),
  deps = [
    ":any",
    ":throw_exception",
    ":bind",
    ":detail",
    ":config",
    ":type_traits",
    ":iterator",
    ":function",
    ":lexical_cast",
    ":smart_ptr",
    ":tokenizer",
  ]
)

cc_library(
  name = "tokenizer",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/tokenizer/include/",
  ],
  hdrs = glob([
    boost_path + "/tokenizer/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":iterator",
    ":assert",
    ":utility",
  ]
)

cc_library(
  name = "any",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/any/include/",
  ],
  hdrs = glob([
    boost_path + "/any/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":throw_exception",
    ":detail",
    ":config",
    ":type_traits",
    ":utility",
    ":mpl",
    ":static_assert",
    ":type_index",
  ]
)

cc_library(
  name = "type_index",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/type_index/include/",
  ],
  hdrs = glob([
    boost_path + "/type_index/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":config",
  ],
)

cc_library(
  name = "utility",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/utility/include/",
  ],
  hdrs = glob([
    boost_path + "/utility/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":core",
    ":config",
  ]
)

cc_library(
  name = "throw_exception",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/throw_exception/include/",
  ],
  hdrs = glob([
    boost_path + "/throw_exception/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":assert",
  ],
)

cc_library(
  name = "bind",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/bind/include/",
  ],
  hdrs = glob([
    boost_path + "/bind/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)


cc_library(
  name = "detail",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/detail/include/",
  ],
  hdrs = glob([
    boost_path + "/detail/include/boost/**/*pp",
  ]),
  srcs = [
  ],
)

cc_library(
  name = "config",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/config/include/",
  ],
  hdrs = glob([
    boost_path + "/config/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)

cc_library(
  name = "type_traits",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/type_traits/include/",
  ],
  hdrs = glob([
    boost_path + "/type_traits/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)

cc_library(
  name = "core",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/core/include/",
  ],
  hdrs = glob([
    boost_path + "/core/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)

cc_library(
  name = "mpl",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/mpl/include/",
  ],
  hdrs = glob([
    boost_path + "/mpl/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":preprocessor",
    ":move",
  ],
)

cc_library(
  name = "preprocessor",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/preprocessor/include/",
  ],
  hdrs = glob([
    boost_path + "/preprocessor/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)

cc_library(
  name = "move",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/move/include/",
  ],
  hdrs = glob([
    boost_path + "/move/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)

cc_library(
  name = "static_assert",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/static_assert/include/",
  ],
  hdrs = glob([
    boost_path + "/static_assert/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)

cc_library(
  name = "iterator",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/iterator/include/",
  ],
  hdrs = glob([
    boost_path + "/iterator/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":detail",
    ":static_assert",
  ],
)

cc_library(
  name = "assert",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/assert/include/",
  ],
  hdrs = glob([
    boost_path + "/assert/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":config",
  ],
)

cc_library(
  name = "function",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/function/include/",
  ],
  hdrs = glob([
    boost_path + "/function/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":detail",
    ":preprocessor",
    ":integer",
  ],
)

cc_library(
  name = "integer",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/integer/include/",
  ],
  hdrs = glob([
    boost_path + "/integer/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)

cc_library(
  name = "lexical_cast",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/lexical_cast/include/",
  ],
  hdrs = glob([
    boost_path + "/lexical_cast/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":config",
    ":range",
    ":numeric_conversion",
    ":array",
    ":container",
    ":math",
  ]
)

cc_library(
  name = "range",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/range/include/",
  ],
  hdrs = glob([
    boost_path + "/range/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    "concept_check",
  ]
)

cc_library(
  name = "concept_check",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/concept_check/include/",
  ],
  hdrs = glob([
    boost_path + "/concept_check/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":iterator",
    ":type_traits",
    ":utility",
    ":mpl",
    ":detail",
  ]
)

cc_library(
  name = "numeric_conversion",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/numeric_conversion/include/",
  ],
  hdrs = glob([
    boost_path + "/numeric_conversion/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":conversion",
  ]
)

cc_library(
  name = "conversion",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/conversion/include/",
  ],
  hdrs = glob([
    boost_path + "/conversion/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":config",
    ":assert",
    ":throw_exception",
    ":utility",
    ":typeof",
  ]
)

cc_library(
  name = "typeof",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/typeof/include/",
  ],
  hdrs = glob([
    boost_path + "/typeof/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":preprocessor",
    ":mpl",
  ]
)

cc_library(
  name = "array",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/array/include/",
  ],
  hdrs = glob([
    boost_path + "/array/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":detail",
    ":assert",
    ":static_assert",
    ":throw_exception",
    ":config",
    ":core",
    ":functional",
  ]
)

cc_library(
  name = "functional",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/functional/include/",
  ],
  hdrs = glob([
    boost_path + "/functional/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":config",
    ":utility",
  ]
)

cc_library(
  name = "container",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/container/include/",
  ],
  hdrs = glob([
    boost_path + "/container/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":config",
  ]
)

cc_library(
  name = "math",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/math/include/",
  ],
  hdrs = glob([
    boost_path + "/math/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
  deps = [
    ":config",
    ":predef",
  ]
)

cc_library(
  name = "predef",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/predef/include/",
  ],
  hdrs = glob([
    boost_path + "/predef/include/boost/**/*.h",
    boost_path + "/predef/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)

cc_library(
  name = "smart_ptr",
  visibility = ["//visibility:public"],
  includes = [
    boost_path + "/smart_ptr/include/",
  ],
  hdrs = glob([
    boost_path + "/smart_ptr/include/boost/**/*.hpp",
  ]),
  srcs = [
  ],
)

