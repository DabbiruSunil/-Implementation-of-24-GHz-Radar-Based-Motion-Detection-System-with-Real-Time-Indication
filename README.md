Implementation of 24-GHz Radar-Based Motion Detection System with Real-Time Indication
This repository contains the project files for the implementation of a 24-GHz Radar-based motion detection system, designed to detect movement with high accuracy using real-time signal processing techniques. The project involves the design, development, and testing of a motion detection system on a custom PCB, utilizing a 24-GHz radar module and advanced signal processing algorithms.

Project Overview
The objective of this project is to design a motion detection system that leverages a 24-GHz radar sensor for precise movement detection. The system is capable of processing radar signals in real-time, providing immediate feedback on detected motion. The project includes both hardware and software components:

Hardware Design:
Custom PCB layout using KiCad for integrating the 24-GHz radar module.
Integration of essential components including ADC, DAC, and DMA for efficient signal processing.
Software Development:
Implementation of a state machine in PSoC Creator for signal processing.
Use of MATLAB for analyzing radar data and implementing Discrete Fourier Transform (DFT) for signal analysis.
Development of firmware for the PSoC 5LP microcontroller.
Repository Contents
The repository is structured as follows:

24GHz-Radar for movement Detection.pptx: A presentation detailing the system's design, implementation, and performance analysis.
Gerber files for PCB.zip: The Gerber files necessary for manufacturing the custom PCB designed for this project.
KiCad files for PCB.zip: KiCad project files used to design the PCB layout for the radar-based motion detection system.
PSoC_project.zip: The PSoC Creator project files, including source code and configurations for the radar system's firmware.
Getting Started
Prerequisites
To work with the files in this repository, you will need the following tools:

KiCad: For viewing and modifying the PCB design files.
PSoC Creator: For compiling and uploading the firmware to the PSoC 5LP microcontroller.
MATLAB: For performing signal processing and data analysis.
A suitable PCB manufacturer: For producing the PCB from the Gerber files.
Installation and Usage
PCB Design:

Open the KiCad project files using KiCad.
Review and modify the PCB design if necessary.
Use the Gerber files to manufacture the PCB.
Firmware Development:

Open the PSoC project in PSoC Creator.
Compile the project and program the PSoC 5LP microcontroller.
Signal Processing:

Use MATLAB scripts provided within the PSoC project to process the radar data.
Analyze the real-time signal to detect motion accurately.
Contributing
Contributions to this project are welcome. Please create a pull request with a detailed description of your changes.

Contact
For any queries or further information, please contact Sunil Dabbiru at dabbiru.sunil@stud.h-da.de.
