# Hardware-Reversing-Lab
Reversing hardware devices: firmware extraction, signal tracing, teardown &amp; analysis

# Hardware Reversing Lab 🧪

This project documents my personal experiments in hardware analysis, firmware dumping, and reverse engineering of real-world embedded systems and devices.

## 🎯 Objectives

- Extract firmware using tools like CH341A, JTAG, UART, SPI
- Analyze digital signal patterns (e.g., scooter controllers)
- Utilize logic analyzers, OpenOCD, Ghidra, and binwalk
- Document attack paths and technical teardown steps

## 🔧 Hardware Used

- CH341A with SOIC8 Clip (SPI Flash dumping)
- Logic Analyzer (AZDelivery 8CH 24 MHz)
- ESP32 Marauder, LILYGO T-Dongle S3
- Flipper Zero (WiFi Dev Board)
- E-scooter controllers, routers, USB devices, legacy boards

## 🛠️ Tools & Software

- Ghidra, binwalk, strings, hexdump
- OpenOCD, pySerial, PulseView / sigrok
- Arduino IDE / PlatformIO
- SerialPlot, Logic 2 (Saleae)

## 📁 Folder Structure

```plaintext
src/            # Scripts, serial logs, UART dumps
docs/           # Documentation, pinout drawings, teardown notes
firmware/       # .bin / .hex firmware images & analysis
analyzers/      # Logic analyzer sessions and exports
