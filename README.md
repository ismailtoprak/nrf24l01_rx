
# NRF24L01 Full-Duplex Project
----
- This project is provide a full-duplex communication between two NRF24L01 modules.

## IDE and Toolchain Configurations
----
- CubeIDE Version
   - 1.12.0
- McuFamily
   - STM32F407VGTx

## PINOUT
----
| NRF24L01 | STM32F4 |
| --- | --- |
| `VCC` | 3.3V |
| `GND` | GND |
| `CE` | PC5 |
| `CSN` | PC4 |
| `SCK` | PB3 |
| `MOSI` | PA7 |
| `MISO` | PA6 |
| `IRQ` | NC |



## Release Notes
----
- v1.0
    - full duplex support is added.
    - SPI speed is set as 5.25Mbit/s
