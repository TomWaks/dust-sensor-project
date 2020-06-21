# Dust Sensor Project
This project was developed as part of an Engineer's Thesis.

The project focuses on measurement and documentation concentrations of PM2.5/PM10 and other parameters of meteorological, taking into account the location of the measuring station.  

<kbd>![Alt text](images/device.png)</kbd>

# Description 
The project can be divided on parts:
* measuring device:
  - [Microcontroller ES8266](https://github.com/TomWaks/esp8266-dust-sensor-project)
  - [Microcontroller Nucleo STM32F4](https://github.com/TomWaks/stm32-dust-sensor-project)
  - others: optical sensor dust, sensor temperature, humidity and pressure, display OLED, reader card microSD, LED
* [Mobile Application](https://github.com/TomWaks/android-dust-sensor-project)
* [Server](https://github.com/TomWaks/server-dust-sensor-project)

## Description
The possibilities of this project are:
- measurement of concentrations PM2.5/PM10 using a optical dust sensor
- measurement meteorology parameters: air temperature, relative humidity and atmospheric pressure using digital sensor
- save measurement results on a microSD card
- save measurement results to MySQL Database
- determining location based on information about cell towers and WIFI nodes that the module WIFI can detect
- presentation of measurement results on build-in display
