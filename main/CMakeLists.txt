# VERSION: V4.3f CMake
idf_component_register(SRCS "main.c"
                    INCLUDE_DIRS "."
                    REQUIRES 
                        esp_lcd 
                        esp_psram 
                        esp_hw_support 
                        esp_lcd_ek79007 
                        nvs_flash 
                        driver)