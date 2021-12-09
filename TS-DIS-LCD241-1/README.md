# Product Details
TS-DIS-LCD241-1 is a display module comes with a 2.4-inch 240 x 320 pixel resolution TFT LCD. It’s SPI interface allows easy integration with low pin use. 

Regarding the SPI interface, Tony Space’s modules use a buffer (74125) for driving Chip Select (CS) pin from MCU’s Slave Select (SS) pin with intention to allow maximum speed communication for every SPI device installed. Therefore, the Output Enable (OE) of the buffer (named “CSOE” on the module’s schematic) must be driven by logic low before starting communication to selected device and logic high when communication ends. When there are 2 or more SPI devices in the system, only one CSOE signal can be driven low at a time.


# Specifications
- No. of slot: 4
- PCB horizontal: 53 mm
- PCB vertical: 63 mm
- Height: 19 mm
- Power supply: 3V3
- I2C: No
- UART: No
- SPI: Yes
- DIO: Yes
- AIO: Yes
- Others: Sitronix ST7789

# List of documents for TS-DIS-LCD241-1
- [TS-DIS-LCD241-1](TS-DIS-LCD241-1_SCH.pdf)
