set(SOURCE_FILES ngx_event.c
		ngx_event.h
		ngx_event_accept.c
		ngx_event_busy_lock.c
		ngx_event_busy_lock.h
		ngx_event_connect.c
		ngx_event_connect.h
		ngx_event_mutex.c
		ngx_event_openssl.c
		ngx_event_openssl.h
		ngx_event_pipe.c
		ngx_event_pipe.h
		ngx_event_posted.c
		ngx_event_posted.h
		ngx_event_timer.c
		ngx_event_timer.h)
add_executable(event ${SOURCE_FILES})
include_directories(. ../core ../os/unix)
add_subdirectory(modules)