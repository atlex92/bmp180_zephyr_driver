# BMP180 Zephyr driver
Zephyr Sensor API support for Bosch BMP180 temperature and pressure sensor

### Usage
1. Create folder `/bmp180` in `ZEPHYR_FODLER/zephyr/drivers/sensor` directory
2. Add this line into `ZEPHYR_FODLER/zephyr/drivers/sensor/CMakeLists.txt`: `add_subdirectory_ifdef(CONFIG_BMP180     bmp180)`
3. Add this line into `ZEPHYR_FODLER/zephyr/drivers/sensor/KConfig`: `source "drivers/sensor/bmp180/Kconfig"`
4. Copy `bosch,bmp180-i2c.yaml` file in `ZEPHYR_FODLER/zephyr/dts/bindings/sensor` folder

### Example
![image](https://user-images.githubusercontent.com/14805012/171182405-656d8524-59d4-4153-b498-f645a6f307dc.png)
