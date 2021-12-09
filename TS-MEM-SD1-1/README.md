# Product Details
TS-MEM-SD1-1 is an expansion memory module for Tony Space platform with 4-wire SPI interface. Accepting micro SD card, it can be used for data logging applications. 

Regarding the SPI interface, Tony Space’s modules use a buffer (74125) for driving Chip Select (CS) pin from MCU’s Slave Select (SS) pin with intention to allow maximum speed communication for every SPI device installed. Therefore, the Output Enable (OE) of the buffer (named “CSOE” on the module’s schematic) must be driven by logic low before starting communication to selected device and logic high when communication ends. When there are 2 or more SPI devices in the system, only one CSOE signal can be driven low at a time.

# Specifications
- No. of slot: 1
- PCB horizontal: 26 mm
- PCB vertical: 31 mm
- Height: 19 mm
- Power supply: 3V3
- I2C: No
- UART: No
- SPI: Yes
- DIO: No
- AIO: Yes
- Others: No

# List of documents for TS-MEM-SD1-1
- [TS-MEM-SD1-1 schematic](TS-MEM-SD1-1_SCH.pdf)
