cc_library (
  name = "nlohmann",
  # This includes magic is needed because the hpp files include other htpp files using #include with <> instead of quotes
  includes = ["."],
  # I was not able to get glob to work and I gave up
  hdrs = [
    "nlohmann/json.hpp",
    "nlohmann/adl_serializer.hpp",
    "nlohmann/detail/conversions/from_json.hpp",
    "nlohmann/detail/conversions/to_chars.hpp",
    "nlohmann/detail/conversions/to_json.hpp",
    "nlohmann/detail/exceptions.hpp",
    "nlohmann/detail/input/binary_reader.hpp",
    "nlohmann/detail/input/input_adapters.hpp",
    "nlohmann/detail/input/json_sax.hpp",
    "nlohmann/detail/input/lexer.hpp",
    "nlohmann/detail/input/parser.hpp",
    "nlohmann/detail/input/position_t.hpp",
    "nlohmann/detail/iterators/internal_iterator.hpp",
    "nlohmann/detail/iterators/iterator_traits.hpp",
    "nlohmann/detail/iterators/iter_impl.hpp",
    "nlohmann/detail/iterators/iteration_proxy.hpp",
    "nlohmann/detail/iterators/json_reverse_iterator.hpp",
    "nlohmann/detail/iterators/primitive_iterator.hpp",
    "nlohmann/detail/json_pointer.hpp",
    "nlohmann/detail/json_ref.hpp",
    "nlohmann/detail/macro_scope.hpp",
    "nlohmann/detail/macro_unscope.hpp",
    "nlohmann/detail/meta/cpp_future.hpp",
    "nlohmann/detail/meta/detected.hpp",
    "nlohmann/detail/meta/is_sax.hpp",
    "nlohmann/detail/meta/type_traits.hpp",
    "nlohmann/detail/meta/void_t.hpp",
    "nlohmann/detail/output/binary_writer.hpp",
    "nlohmann/detail/output/output_adapters.hpp",
    "nlohmann/detail/output/serializer.hpp",
    "nlohmann/detail/value_t.hpp",
    "nlohmann/json_fwd.hpp",
  ],
  visibility = ["//visibility:public"],
)
