# Product Details 
TSX-POW-DC2-x is a power supply unit in SX form of Tony Space platform. Using TI’s switching voltage regulator TPS54331, the board can deliver 5V 3A from wide range voltage input. This is sufficient for most applications including applications that use 3G/4G GSM modules.

In addition, 2 power relays are provided with the board for general purpose. These replays are controlled by digital output pins from the MCU board with the following method.
- Relay1 controlled by IO14
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
- Power supply: 9-24 VDC
- I2C: No
- UART: No
- SPI: No
- DIO: No
- AIO: No
- Others: TI TPS54331, HKE HRS4H-SDC5V

# List of documents for TSX-POW-DC2-1
- [TSX-POW-DC2-1 schematic](TSX-POW-DC2-1_SCH.pdf)
- [TI TPS54331DDAR datasheet](https://www.ti.com/lit/ds/symlink/tps54331.pdf)
- [Multicomp HRS4-S DC 5V datasheet](http://www.farnell.com/datasheets/3176360.pdf)
