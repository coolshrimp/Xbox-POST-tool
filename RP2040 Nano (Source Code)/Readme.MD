# Xbox POST Tool (RP2040 Nano Edition)

This is a fork of the original [Durango POST Code Reader](https://github.com/XboxOneResearch/PicoDurangoPOST) adapted to run on the **RP2040 Nano** board with an **I2C OLED Display**.

## ✅ What’s Different in This Fork?

- Ported to **RP2040 Nano**
- Added support for **SSD1306 OLED Display (128x32 or 128x64)**
- Uses **Adafruit_SSD1306** and **Wire** libraries
- I2C pin definitions added for both the display and Xbox POST reader
- POST code data is shown **on the OLED screen** and over **Serial Monitor**

---

## 📟 Display Requirements

- **Display Type**: SSD1306 OLED
- **Resolution**: 128x32 or 128x64
- **Connection**: I2C
- **Library**: [Adafruit_SSD1306](https://github.com/adafruit/Adafruit_SSD1306)
Install via Arduino Library Manager:

## 🪛 Pinout Configuration (RP2040 Nano)

| Function        | Pin Label on RP2040 Nano | GPIO  |
|----------------|--------------------------|--------|
| Xbox SDA (I2C) | GP0                       | `GPIO 0` |
| Xbox SCL (I2C) | GP1                       | `GPIO 1` |
| Display SDA    | GP10                      | `GPIO 10` |
| Display SCL    | GP11                      | `GPIO 11` |

### 📦 RP2040 Source & Binaries

- [View RP2040 Source Code](https://github.com/coolshrimp/Xbox-POST-tool/tree/main/RP2040%20Nano%20(Source%20Code))
- [Latest Precompiled UF2](https://github.com/coolshrimp/Xbox-POST-tool/releases/latest)

📷 **Wiring Diagram:**

Coming soon..
