# Product Details
Tony SX E32 Pro is the MCU Board that has 32-bit MCU (ESP32-WROVER-IB). Users are able to develop the program with Arduino IDE and upload program on a board with USB (Micro-B), using power input 5 VDC, supported by Wi-Fi and Bluetooth BLE 4.2 / 3 / 2.1, including serial communication on SPI, I2C, UART. There is Digital Input/Output, ADC (Analog to Digital Converter) and DAC (Digital to Analog Converter) on a board which users are able to program for configuring a port to ADC or DAC freely. In addition, there is an RTC (Real Time Clock) which is an important thing for some projects that require time records or Time Stamp. There is an LED Built-in and a U.FL connector for connecting to an external antenna. This board supports other modules in Tony S Platform.

# Product Features
- ADC and DAC 12 bit  12 channels
- IO 12 channels
- RTC (Real Time Clock)
- 3 Regulators
     - Regulator 1 is a power supply 3.3 VDC for main board such as ESP32, RTC , MAXxxx.
    When ESP32 has power, users are able to program in order to supply electricity for Regulator 2 and Regulator 3 on port I/O25
   	 - Regulator 2 is a power supply 3.3 VDC for SLOT 1, SLOT 2 and SLOT 3
   	 - Regulator 3 is a power supply 3.3 VDC for SLOT 4, SLOT 5 and SLOT 6

# Specifications
- PCB size: 71 mm X 103 mm X 6 mm (W x L x H)
- Microcontroller: ESP32-WROVER-IB
- Flash memory: 16 MB
- SRAM: 520 KB
- PSRAM: 8 MB
- Integrated crystal: 40 MHz
- USB: Micro-B
- Bluetooth: BLE 4.2 / 3 / 2.1
- Wi-Fi: IEEE 802.11 b/g/b
- Input Voltage (limit): 3.3 - 5 VDC
- IO: 12 
- SPI: 1
- I2C: 1
- UART: 2
- LED_BUILTIN: 1
- 12-bit ADC/DAC (0-10V): 12 channels
- Conversion Rate: 400 kHz
- DAC Current per port (with over-current protection): 25 mA 
- RTC (Real Time Clock): DS3231
- Antenna connector: IPEX connectors
- 2x8 Connector pitch 2.54mm: 6

# List of documents for TSX-MCU-E32P61-1
- [TSX-MCU-E32P61-1 Schematic](TSX-MCU-E32P61-1_SCH.pdf)
- [Espressif Systems ESP32-WROVER-IE Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-wrover-e_esp32-wrover-ie_datasheet_en.pdf)
- [Maxim Integrated MAX11301GL+ Datasheet](https://datasheets.maximintegrated.com/en/ds/MAX11301.pdf)
- [Maxim Integrated DS3231MZ+ Datasheet](https://datasheets.maximintegrated.com/en/ds/DS3231M.pdf)
- [Silicon Las CP2102N Datasheet](https://www.silabs.com/documents/public/data-sheets/cp2102n-datasheet.pdf)
