# 📖 Personal ESP32 E-Reader

## 💡 The Origin Story
I kept stealing my girlfriend’s e‑reader, so I figured, why not build one myself?
Instead of just buying my own, I realized this was the perfect excuse to dive into the world of electronics and build one from scratch. This project is my hands-on introduction to embedded systems, bridging the gap between raw hardware components and functional software.

## 🛠️ The Tech Stack
* **Microcontroller:** DOIT ESP32 DevKit V1
* **Display:** Waveshare 4.2" E-Ink Module (Version 2 - GDEY042T81)
* **Environment:** Visual Studio Code + PlatformIO
* **Framework:** Arduino
* **Core Libraries:** `GxEPD2`, `Adafruit GFX`

## 🧠 What I'm Learning
Building an e-reader from scratch goes far beyond just writing code. This project is teaching me:

* **Microcontroller Architecture:** Understanding GPIO pinouts, strapping pins, and memory allocation on the ESP32.
* **Hardware Communication:** Mastering the SPI (Serial Peripheral Interface) protocol to successfully push image data to the display.
* **Power Management:** Managing 3.3V logic, handling the current spikes required to flip e-ink microcapsules, and bypassing hardware brownout triggers.
* **C++ & Embedded Programming:** Moving beyond basic scripts to manage libraries, object-oriented displays, and the Arduino framework in a professional IDE (PlatformIO).
* **Advanced Debugging:** Isolating issues between physical wiring faults and software bugs using Serial Monitor diagnostics.
* **Data Parsing (Upcoming):** Reading `.txt` files from a physical SD card, parsing strings, and calculating pagination based on font metrics.
* **Industrial Design (Upcoming):** 3D modeling and printing a custom, ergonomic enclosure for the final hardware.

## 🚀 Project Roadmap
- [x] Establish development environment (VS Code + PlatformIO).
- [x] Wire hardware and successfully bypass breadboard/power constraints.
- [x] Initialize display and verify SPI communication with test graphics.
- [ ] Integrate Micro-SD card module for local file storage.
- [ ] Develop text parsing and pagination logic.
- [ ] Wire physical hardware buttons for page turning.
- [ ] Implement deep-sleep power saving mode.
- [ ] Design and 3D print the final case.

---
*Documenting the journey from a pile of wires to a finished product.*
