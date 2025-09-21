# 📡 24-GHz Radar-Based Motion Detection System with Real-Time Indication

This repository contains the design, development, and testing files for a **24-GHz radar-based motion detection system**, capable of detecting movement with high accuracy using real-time signal processing. The project integrates hardware (custom PCB with a 24-GHz radar module) and software (firmware, MATLAB analysis, and signal processing algorithms) into a complete working system.

---

## 📌 Project Overview

The objective of this project is to build a **precise motion detection system** leveraging a **24-GHz radar sensor**. The radar signals are captured, digitized, and processed in real time to provide immediate feedback when motion is detected.

### Hardware

* Custom PCB designed in **KiCad**.
* Integration of **24-GHz radar module**, **ADC**, **DAC**, and **DMA** for efficient data handling.
* Gerber files provided for fabrication.

### Software

* **Firmware** written in **PSoC Creator** for the Cypress PSoC 5LP microcontroller.
* State machine–based design for efficient real-time processing.
* **MATLAB scripts** for radar data analysis and Discrete Fourier Transform (DFT)–based signal evaluation.

---

## ✨ Features

* **High-frequency motion detection** at 24 GHz.
* **Custom PCB** with modular radar integration.
* **Real-time indication** of detected motion.
* **Efficient data processing pipeline** using DMA and microcontroller firmware.
* **MATLAB support** for offline data visualization and spectral analysis.

---

## 📂 Repository Contents

* **`24GHz-Radar for movement Detection.pptx`** – Presentation of design, implementation, and performance.
* **`Gerber files for PCB.zip`** – Fabrication files for the custom PCB.
* **`KiCad files for PCB.zip`** – Full KiCad project for PCB layout and schematic.
* **`PSoC_project.zip`** – Source code, configuration, and firmware project for PSoC Creator.

---

## 🛠️ Getting Started

### 🔧 Prerequisites

* [KiCad](https://www.kicad.org/) – For PCB design files.
* [PSoC Creator](https://www.cypress.com/products/psoc-creator-integrated-design-environment-ide) – To build and flash firmware onto the PSoC 5LP.
* [MATLAB](https://www.mathworks.com/products/matlab.html) – For radar data analysis and signal processing.
* PCB fabrication service – To manufacture the board from the Gerber files.

### ⚙️ Installation & Usage

#### 1. PCB Design

* Open KiCad project files.
* Review or modify the layout.
* Send **Gerber files** to a PCB manufacturer.

#### 2. Firmware Development

* Open the **PSoC project** in PSoC Creator.
* Compile and program the PSoC 5LP microcontroller.

#### 3. Signal Processing

* Use MATLAB scripts to process captured radar data.
* Perform **DFT analysis** for precise motion detection.

---

## 🧪 Testing & Validation

* Hardware validated through PCB prototypes.
* Firmware tested with real-time motion detection scenarios.
* MATLAB used to visualize motion profiles and confirm radar accuracy.

---

## 🤝 Contributing

Contributions are welcome! To propose improvements:

1. Fork this repository.
2. Create a feature branch.
3. Commit your changes.
4. Submit a pull request with details.

---

## 📜 License

MIT License – see [LICENSE](LICENSE) for details.

**Author:** Sunil Dabbiru
