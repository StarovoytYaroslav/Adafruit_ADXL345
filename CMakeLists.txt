idf_component_register(
    SRCS "Adafruit_ADXL345_U.cpp"
    INCLUDE_DIRS "."
    REQUIRES arduino-esp32 Adafruit_BusIO Adafruit_Sensor
)
