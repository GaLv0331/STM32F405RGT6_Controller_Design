# ⚡️ STM32F405RGT6 Controller Design

![3D Render of the Custom PCB](assets/pcb_design.png)
![Schematics](assets/stm32f405rgt6.pdf)
[![Design Tool](https://img.shields.io/badge/Designed%20in-KiCad-207396.svg)](https://www.kicad.org/)

***

## 🌟 Overview

I initially made this design for a 36V/350W motor controller but then the project was dropped, as the design is robust and flexible, it can be used in diy project or some design reference for people.

I have also included an rf module for connectivity (can be used for drones). 

Also there can be design issues in this like missing mouting holes in the pcb design(will be fixed in future revisions).

All schematics and PCB layout files were created using the **KiCad**.

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
