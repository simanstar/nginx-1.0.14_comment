set(SOURCE_FILES ngx_cpp_test_module.cpp ngx_google_perftools_module.c)
add_executable(misc ${SOURCE_FILES})
include_directories(. ../core)