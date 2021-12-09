# Product Details
TSX-POW-AC1-x is a power supply unit in SX form of Tony Space platform. Using Hi-Link’s power module HLK-5M05, the board can deliver 5V 1A from 90-240 VAC. This is sufficient for most applications.

In addition, 2 power relays are provided with the board for general purpose. These replays are controlled by digital output pins from the MCU board with the following method.
- Relay1 controlled by IO14,
  - Logic High - COM is connected to NC 
  - Logic Low - COM is connected to NO
- Relay1 controlled by IO15
  - Logic High - COM is connected to NC 
  - Logic Low - COM is connected to NO

# Specifications
- No. of slot: 0
- PCB horizontal: 71 mm
- PCB vertical: 95 mm
- Height: 24 mm
- Power supply: 220 VAC
- I2C: No
- UART: No
- SPI: No
- DIO: No
- AIO: No
- Others: Hi-Link HLK-5M05, HKE HRS4H-SDC5V

# List of documents for TSX-POW-AC1-1
- [TSX-POW-AC1-1 schematic](TSX-POW-AC1-1_SCH.pdf)
- [Hi-Link HLK5M05 datasheet](https://datasheet.lcsc.com/szlcsc/1912111437_HI-LINK-HLK-5M05_C209907.pdf)
- [Multicomp HRS4-S DC 5V datasheet](http://www.farnell.com/datasheets/3176360.pdf)
