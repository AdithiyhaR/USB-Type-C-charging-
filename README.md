# USB Type-C Charger Using Flyback Converter

## Project Overview

This project involves the design and implementation of a USB Type-C charger using a Flyback Converter. The charger is designed to deliver 60W power from a universal mains supply (230V, 50Hz) with an output current of 3A. The design features an AC to DC conversion using a Full Bridge Rectifier, followed by an isolated DC-DC conversion using a Flyback Converter. The output voltage is adjustable between 15V and 20V, with an accuracy of +/-10%, meeting the USB-C power delivery specifications.

## Features

- **Power Rating**: 60W
- **Mains Voltage**: 230V, 50Hz
- **Output Current**: 3A
- **Output Voltage**: Adjustable between 15V and 20V with an accuracy of +/-10%
- **AC to DC Conversion**: Full Bridge Rectifier
- **Isolated DC-DC Conversion**: Flyback Converter
- **Compliance**: USB-C Power Delivery Specifications

## Design Specifications

### AC to DC Conversion

- **Component**: Full Bridge Rectifier
- **Function**: Converts the AC mains voltage (230V, 50Hz) to a DC voltage suitable for the Flyback Converter.

### Isolated DC-DC Conversion

- **Component**: Flyback Converter
- **Function**: Provides isolation and converts the rectified DC voltage to an adjustable output voltage (15V to 20V) with the required current (3A).

### Output Voltage Levels

- **Voltage Levels**: 15V, 20V
- **Accuracy**: +/-10%

### Power and Current Requirements

- Refer to the USB-C specifications for detailed information on output wattage and current requirements, which have been analyzed and verified using MATLAB simulations.

## Getting Started

### Prerequisites

- Basic knowledge of power electronics and circuit design.
- Familiarity with MATLAB for simulations and analysis.
- Understanding of USB-C power delivery specifications.

### Tools and Components

- MATLAB (for simulations and design verification)
- Full Bridge Rectifier components
- Flyback Converter components
- Testing and measurement equipment

### Installation

1. **MATLAB Simulation**:
    - Open the MATLAB files in the `simulations` directory.
    - Run the simulations to verify the design specifications.

### Usage

1. **Power On**:
    - Connect the charger to the mains supply (230V, 50Hz).
    - Ensure the output voltage is set to the desired level (15V or 20V) using the adjustable control.

2. **Testing**:
    - Connect a USB-C device to the charger.
    - Measure the output voltage and current to verify they meet the specified levels.

## Documentation

- Detailed design documents, including schematics and PCB layouts, can be found in the `docs` directory.
- MATLAB simulation files and analysis reports are available in the `simulations` directory.
- Assembly and testing instructions are provided in the `hardware` directory.

## Contributing

We welcome contributions to improve the design and functionality of this USB Type-C charger. Please fork the repository, create a new branch, and submit a pull request with your changes.
