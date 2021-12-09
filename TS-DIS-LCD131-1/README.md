# Product Details
TS-DIS-LCD131-1 is a display module comes with a 1.3-inch 240 x 240 pixel resolution IPS LCD. It’s SPI interface allows easy integration with low pin use. With IPS technology, the LCD has a full viewing angle which makes this module perfect for small displays. The backlight can also be turned on/off by a GPIO pin.

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
- AIO: Yes
- Others: Sitronix ST7789

# List of documents for TS-DIS-LCD131-1
- [TS-DIS-LCD131-1](TS-DIS-LCD131-1_SCH.pdf)
