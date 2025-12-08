# Arduino-RC522-Rfid tester
A simple Arduino project using the MFRC522 RFID module to read and display RFID tag UIDs on the Serial Monitor.

[![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Arduino Version](https://img.shields.io/badge/Arduino-IDE-blue.svg)]()

---

## Description
This project uses an **RFID-RC522 module** with Arduino to read RFID tags and display the UID on the Serial Monitor. Ideal for beginners in electronics and embedded systems.

---

## Features
- Read RFID tag UID
- Display UID on Serial Monitor
- Beginner-friendly code
- Works with Arduino Uno

---

## Requirements
- Arduino Uno
- RFID-RC522 module
- RFID tag/card
- Jumper wires
- Arduino IDE
- `MFRC522` library by Miguel Balboa

---

## Wiring / Setup
| RC522 Pin | Arduino Pin |
|-----------|-------------|
| SDA       | 10          |
| SCK       | 13          |
| MOSI      | 11          |
| MISO      | 12          |
| RST       | 9           |
| 3.3V      | 3.3V        |
| GND       | GND         |

> **Important:** Use 3.3V only, not 5V.

---

## Installation
1. Install Arduino IDE from [https://www.arduino.cc/en/software](https://www.arduino.cc/en/software)
2. Install `MFRC522` library via Arduino Library Manager
3. Connect your RFID module according to the wiring table
4. Upload the [test code]() sketch to your Arduino

---

## Usage
1. Open Arduino Serial Monitor (baud rate: 9600)
2. Place RFID tag near the module
3. Serial Monitor will display the UID like:


---

## Troubleshooting
- Ensure the module is powered with 3.3V
- Check wiring carefully
- Install MFRC522 library
- Hold the RFID tag close (1–3 cm) to the antenna
- Make sure baud rate in Serial Monitor is 9600

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Author
Amiel Josh Basug


