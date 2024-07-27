.. _lsm303dlhc:

LSM303DLHC: Magnetometer and Accelerometer data Monitor
#######################################################

Overview
********
This sample application periodically reads magnetometer and accelerometer data
from the LSM303DLHC eCompass module's sensors, and displays the sensor data
on the console.

Requirements
************

This sample uses the LSM303DLHC, ST MEMS system-in-package featuring a
3D digital linear acceleration sensor and a 3D digital magnetic sensor,
controlled using the I2C interface.

References
**********

For more information about the LSM303DLHC eCompass module, see
https://www.st.com/en/mems-and-sensors/lsm303dlhc.html

Building and Running
********************

This project outputs sensor data to the console. It requires a LSM303DLHC
system-in-package, which is present on the stm32f3_disco board

.. zephyr-app-commands::
   :zephyr-app: samples/rtc/ds1307
   :board: esp32_devkitc_wroom
   :goals: build
   :compact:

Sample Output
=============
   Current RTC time: 2024-07-28 02:46:00
   Current RTC time: 2024-07-28 02:46:01
   Current RTC time: 2024-07-28 02:46:02
   Current RTC time: 2024-07-28 02:46:03
   Current RTC time: 2024-07-28 02:46:04

.. code-block:: console

   <repeats endlessly every 1 seconds>
