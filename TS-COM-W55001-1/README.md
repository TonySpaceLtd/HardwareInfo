# Product Details
TS-COM-W55001-1 is the W5500 module for Tony Space platform. Mainly used for Ethernet communication, the board is composed of WIZnet W5500. It’s SPI interface allows easy integration with low pin use. W5500 allow user connect to standard 10/100 Fast Ethernet network. Interupt from W5500 can be read via GPIO, also user can reset W5500 via GPIO.

Regarding the SPI interface, Tony Space’s modules use a buffer (74125) for driving Chip Select (CS) pin from MCU’s Slave Select (SS) pin with intention to allow maximum speed communication for every SPI device installed. Therefore, the Output Enable (OE) of the buffer (named “CSOE” on the module’s schematic) must be driven by logic low before starting communication to selected device and logic high when communication ends. When there are 2 or more SPI devices in the system, only one CSOE signal can be driven low at a time.

# Specifications
- No. of slot: 2
- PCB horizontal: 53 mm
- PCB vertical: 31 mm
- Height: 19 mm
- Power supply: 3V3
- I2C: No
- UART: No
- SPI: Yes
- DIO: Yes
- AIO: No
- Others: WIZnet W5500

# List of documents for TS-COM-W55001-1
- [TS-COM-W55001-1 schematic](TS-COM-W55001-1_SCH.pdf)
- [WIZnet W5500 datasheet](http://wizwiki.net/wiki/lib/exe/fetch.php/products:w5500:w5500_ds_v109e.pdf)
