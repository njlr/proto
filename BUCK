include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'proto',
  header_only = True,
  header_namespace = 'boost/proto',
  exported_headers = subdir_glob([
    ('include/boost/proto', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
