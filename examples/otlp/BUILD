cc_binary(
    name = "example_otlp_grpc",
    srcs = [
        "grpc_main.cc",
    ],
    deps = [
        "//api",
        "//examples/common/foo_library:common_foo_library",
        "//exporters/otlp:otlp_grpc_exporter",
        "//sdk/src/trace",
    ],
)

cc_binary(
    name = "example_otlp_http",
    srcs = [
        "http_main.cc",
    ],
    deps = [
        "//api",
        "//examples/common/foo_library:common_foo_library",
        "//exporters/otlp:otlp_http_exporter",
        "//sdk/src/trace",
    ],
)

cc_binary(
    name = "example_otlp_http_log",
    srcs = [
        "http_log_main.cc",
    ],
    deps = [
        "//api",
        "//examples/common/logs_foo_library:common_logs_foo_library",
        "//exporters/otlp:otlp_http_exporter",
        "//exporters/otlp:otlp_http_log_exporter",
        "//sdk/src/trace",
    ],
)
