# Domino4 Firmware

Download latest .bin file from here: [Latest release](https://github.com/24mm2/Domino4-Firmware/releases/latest)

## Libraries
- **Core:**
  - ESP32: [JSON board file](https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_dev_index.json
)
- **Sensors:**
  - ODA: [OLED Display](https://github.com/ThingPulse/esp8266-oled-ssd1306) (via GitHub)
  - ILB: [Light Sensor (LTR390)](https://github.com/levkovigor/LTR390) (via Arduino)
  - IWA: [Weather Sensor (AHTxx)](https://github.com/enjoyneering/AHTxx) (via Github)
  - IWA: [Weather Sensor (SHT3x)](https://github.com/wemos/WEMOS_SHT3x_Arduino_Library) (via Github)
  - IWB: Barometer (SPL06-001) TBD
  - INA: GNSS TBD
  - IGA: Airquaility (SGP30) TBD
  - IIA: Accelerometer (LIS2DH12) TBD
- **Support:**
  - ArduinoJSON (via Arduino) [...more](https://arduinojson.org)
  - PubSubClient (via Arduino) [...more](https://pubsubclient.knolleary.net)
  - LoRa: [RadioHead](https://www.airspayce.com/mikem/arduino/RadioHead/)
  - WiFimanager (via Arduino) [...more](https://github.com/tzapu/WiFiManager)
  - NTPClient (via Arduino) *must be v3.1.0* [...more](https://github.com/arduino-libraries/NTPClient)

## Compiling
- Board: ESP32 Dev Module
- Upload Speed: 460800
- Partition Scheme: TBD
