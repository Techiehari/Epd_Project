# Epd_Project: 3.3V to 15V Boost Converter

## Overview
This repository contains the KiCad design files for a custom DC-to-DC power converter. The circuit is designed to take a 3.3V input and provide a highly regulated 15V output at 1A, utilizing the MP3429 IC.

## Key Specifications
* **Input Voltage:** 3.3V
* **Output Voltage:** 15V
* **Output Current:** 1A
* **Core IC:** MPS MP3429

## Tools Used
* **EDA Software:** KiCad
* **Routing:** Freerouting plugin
* **Custom Footprints/Symbols:** Designed specifically for the MP3429 and associated components.

## Repository Structure
* `/Custom_libraries` - Contains project-specific library files.
* `/models` - 3D models for PCB visualization.
* `/MP3429_Custom.pretty` - Custom footprint library for the MP3429 IC.
* `/symbols` - Custom schematic symbols.
* `Bom.csv` - Bill of Materials containing component selection and costs.
* `Epd_Project.kicad_sch` - The main KiCad schematic file.
* `Epd_Project.kicad_pcb` - The main KiCad PCB layout file.

## Design Details
Detailed design equations, component selection justifications, and technical specifications derived from the MP3429 datasheet are maintained in the project report documents.
