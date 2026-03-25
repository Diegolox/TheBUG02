# TheBUG02

## 🇬🇧 English

**TheBUG02** is a custom **all-in-one control PCB** designed for a **two-wheel differential drive robot**.  
The project aims to provide a compact and integrated embedded platform that combines the essential hardware blocks required in a small mobile robot: power management, motor driving, microcontroller integration, battery monitoring, and development interfaces.

Instead of relying on multiple external modules, this board concentrates the complete low-level electronics into a single PCB, making the robot easier to assemble, more reliable, and better suited for rapid prototyping and iterative development.

## What the project consists of

TheBUG02 is built as a robotics electronics platform where the main control and power subsystems are already integrated on-board. The design includes:

- **ESP32-based control system** as the main processing unit
- **Integrated motor drivers** for controlling the DC motors of the robot
- **Integrated DC-DC converter** for efficient power conversion from the battery supply
- **Integrated linear regulator** for stable regulated voltage rails
- **Battery voltage sensing** for supply monitoring and power supervision
- **ESP-PROG programming/debugging interface** for firmware upload and debugging
- **Compact full-SMD PCB design** for reduced size and improved manufacturability

## Project purpose

The purpose of TheBUG02 is to serve as a compact embedded controller for mobile robotics applications, especially small autonomous robots based on differential drive kinematics.

This board is intended to simplify the hardware side of robotics development by offering a self-contained solution that can be used for:

- Differential drive motor control
- Battery-powered robot platforms
- Embedded firmware development with ESP32
- Rapid robotics prototyping
- Autonomous navigation experiments
- Educational and research-oriented robotics projects

## Design approach

The project follows a clear design philosophy: reduce external wiring, improve electrical integration, and create a cleaner and more robust electronics architecture for mobile robots.

By integrating the power stage, motor drivers, processor, and monitoring circuitry into a single board, TheBUG02 becomes a practical base for building complete robotic systems with fewer external dependencies.

## Project status

**Status:** In development / prototyping
