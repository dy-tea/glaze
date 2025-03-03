project(
   'glaze',
   'cpp',
   version: '4.4.3',
   license: 'MIT',
   default_options: ['cpp_std=c++23'],
)

include = include_directories('include')

glaze = static_library('glaze', sources: 'src/main.cpp', include_directories: include)

glaze_dep = declare_dependency(link_with: glaze, include_directories: include)
