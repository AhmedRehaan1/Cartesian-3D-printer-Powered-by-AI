# Custom 3D Printer Project

This repository contains the firmware and related files for a custom-built 3D printer. The project aims to provide a robust and customizable platform for 3D printing enthusiasts and makers.

## Features

*   **Custom Marlin Firmware:** Optimized and configured for this specific 3D printer hardware, ensuring precise control and enhanced performance.
*   **Modular Design:** (Placeholder - Add details about the printer's modular design if applicable)
*   **High-Quality Prints:** (Placeholder - Add details about print quality and capabilities)

## Repository Structure

*   `Marlin-2.0.9.7cartesian/`: Contains the custom Marlin firmware source code.
*   `CAD_Model/`: (Placeholder - This directory will contain the CAD model files of the 3D printer.)
*   `Documentation/`: (Placeholder - This directory will contain the project report and other relevant documentation.)

## Getting Started

### Firmware

The `Marlin-2.0.9.7cartesian/` directory contains the Marlin firmware. To compile and upload the firmware to your 3D printer's control board, follow these steps:

1.  **Install Arduino IDE:** Download and install the Arduino IDE from the official website.
2.  **Install PlatformIO (Recommended):** For a more streamlined development experience, it is highly recommended to use PlatformIO within Visual Studio Code. Follow the official PlatformIO installation guide.
3.  **Open Project:** Open the `Marlin-2.0.9.7cartesian/Marlin/Marlin.ino` file in Arduino IDE or the `Marlin-2.0.9.7cartesian/` folder as a PlatformIO project.
4.  **Configure:** Review `Configuration.h` and `Configuration_adv.h` for any specific settings you might need to adjust for your hardware (e.g., thermistor types, stepper drivers, bed size). **Note:** This firmware is already pre-configured for the custom 3D printer this project is based on.
5.  **Compile and Upload:** Compile the firmware and upload it to your 3D printer's control board.

### CAD Model

The CAD model of the 3D printer will be available in the `CAD_Model/` directory. This will include design files (e.g., SolidWorks, STEP, STL) for all mechanical components, allowing for replication, modification, or understanding of the printer's physical structure.

### Project Report

A detailed project report will be located in the `Documentation/` directory. This report will cover the design considerations, component selection, assembly process, calibration procedures, and performance testing of the 3D printer. It will also delve into the specific customizations made to the Marlin firmware and their impact on the printer's operation.



---

**Author:** Ahmed Rehaan
