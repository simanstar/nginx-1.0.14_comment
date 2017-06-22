set(SOURCE_FILES ngx_http.c
		ngx_http.h
		ngx_http_busy_lock.c
		ngx_http_busy_lock.h
		ngx_http_cache.h
		ngx_http_config.h
		ngx_http_copy_filter_module.c
		ngx_http_core_module.c
		ngx_http_core_module.h
		ngx_http_file_cache.c
		ngx_http_header_filter_module.c
		ngx_http_parse.c
		ngx_http_parse_time.c
		ngx_http_postpone_filter_module.c
		ngx_http_request.c
		ngx_http_request.h
		ngx_http_request_body.c
		ngx_http_script.c
		ngx_http_script.h
		ngx_http_special_response.c
		ngx_http_upstream.h
		ngx_http_upstream.c
		ngx_http_upstream_round_robin.c
		ngx_http_upstream_round_robin.h
		ngx_http_variables.h
		ngx_http_variables.c
		ngx_http_write_filter_module.c)
add_executable(http ${SOURCE_FILES})
include_directories(. ../core ../event)
add_subdirectory(modules)