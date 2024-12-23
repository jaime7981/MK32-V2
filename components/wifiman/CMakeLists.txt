idf_component_register(SRCS "wifi_manager.c"
                    INCLUDE_DIRS "include" "${CMAKE_SOURCE_DIR}/src"
                    REQUIRES esp_wifi nvs_flash plugins)
