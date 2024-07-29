# Environment Sensor MYRA SiP Baseboard
Copyright (c) 2024 [Antmicro](https://www.antmicro.com/)

![Visualization](img/environment-sensor-sip-baseboard_top_photo_paper_black.png)

## Overview

This repository contains open hardware design files for Antmicro's Environment Sensor Board variant which includes the [MYRA SiP](https://github.com/antmicro/myra-sip) as well as temperature, pressure and humidity sensors.

The design files were prepared in KiCad 7.

## Key features

* Environment sensor SiP (with STM32G491REI6 MCU, 128kB FRAM, FTDI FT231XQ USB to UART converter)

* 50.00 mm X 26.50 mm PCB SIZE

* USB-C Connector for data and power

* SHT45 temperature + humidity sensor:
	* Typ. relative humidity accuracy ±1% RH
	* Operating relative humidity range 0 - 100% RH
	* Typ. temperature accuracy ±0.1 °C
	* Operating temperature range (-40) - (+125) °C

* BME280 temperature + humidity + pressure sensor:
	* Typ. relative humidity accuracy ±3% RH
	* Operating relative humidity range 10 - 100% RH
	* Typ. temperature accuracy ±1 °C
	* Operating temperature range (-40) - (+85) °C
	* Typ. pressure accuracy ±1 hPa
	* Operating pressure range 300 - 1100 hPa

* QWIIC Connectors

* RTC battery backup

## Repository structure

The main repository directory contains KiCad PCB project files, a LICENSE, and a README.
The remaining files are stored in the following directories:

* `img` - contains graphics for this README

## Licensing
This project is published under the [Apache-2.0](https://github.com/antmicro/myra-sip/blob/main/LICENSE) license.
