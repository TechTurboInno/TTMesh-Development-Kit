# TTMesh-Development-Kit

## About

A development tool for ble mesh or SIG mesh. Based on chip TLSR8269F512AT32 which is an SOC for muti-protocols. It includes motherboard with flash programmer on it, mesh node board and gateway board.

## Firmwares
* TT_DEV_RGBCW_V1.H.1.0.bin
  ble mesh light control demo with 5 channels adjustable.
  support both APP and IOT gateway

## User manuals
* not ready now

## Features
### Motherboard
1. Telink Flash Programmer
2. Debug port on board
3. Debug port export with voltage switch for 5V or 3.3V
4. 5 channels led include red, blue, green, cold white, warm white
5. Double H bridge for motor control
6. 4x4 press buttons
7. Buzzer
8. IR emitter

### Mesh node board
1. USB-A power supply with debug feature
2. Double press buttons
3. 5 channels led include red, blue, green, cold white, warm white
4. External power supply port
5. All IO port are connected to pins

### Mesh gateway board
1. USB-A power supply with debug feature
2. Double press buttons
3. 5 channels led include red, blue, green, cold white, warm white
4. External power supply port
5. All IO port are connected to pins
6. On board USB to serial chip CH340
7. On board switch for USB to CH340 or MCU
8. On board switch for UART from MCU to CH340 or External pins

## Author

Contact: techturbo <ai@techturbo.io>

## License

The TTMesh-Development-Kit is available under BSD 3-Clause license. See the LICENSE file for more info.
