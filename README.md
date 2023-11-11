# USB to 12V Boost Converter

## Overview
This repository features a USB to 12V Boost Converter designed with the LT1371 from Analog Devices. It efficiently raises the input voltage from a USB port (5V) to 12V, providing a reliable power source for small electronic devices.

## Key Features
- Boosts USB voltage (5V) to 12V
- Utilizes LT1371 from Analog Devices
- Efficient and compact design

## Purpose
Ideal for powering small devices that require a 12V supply, such as:
- Motor drivers like L298N, which is a dual H-Bridge motor driver.
- Motors like stepper motors and brushless motors, which often require a 12V supply to operate effectively.

## Design Considerations
Careful consideration was given to component selection and topology to ensure optimal performance and efficiency.

## PCB 3D Image
![PCB 3D Image]([path/to/pcb_image.png](https://github.com/zack1ng/images/blob/main/PCB.png?raw=true))

## Simulation
Simulation was performed using LTspice. The following graph illustrates the voltage progression from 5V to 12V over time.
![LTspice Simulation]([path/to/simulation_image.png](https://github.com/zack1ng/images/blob/main/Simulation.png?raw=true))

## Usage
This project is designed for personal use, and the design files are not provided. You can, however, find a detailed description of the design process in the [design documentation](docs/design_documentation.md).

## License
This project is provided without a specific license. All rights reserved.



