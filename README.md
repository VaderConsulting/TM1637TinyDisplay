# TM1637TinyDisplay

A simple library to display numbers, text and animation on 4 and 6 digit 7-segment TM1637 based display modules. Connect the TM1637 display CLK and DIO pins to your Arduino GPIO pins, include this library, initialize TM1637TinyDisplay and call easy to use functions like showNumber(), showString(), showLevel() and showAnimation(). Display will scroll text for larger strings. Functions support screen splitting for easy number + text formatting. Runs well on tiny controllers including the ATtiny85. Original author: Jason Cox <jason@jasonacox.com>. This is my working copy from the Arduino `libraries` tree. Version recorded in `library.properties`: 1.4.4. Upstream: <https://github.com/jasonacox/TM1637TinyDisplay>.

**Source last updated:** 2022-02-22  
**Language:** C++ / Arduino  
**Target:** Arduino (*)  
**Output:** Arduino library

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `TM1637TinyDisplay` | C++ / Arduino | library | A simple library to display numbers, text and animation on 4 and 6 digit 7-segment TM1637 based display modules |
| `ATtiny85` | C++ / Arduino | example sketch | `examples/ATtiny85/ATtiny85.ino` |
| `TM1637-6Digit-Test` | C++ / Arduino | example sketch | `examples/TM1637-6Digit-Test/TM1637-6Digit-Test.ino` |
| `TM1637-Countdown` | C++ / Arduino | example sketch | `examples/TM1637-Countdown/TM1637-Countdown.ino` |
| `TM1637-Countdown-Buttons` | C++ / Arduino | example sketch | `examples/TM1637-Countdown-Buttons/TM1637-Countdown-Buttons.ino` |
| `TM1637Demo` | C++ / Arduino | example sketch | `examples/TM1637Demo/TM1637Demo.ino` |
| `TM1637Test` | C++ / Arduino | example sketch | `examples/TM1637Test/TM1637Test.ino` |

## How to open

Install this folder as an Arduino library (Sketch → Include Library → Add .ZIP Library, or copy into `libraries/TM1637TinyDisplay`). Open any `examples/*.ino` from the Arduino IDE.

## Requirements

- Arduino IDE

## Attribution and provenance

- **Original author / maintainer:** Jason Cox <jason@jasonacox.com>
- **library.properties name:** TM1637TinyDisplay
- **Version:** 1.4.4
- **Upstream URL:** <https://github.com/jasonacox/TM1637TinyDisplay>
- **Category:** Display
- This repository is my working copy for catalogue/reference; authorship stays with the original authors.

## License

Original upstream license terms in this tree (where recorded). This repository does not claim authorship of the upstream library. See `THIRD_PARTY_NOTICES.md`. The `LICENSE` file added at import is a Vader Consulting MIT wrapper and does not replace upstream terms.
