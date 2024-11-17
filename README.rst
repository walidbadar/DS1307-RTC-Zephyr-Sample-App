.. zephyr:code-sample:: rtc
   :name: Real-Time Clock (RTC) sample
   :relevant-api: rtc_interface

   Reads date and time data from the Real-Time Clock.

Overview
********

This sample shows how to use the :ref:`rtc driver API <rtc_api>`
to read date and time from the RTC and display on the console
and can be built and executed on boards supporting RTC.

Building and Running
********************

This application can be built on :ref:`stm32f3_disco <stm32f3_disco>` as follows:

.. zephyr-app-commands::
   :zephyr-app: samples/drivers/rtc
   :board: stm32f3_disco
   :goals: build
   :compact:

Sample Output
=============

.. code-block:: console

   RTC date and time: 2024-11-17 04:21:47
   RTC date and time: 2024-11-17 04:21:48
   RTC date and time: 2024-11-17 04:21:49

   <repeats endlessly>
   
