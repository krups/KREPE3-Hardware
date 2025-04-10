# LP-DataLogger
PCB design files and documentation for low power data-logger module for KREPE-3

### PCB Render

### Components
- [Raspberry Pi Pico 2 (4MB Flash)](https://datasheets.raspberrypi.com/pico/pico-2-datasheet.pdf)
- [FSM300 9-axis IMU module](https://www.mouser.com/datasheet/2/1480/FSM30x_Datasheet-3196253.pdf)
- [MCP9600 Thermocouple to digital converter](https://ww1.microchip.com/downloads/aemDocuments/documents/MSLD/ProductDocuments/DataSheets/MCP960X-L0X-RL0X-Thermocouple-EMF-to-Temperature-Converter-plus-minus-1-5-degrees-Celcius-Maximum-Accuracy-DS20005426.pdf)
- [Honeywell SSCSRNN015PA3A3 Pressure Sensor](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/2157/ssc_series_DS.pdf)

### Pin Mapping
| Pico 2 GPIO Pin | Net Name |
| --- | --- |
| GPIO4 | I2C_SDA |
| GPIO5 | I2C_SCL |
| GPIO6 | FSM300_RESET |
| GPIO7 | HINTN |
| GPIO8 | UART_LOGGER_TO_MAIN |
| GPIO9 | UART_MAIN_TO_LOGGER |
| GPIO10 | SD_SPI_CLK |
| GPIO11 | SD_SPI_MOSI |
| GPIO12 | SD_SPI_MISO |
| GPIO13 | SD_SPI_CS |
