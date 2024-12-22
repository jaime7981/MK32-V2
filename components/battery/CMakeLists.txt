idf_component_register(SRCS "battery_monitor.c"
                    INCLUDE_DIRS "include" "${CMAKE_SOURCE_DIR}/src"
                    REQUIRES driver oled)
