This repository contains all the necessary files (libraries) needed to create
our Search and Recover (rescue?) bots in AHS's Electronics Workshop class.


all files are dependencies which have been copy-pasted in from their respective repositories in this same GitHub organization as well as AdaFruits, and they will ***not*** be kept up to date here.
Up to date links to the library files used can be found here: [DRV8833](https://github.com/AHSPC/DRV8833_micropython), [VL53L4CD](https://github.com/AHSPC/VL53L4CD_micropython), [AS7341](https://github.com/AHSPC/AS7341_micropython), [mpu9259](https://github.com/AHSPC/mpu9250), [i2c_device](https://github.com/AHSPC/adafruit_i2c_device_micropython), [register](https://github.com/adafruit/Adafruit_CircuitPython_Register/tree/main/adafruit_register), 

- ak8963.py - Magnetometer
- as7341.py - Color Sensor
- drv8833.py - Motor Controller
- mpu6500.py - Accelerometer and GyroScope
- mpu9250.py - Wrapper for the Magnetometer(ak8963.py), Accelerometer and GyroScope(mpu6500.py)
- vl53l4cd.py - Distance
- web_dashboard.py - Web Logging

- i2c_device.py, i2c_bit.py, i2c_bits.py, i2c_struct.py: adafruit libraries from `i2c_device` and `register` projects (linked above)

**TODO:**
- Add a main.py/test.py with web logging, as well as DRV5053VAQLPGM (hall effect sensor) usage (which doesn't need and separate libraries)
