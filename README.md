# Autonomous Rover

> 🚧 **Status: In Development**

An autonomous mobile rover being developed as part of ECE Project Lab at Texas Tech University. The project focuses on integrating sensors, motor control, embedded hardware, and software to enable autonomous navigation and environmental detection.

## Project Objectives

- Develop autonomous navigation capabilities
- Detect environmental conditions using onboard sensors
- Control DC motors through embedded control hardware
- Integrate sensing, processing, power, and motor-control subsystems
- Test and refine rover behavior through iterative prototyping

## Current Hardware

- Raspberry Pi
- Line sensor
- Color sensor
- 9.6V battery
- DC motors
- Breadboard and prototyping components

Additional hardware will be added as the rover design develops.

## System Architecture

The current system is being developed around the following structure:

**Sensors → Embedded Controller → Control Logic → Motor Control → DC Motors**

### Sensors
The rover uses sensors to gather information about its environment. Current development includes line and color sensing.

### Embedded Controller
The controller processes sensor inputs and will execute the logic required to determine rover behavior.

### Motor Control
The motor-control subsystem will interface the controller with the rover's DC motors, allowing direction and movement to be controlled electronically.

## Current Progress

- Defined initial system architecture
- Identified major rover subsystems
- Obtained initial sensing and control hardware
- Selected line and color sensors for environmental detection
- Began planning sensor integration and motor control
- Developing hardware integration and testing strategy

## Next Steps

- Test sensors individually
- Characterize sensor outputs
- Develop and test motor-control circuitry
- Test DC motor operation
- Integrate sensors with the controller
- Assemble initial rover prototype
- Develop autonomous control logic
- Perform system-level testing

## Engineering Concepts

- Embedded Systems
- Robotics
- Sensor Interfacing
- DC Motor Control
- Hardware Integration
- System Architecture
- Prototyping
- Troubleshooting

## Project Development

This repository will be updated throughout development with code, hardware documentation, testing results, design changes, and prototype progress.
