idf_component_register(
    SRCS "esp_sparkbot_bsp.c" "esp_sparkbot_bsp_idf5.c"
    INCLUDE_DIRS "include" "include/bsp"
    PRIV_INCLUDE_DIRS "priv_include"
    REQUIRES driver spiffs touch_element
    PRIV_REQUIRES fatfs esp_lcd 
)
