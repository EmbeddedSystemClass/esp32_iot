set(COMPONENT_SRCS "iot_base.c")
set(COMPONENT_ADD_INCLUDEDIRS ".")


# Embed the server root certificate into the final binary
set(COMPONENT_EMBED_TXTFILES ${PROJECT_PATH}/server_certs/ca_cert.pem)

register_component()
