inc = include_directories('include')
sources_ = files('main.cpp')

subdir('source')

exe = executable('example_task', sources:sources_, include_directories:inc, link_with:source_lib)

subdir('test')

