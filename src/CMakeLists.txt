idf_component_register(SRCS "main.cpp" "keymap.c" "matrix.c" "keypress_handles.c"
                    INCLUDE_DIRS "."
                    REQUIRES "battery" "ble" "oled" "nvsfuncs" "plugins" "espnowmk32" "rotencoder")
