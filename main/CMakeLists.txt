idf_component_register(
                    SRCS         "main.c"
                                 "url_decode.c"
                                 "nvs.c"
                                 "wifi.c"
                                 "gpio.c"
                                 "timer.c"
                                 "mdns_local.c"
                                 "http_client.c"
                                 "json.c"
                                 "http_server.c"
                                 "ota_task.c"
                    INCLUDE_DIRS "include"
                    EMBED_TXTFILES ${project_dir}/server_certs/ca_cert.pem)
