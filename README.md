# Simple ESP32-S3 Media Player (ESPHome & PSRAM Optimized)

A high-performance, compact network audio player based on the ESP32-S3-DevkitC-1 and PCM5102A DAC. Optimized for **Music Assistant (Home Assistant)** with a focus on stability, zero-stutter playback, and deep software-hardware integration.

---

## 🚀 Key Features
* **Superior Stability:** Optimized for ESP32-S3 N16R8, utilizing specialized network buffers and PSRAM management to eliminate stuttering.
* **Hi-Fi Output:** Uses PCM5102A DAC with hardware-level pop-noise suppression and optimized I2S signaling.
* **Smart Power:** Integrated deep sleep logic with automatic headphone jack detection for energy efficiency.
* **Perfect Sync:** Full support for the Sendspin protocol, enabling low-latency multi-room audio synchronization.

---

## 📖 Project Structure
Detailed guides and technical insights are organized into the following sections:

* [🛠 **Hardware & Soldering Guide**](./docs/01.hardware_build.md) – Components, wiring diagrams, and assembly steps.
* [💻 **Software & Debugging Guide**](./docs/02.debugging.md) – YAML configuration, SDK optimizations, and performance tuning.
* [💡 **Notes & Tips**](./docs/03.notes_n_tips.md) – Critical debugging discoveries, hardware "gotchas," and optimization tricks.

---

## 📦 3D Enclosure Files
The enclosure is designed to be compact and functional. You can find the STL files in the `/stls` folder.

### Bottom Case Options:
* **Hidden Port:** Only exposes the UART port for a minimalist look.
* **Dual Port:** Both USB ports are accessible.

### Lid Options
* **Small Button (Black):** Features longer internal pillars to match the lower profile of black tactile switches (height of the swtich is about 2mm).
* **Large Button (White):** Features shorter pillars to accommodate the taller profile of white tactile switches (height of the swtich is about 3mm).
* **No-Button:** A clean, flat top for an enclosed aesthetic.

---

## 🤝 Acknowledgments
- **ESPHome Community**: For the powerful tools that make these projects possible.
- A huge thank you to [arhills](https://github.com/arhills) for his invaluable help and technical guidance throughout the development of this project.

---

## 📜 License

This project is licensed under the **GPL-3.0 License** - see the [LICENSE](LICENSE) file for details. 