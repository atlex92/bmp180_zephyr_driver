# bmp180_zephyr_driver
Zephyr Sensor API support for Bosch BMP180 temperature and pressure sensor

# Usage
1. Create folder 'bmp180' in ZEPHYR_FODLER/zephyr/drivers/sensor directory
2. Add this line into zephyr/drivers/sensor/CMakeLists.txt:
'add_subdirectory_ifdef(CONFIG_BMP180        bmp180)'
