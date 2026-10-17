# programmable-educational-robot
Electrical Engineering Projects

# Programmable Educational Robot Platform

## Overview

This repository documents the hardware design of a programmable educational robotics platform intended for STEM education and embedded systems learning.

The goal of the project was to create a four-wheel robotic vehicle that would allow students to experiment with sensors, actuators, communication interfaces, and programming concepts in a practical, hands-on environment.

The platform was designed to expose students to real-world embedded systems development by providing access to a wide range of programmable peripherals and communication technologies.

The platform combines environmental sensors, motion sensing, obstacle detection, wireless communication, infrared communication, and motor control technologies into a single educational development platform.

My responsibility within the project was exclusively focused on hardware engineering, including electronic circuit design, schematic capture, component selection, PCB layout development, and hardware architecture design.

---

## Project Status

This project reached the hardware design phase, including system architecture definition, schematic development, and PCB layout design.

Due to project constraints, the design was not manufactured and no physical prototype was produced.

The repository is presented as an example of the engineering design process and hardware architecture development for an educational robotics platform.

---

## Project Goals

The platform was designed to:

- Introduce students to embedded systems development
- Provide practical experience with sensors and actuators
- Teach hardware-software interaction
- Support motor control and robotics programming
- Allow experimentation with wireless communication technologies
- Create an expandable learning platform for STEM education
- Demonstrate real-world engineering concepts through hands-on projects
- Encourage problem-solving through hardware and software integration

---

## System Block Diagram

<img width="1328" height="803" alt="image" src="https://github.com/user-attachments/assets/fd3fd113-7c87-46ec-ae7a-403fef3b6b8d" />


High-level architecture of the educational robot platform based on an Arduino Mega microcontroller.

---

## System Architecture

The platform was designed around an Arduino Mega microcontroller, selected for its large number of GPIO pins, multiple communication interfaces, and suitability for integrating numerous sensors and peripherals on a single educational platform.

The robot was designed as a four-wheel robotic vehicle featuring independent motor control for each wheel.

Students would be able to develop software that interacts with multiple onboard sensors and communication interfaces while exploring real-world engineering concepts such as:

- Sensor integration
- Motor control
- Embedded programming
- Wireless communication
- Environmental monitoring
- Signal processing
- Obstacle detection
- Autonomous navigation
- Line following
- Human-machine interaction

---

## Hardware Design

The hardware platform integrates sensing, communication, control and power management functions on a custom-designed PCB.

### Schematic Design

<img width="1328" height="874" alt="image" src="https://github.com/user-attachments/assets/46f345a8-e362-4aa0-a700-6f84654b8443" />


High-level schematic showing the integration of sensors, communication modules, motor drivers and the Arduino Mega controller.

### PCB Layout

<img width="825" height="436" alt="image" src="https://github.com/user-attachments/assets/582116d8-ea2d-495e-a566-0cfd3b6fdd4e" />


Custom PCB designed to integrate sensors, motor drivers, communication modules and supporting circuitry.

### 3D PCB Visualization

<img width="820" height="434" alt="image" src="https://github.com/user-attachments/assets/591b1c48-a36b-447f-a8c9-32c99a3ea794" />


3D rendering of the PCB used to verify component placement and mechanical integration before manufacturing.

---

## Hardware Features

### Arduino Mega-Based Control System

The hardware architecture was built around an Arduino Mega microcontroller, providing sufficient processing capability and I/O resources to support multiple sensors, motor drivers, and communication modules simultaneously.

### Independent Motor Control

The robot utilizes four independently controllable drive motors.

Applications:

- Differential steering
- Motion control experiments
- Robotics programming exercises
- Autonomous navigation algorithms
- Motor characterization studies

Motor control is implemented using two TB6612FNG motor driver ICs, allowing independent control of all four wheel motors.

---

## Sensor and Peripheral Suite

The platform integrates a broad range of sensors and peripherals intended for educational experimentation.

### Environmental Monitoring

#### DHT22 Temperature and Humidity Sensor

Provides environmental measurements for:

- Sensor interfacing exercises
- Data acquisition projects
- Environmental monitoring applications

#### BMP180 Barometric Pressure Sensor

