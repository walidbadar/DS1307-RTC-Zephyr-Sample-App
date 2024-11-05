.. zephyr:code-sample:: ds1307
   :name: Real-Time Clock (RTC) read sample
   :relevant-api: rtc_interface

   Reads date and time data from the DS1307 Real-Time Clock.

Overview
********

This sample shows how to use the :ref:`rtc driver API <rtc_api>`
to read date and time data from the DS1307 RTC module,
and display on the console.

Building and Running
********************

Note that this sample requires a ``esp32_devkitc_wroom``
wired to a DS1307 RTC module. See the overlay file
:zephyr_file:`samples/drivers/rtc/ds1307/boards/esp32_devkitc_wroom_procpu.overlay` 
for wiring configuration.

.. zephyr-app-commands::
   :zephyr-app: samples/drivers/rtc/ds1307
   :board: esp32_devkitc_wroom
   :goals: build flash
   :compact:

Sample Output
=============

 Current RTC time: 2024-07-28 02:46:00
.. code-block:: console

   <repeats endlessly every 1 seconds>
