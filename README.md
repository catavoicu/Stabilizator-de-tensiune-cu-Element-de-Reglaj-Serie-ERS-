# Voltage Regulator with Series Control Element (ERS)

## Project Overview

This project involves the design of a DC voltage regulator that provides a constant output voltage, even under variations in the input voltage or load conditions. It is intended for DC power supply applications that require a stable voltage level.

## Key Features

- Adjustable output voltage: 14 – 28 V  
- Series control element  
- Output load: 1120 Ω  
- Overload protection by limiting the series regulator transistor temperature to 120°C and the maximum current to 0.5 A  
- Input voltage range: 50.4 – 56 V  
- Operating temperature range: 0 – 60°C (verified through thermal testing)

## Project Structure

The project is organized into the following folders:

- `Bill_of_Materials` – Detailed list of all components required for manufacturing, including quantities, specifications, and supplier information (BOM).
- `Data Sheets` – Technical documents providing specifications, features, performance, and recommended usage of the components.
- `Layout` – PCB design files created using OrCAD X PCB.
- `Proiect Docs` – Project documentation:
  - Project report (PDF)
  - Design formulas and calculations
- `Schematics` – Circuit schematic showing components and connections.
- `Simulations` – Circuit simulations used to evaluate performance and stability, as well as to optimize component selection and operating conditions.

## Usage Instructions

### 1. Circuit Simulation

1. Open the `"P1_VOICU_CATALIN.opj"` file located in the `Schematics` folder using OrCAD X or a compatible simulator.
2. Run the simulations to verify correct circuit behavior.

### 2. PCB Fabrication

1. Use the Gerber files located in the `Layout` folder to view and manufacture the printed circuit board (PCB).

## Technical Requirements

- OrCAD 17.2 or OrCAD X for circuit simulation
- OrCAD 17.2 or OrCAD X for PCB design

## Screenshots and Schematics

- **Electronic Schematic**:  
 https://github.com/catavoicu/Stabilizator-de-tensiune-cu-Element-de-Reglaj-Serie-ERS-/blob/main/Schematics/Schema.jpg

- **PCB Layout**:  
https://github.com/catavoicu/Stabilizator-de-tensiune-cu-Element-de-Reglaj-Serie-ERS-/blob/main/Layout/p1_voicu_catalin.jpg

## Author

**Name**: Cătălin Voicu  
**Email**: catavoicu01@gmail.com  
**Course**: P1 – Faculty of Electronics, Telecommunications and Information Technology  
**University**: Polytechnic University of Bucharest