Provides atmospheric pressure measurements for:

- Environmental monitoring
- Data logging exercises
- Sensor calibration projects
- Weather-related experiments

---

### User Interaction

#### Programmable Push Button

Allows students to implement:

- Event-driven programming
- User input handling
- State machine exercises
- User interface concepts

#### Buzzer

Can be used for:

- Audio feedback
- Alarm generation
- Interactive projects
- Status indication

---

### Obstacle Detection

#### SRF05 Ultrasonic Distance Sensor

Provides distance measurements for:

- Obstacle avoidance
- Autonomous navigation
- Environmental mapping exercises

#### GP2Y0A21YK0F Infrared Distance Sensor

Provides short-range distance measurements for:

- Object detection
- Obstacle avoidance
- Sensor comparison exercises
- Multi-sensor fusion experiments

---

### Motion Sensing

#### ADXL335 Accelerometer

A three-axis analog accelerometer used for:

- Motion detection
- Tilt sensing
- Orientation measurements
- Robotics control experiments
- Inertial sensing exercises

---

### Acoustic Sensing

#### Microphone

Supports experiments involving:

- Sound detection
- Audio processing
- Event monitoring
- Signal analysis

---

### Line Following

#### Dual TCRT5000 Optical Sensors

Two optical sensors enable:

- Line-following applications
- Reflective surface detection
- Autonomous navigation exercises
- Sensor calibration experiments

---

### Wireless Communication

#### CC2541 Bluetooth Module

Provides short-range wireless communication for:

- Mobile device connectivity
- Wireless control applications
- Sensor data transmission
- Bluetooth communication experiments

#### ESP8266 Wi-Fi Module

Provides Wi-Fi connectivity for:

- IoT projects
- Remote monitoring
- Cloud connectivity experiments
- Network programming exercises
- Wireless telemetry applications

---

### Infrared Communication

#### Infrared LED

Used for:

- Infrared transmission
- Remote control experiments
- Optical communication exercises

#### TSOP4838 Infrared Receiver

Allows students to:

- Decode IR remote control signals
- Implement wireless control systems
- Experiment with communication protocols
- Build infrared communication applications

---

## Hardware Design Scope

My engineering responsibilities included:

- Requirements analysis
- System architecture development
- Component selection
- Electronic circuit design
- Schematic capture
- Sensor interface design
- Communication interface design
- Power distribution design
- Signal routing and integrity considerations
- Motor control hardware design
- PCB layout development
- Design verification

Firmware, robotics software, and educational content development were outside the scope of my responsibilities.

---

## Engineering Challenges

Key design challenges included:

- Integrating numerous sensors and peripherals on a single platform
- Providing sufficient I/O resources for future expansion
- Designing reliable motor control circuitry
- Managing electrical noise generated by DC motors
- Supporting multiple wireless communication technologies
- Balancing functionality, complexity, and manufacturing cost
- Creating an architecture suitable for educational use
- Ensuring compatibility between analog and digital sensor interfaces
- Designing an expandable platform for future developments

---

## Design Deliverables

This repository contains:

- System architecture diagrams
- Hardware block diagrams
- Schematics
- PCB layout screenshots
- 3D PCB renderings
- Design documentation
- Component selection notes

---

## Educational Applications

The platform was intended to support practical exercises in:

- Embedded programming
- Robotics
- Electronics
- Sensor integration
- Environmental monitoring
- Motor control
- Wireless communication
- Bluetooth communication
- Wi-Fi networking
- Infrared communication
- IoT systems
- Automation
- Real-time systems
- Data acquisition
- Signal processing

---

## Lessons Learned

This project provided valuable experience in the design of complex embedded hardware systems that integrate sensing, actuation, communication, and control functions into a single educational platform.

Particular focus areas included:

- System-level architecture design
- Sensor integration
- Motor driver implementation
- Wireless communication hardware
- PCB layout for mixed-signal systems
- Educational hardware design considerations

Although the project did not progress to prototype manufacturing, it served as a comprehensive exercise in hardware architecture development, PCB design, and system-level engineering.

The project demonstrates the complete hardware design workflow from requirements definition through schematic capture and PCB layout development.
