set(SOURCE_FILES ngx_http_myupstream_module.c ngx_http_mytest_module.c)

add_executable(myupstream_module ${SOURCE_FILES})
target_link_libraries(myupstream_module)
include_directories(../src/core ../src/os/unix ../src/event ../objs ../src/http)
link_directories(${PROJECT_SOURCE_DIR}/objs/src)