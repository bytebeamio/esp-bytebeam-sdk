idf_component_register(SRCS "bytebeam_sdk.c" "bytebeam_esp_hal.c"
                       INCLUDE_DIRS "include"
                       PRIV_REQUIRES "json"
                                     "mqtt"
                                     "nvs_flash"
                                     "esp_https_ota"
                                     "app_update"
                                     "spiffs")
