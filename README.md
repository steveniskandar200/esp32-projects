# ESP32 Projects 🔌

A collection of ESP32 projects built with the Elegoo Super Starter Kit while learning embedded systems and IoT development.

## Hardware
- **Board:** ESP32 (30-pin)
- **Kit:** Elegoo Super Starter Kit
- **IDE:** Arduino IDE

## Projects

| # | Project | Concepts | Status |
|---|---------|----------|--------|
| 01 | [LED Blink](./01-led-blink/) | Digital output, GPIO | ✅ Done |

## Getting Started

1. Install [Arduino IDE](https://www.arduino.cc/en/software)
2. Add ESP32 board support:
   - Go to **File → Preferences**
   - Add this URL to "Additional Boards Manager URLs":
     ```
     https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
     ```
   - Go to **Tools → Board → Boards Manager**, search `esp32`, install
3. Clone this repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/esp32-projects.git
   ```
4. Open any `.ino` file in Arduino IDE and upload to your board

## Resources
- [ESP32 Pinout Reference](https://randomnerdtutorials.com/esp32-pinout-reference-gpios/)
- [Elegoo Support](https://www.elegoo.com/pages/download)
- [Arduino Language Reference](https://www.arduino.cc/reference/en/)
