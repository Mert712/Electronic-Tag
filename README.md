# 🏷️ Electronic Shelf Label (ESL) Automation System

An IoT-based Electronic Shelf Label management system designed to dynamically synchronize retail product prices, stock status, and details across e-paper displays via ESP32 microcontrollers.

---

## 📌 Project Overview
This project provides a cost-effective, energy-efficient, and centralized electronic labeling solution for retail environments. It bridges central inventory management with physical shelf displays in real-time.

### Key Features
* **Ultra-Low Power Consumption:** Deep-sleep modes and e-paper display technology for long battery life.
* **Real-Time Synchronization:** Instant updates for prices, discounts, and stock levels over Wi-Fi.
* **Central Control Panel:** Desktop/Web-based UI for managing inventory and pushing screen layouts.
* **Dynamic Layouts:** Custom rendering for barcodes, QR codes, promotional badges, and price tags.

---

## 🛠️ Tech Stack & Architecture

* **Microcontroller:** ESP32
* **Display:** E-Paper / E-Ink Display (SPI Interface)
* **Embedded Software:** C++ / Arduino Framework (PlatformIO)
* **Desktop & Backend:** Python / C# (.NET)
* **Database & Communication:** REST API / MQTT / Web Scraping Integration

---

## 📂 Project Structure

├── firmware/          # ESP32 source code, e-paper drivers, Wi-Fi handlers
├── backend/           # API services, scrapers, database controllers
├── desktop-ui/        # Management dashboard application
├── hardware/          # Schematics, pinouts, and 3D casing models
├── docs/              # System architecture and setup documentation
└── README.md

---

## 🚀 Getting Started

### Prerequisites
* PlatformIO / Arduino IDE
* Python 3.x or .NET Runtime
* Git

### Installation
1. Clone the repository:
   git clone https://github.com/Mert712/Electronic-Tag.git
   cd Electronic-Tag

2. Set up firmware:
   * Open the /firmware directory in VS Code (PlatformIO).
   * Update Wi-Fi and server configurations in config.h.
   * Flash the ESP32 board.

---

## 👥 Contributors
* **Esat Mert Sayıcı** - [@Mert712](https://github.com/Mert712)
* **Umut Beytullah Yoncalık** - [@Umutynclk](https://github.com/Umutynclk)
