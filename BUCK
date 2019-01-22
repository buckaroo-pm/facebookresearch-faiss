load('//:buckaroo_macros.bzl', 'buckaroo_deps')
load('//:subdir_glob.bzl', 'subdir_glob')

cxx_library(
  name = 'faiss',
  header_namespace = '',
  exported_headers = subdir_glob([
    ('', '*.h'),
  ]),
  srcs = glob([
    '*.cpp',
  ]),
  deps = buckaroo_deps(),
  visibility = [
    'PUBLIC',
  ],
)
