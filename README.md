# ESP32 High Voltage Encoder Controller

Sponsored by [TowerSoftware](http://www.towersoftwareltd.com/)

<img src="https://github.com/hotteshen/esp32c3-high-voltage-encoder/blob/master/doc/preview-3d-v1.1.png?raw=true">

## Overview

An ESP32-C3 powered encoder controller with voltage level translator and CAN transciever.

* ESP32-C3
* 3-ch Voltage level translator using MOSFETs
* CAN bus transceiver
* RS232 transceiver

## Revisions


### 1.1

* Diodes between +5V and VUSB rails are removed.
* Added 2 x 100uF and 1 x 47uF capacitors to supply enough current when wifi starts up

### 1.0

* Initial release.
