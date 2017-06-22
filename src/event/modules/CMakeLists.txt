set(SOURCE_FILES ngx_aio_module.c
		ngx_devpoll_module.c
		ngx_epoll_module.c
		ngx_eventport_module.c
		ngx_kqueue_module.c
		ngx_rtsig_module.c
		ngx_poll_module.c
		ngx_select_module.c
		ngx_win32_select_module.c)
add_executable(event_modules ${SOURCE_FILES})
include_directories(../../event)
