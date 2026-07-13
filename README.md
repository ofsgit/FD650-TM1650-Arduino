
# FD650-TM1650-Arduino

An easy-to-use Arduino library for driving **FD650** and **TM1650** 7-segment LED display modules, including front-panel displays salvaged from digital set-top boxes (STBs).

> Give old hardware a second life. ♻️

## Features

- ✅ Supports FD650 display controllers
- ✅ Supports TM1650 display controllers
- ✅ Compatible with Arduino and other Arduino-compatible boards
- ✅ Display numbers, letters, and custom segment data
- ✅ Brightness control
- ✅ Simple and lightweight API
- ✅ Perfect for salvaged STB front-panel displays

## Supported Hardware

This library is designed for displays using one of the following ICs:

- FD650
- TM1650

Common examples include:

- 4-digit 7-segment display modules
- Digital set-top box (STB) front-panel displays
- Recycled consumer electronics displays

> **Note:** Some STB display boards may require reverse-engineering of their pinout before use.

## Installation

### Arduino Library Manager

*Coming soon.*

### Manual Installation

1. Download or clone this repository.
2. Copy the folder into your Arduino `libraries` directory.
3. Restart the Arduino IDE.

Or clone it with Git:

```bash
git clone https://github.com/<your-username>/FD650-TM1650-Arduino.git
```

## Example

```cpp
#include <FD650_TM1650.h>

FD650_TM1650 display;

void setup() {
    display.begin();
    display.print("1234");
}

void loop() {

}
```

> The exact API may vary depending on the library version.

## Why this library?

Many inexpensive digital set-top boxes contain high-quality LED display modules driven by FD650 or TM1650 chips. Instead of throwing them away, this library makes it easy to reuse those displays in your Arduino projects.

Perfect for:

- DIY clocks
- Counters
- Sensor displays
- Home automation
- Retro electronics projects
- Hardware recycling

## Compatibility

- Arduino Uno
- Arduino Nano
- Arduino Mega
- ESP8266
- ESP32
- Other Arduino-compatible boards

## Contributing

Contributions, bug reports, feature requests, and pull requests are always welcome.

If you've successfully connected a salvaged display, feel free to share its pinout to help others.

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0).

See the `LICENSE` file for details.

---
