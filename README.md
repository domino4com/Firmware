# Domino4 Firmware

Download latest .bin file from here: [Latest release](https://github.com/24mm2/Domino4-Firmware/releases/latest)

## Libraries
- **Core:**
  - ESP32: [JSON board file](https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json
)
- **Sensors:**
  - ODA: [OLED Display](https://github.com/ThingPulse/esp8266-oled-ssd1306) (via GitHub)
  - ILB: [Light Sensor (LTR390)](https://github.com/levkovigor/LTR390) (via Arduino)
  - IWA: [Weather Sensor (AHTxx)](https://github.com/enjoyneering/AHTxx) (via GitHub)
  - IWA: [Weather Sensor (SHT3x)](https://github.com/wemos/WEMOS_SHT3x_Arduino_Library) (via GitHub)
  - IWB: [Barometer (SPL06-00x)](https://github.com/rv701/SPL06-007) (via GitHub)
  - INA: GNSS (ATGM336H-5N31) TBD
  - IGA: [Airquaility (SGP30)](https://github.com/sparkfun/SparkFun_SGP30_Arduino_Library) (via GitHub)
  - IIA: Accelerometer (LIS2DH12) TBD
- **Support:**
  - ArduinoJSON [...more](https://arduinojson.org) (via Arduino)
  - PubSubClient [...more](https://pubsubclient.knolleary.net) (via Arduino)
  - LoRa: [RadioHead](https://www.airspayce.com/mikem/arduino/RadioHead/) (via GitHub)
  - WiFimanager [...more](https://github.com/tzapu/WiFiManager) (via Arduino)
  - NTPClient *must be v3.1.0* [...more](https://github.com/arduino-libraries/NTPClient) (via Arduino)

## Compiling
- Board: ESP32 Dev Module
- Upload Speed: 460800
- Partition Scheme: TBD
