# ⚡️ STM32F405RGT6 Controller Design

![Controller Board Image Placeholder]([(https://drive.google.com/file/d/1WejSWMD9wfBn6vvBd5DN38Q0o6gYwlGU/view?usp=sharing)])

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Design Tool](https://img.shields.io/badge/Designed%20in-KiCad-207396.svg)](https://www.kicad.org/)

***

## 🌟 Overview

This repository contains the complete **hardware design files** for a custom controller board built around the powerful **STM32F405RGT6** microcontroller.

The design is engineered for high-performance control applications and features integrated **RF wireless communication** capabilities, making it suitable for projects such as remote control systems, robotics, or advanced data acquisition platforms.

All schematics and PCB layout files were created using the **KiCad** open-source EDA suite.

***

## 🎯 Key Features and Components

| Feature | Description | Related Files |
| :--- | :--- | :--- |
| **Microcontroller** | **STM32F405RGT6** (Cortex-M4, 168 MHz) is the core processing unit. | `STM32.kicad_sch`, `STM32.kicad_pcb` |
| **Wireless Interface** | Dedicated circuitry for an **nRF** series radio module (e.g., nRF24L01). | `nrf.kicad_sch` |
| **Design Platform**| Complete PCB layout and schematic captured in KiCad. | `STM32.kicad_pro`, `STM32.kicad_pcb` |
| **Connectivity** | Includes necessary debugging headers (SWD/JTAG), power supply, and breakout points for peripherals. | |

***

## 📂 Design Files Structure

The project is managed entirely within **KiCad**. The following files are included in the main directory:

| File Name | Description |
| :--- | :--- |
| `STM32.kicad_pro` | The main KiCad project file. |
| `STM32.kicad_sch` | The primary schematic document for the STM32 controller. |
| `STM32.kicad_pcb` | The complete PCB layout file, including routing, layers, and footprints. |
| `nrf.kicad_sch` | A separate schematic sheet detailing the integration of the nRF wireless module. |
| `RF(pin change).kicad_sym` | Custom schematic symbol for the RF component or a related section. |

***

## 🛠️ Getting Started (Viewing the Design)

To open, inspect, or modify the design files, you must have KiCad installed.

### Prerequisites

1.  **KiCad EDA:** Download and install the latest stable version from the [official KiCad website](https://www.kicad.org/download/).

### How to Open

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/GaLv0331/STM32F405RGT6_Controller_Design.git](https://github.com/GaLv0331/STM32F405RGT6_Controller_Design.git)
    ```
2.  **Open Project:** Launch KiCad and open the main project file: `STM32.kicad_pro`.
3.  From the KiCad project manager, you can then launch the Schematic Editor or the PCB Layout Editor to view the respective files.

***

## 📄 License

This project is open-source and released under the **MIT License**. See the `LICENSE` file for more details.

***

## 📞 Contact

For questions, bug reports, or contributions, please feel free to open a GitHub Issue in this repository.
