set(SOURCE_FILES ngx_mail.c
		ngx_mail.h
		ngx_mail_core_module.c
		ngx_mail_auth_http_module.c
		ngx_mail_handler.c
		ngx_mail_imap_handler.c
		ngx_mail_imap_module.c
		ngx_mail_imap_module.h
		ngx_mail_parse.c
		ngx_mail_pop3_module.c
		ngx_mail_pop3_handler.c
		ngx_mail_pop3_module.h
		ngx_mail_proxy_module.c
		ngx_mail_smtp_handler.c
		ngx_mail_smtp_module.c
		ngx_mail_smtp_module.h
		ngx_mail_ssl_module.c
		ngx_mail_ssl_module.h)
add_executable(mail ${SOURCE_FILES})
include_directories(.)