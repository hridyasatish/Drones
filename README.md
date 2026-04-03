# Quadcopter UAV Build and System Integration

**Author:** Hridya Satish Pisharady  
**Role:** Embedded Systems Engineer  
**Institution:** University of California, Irvine  
**Program:** Master of Embedded and Cyber-Physical Systems  
**Project Category:** UAV System Integration, Power Systems, and Validation  
**Location:** Irvine, California, USA  

---

## Project Overview

This repository documents my end-to-end build, integration, and validation of a quadcopter UAV system completed as part of a graduate embedded systems project.

The work focuses on **hardware–software integration at the system level**, including electrical wiring, power-path design, flight-controller configuration, communication interfaces, and validation workflows required to achieve stable and reliable flight operation.

---

## Key Contributions

- Integrated a complete UAV system including **brushless motors, ESCs, battery power system, flight controller, GPS, and radio receiver**
- Performed **power-path wiring and validation**, ensuring correct distribution from battery to ESCs and onboard electronics
- Configured and validated flight control firmware using **ArduCopter and Mission Planner**
- Established **UART-based receiver and telemetry communication** for control and monitoring
- Executed **system-level validation and debugging**, including motor direction verification, control mapping, and flight-mode testing
- Captured and preserved final configuration parameters for **repeatable system bring-up and troubleshooting**

---

## Technical Focus Areas

- Embedded hardware integration  
- Power system and wiring validation  
- Flight controller configuration and firmware setup  
- Communication interfaces (UART-based systems)  
- System-level debugging and validation  
- Reproducible configuration and documentation  

---

## Technologies Used

- ArduCopter  
- Mission Planner  
- ExpressLRS / EdgeTX  
- BLHeli_S ESC firmware  
- GPS modules  
- ESP32 (Telemetry integration)  
- UART-based subsystem communication  

---

## Validation Workflow

A structured validation process was followed to ensure system reliability:

- Verified **motor order and rotation direction**
- Validated **radio control mapping and failsafe behavior**
- Tested **flight modes and arming/disarming logic**
- Confirmed **telemetry communication and GPS lock**
- Tuned system parameters for stable and controlled flight

Final system parameters were saved to enable **consistent and reproducible deployment**.

---

## Certification

- FAA TRUST Certification (Recreational UAS Safety Test)

---

## What This Project Demonstrates

This project reflects hands-on experience in:

- Embedded systems at the **hardware–software boundary**
- **Power system integration and validation**
- Real-world **system debugging and troubleshooting**
- Integration of **multiple subsystems into a working platform**
- Engineering workflows focused on **reliability and repeatability**

This is a **full hardware build and validation project**, not a simulation-based implementation.

---

## Repository Structure

```text
quadcopter-uav-build/
├── README.md
├── ParameterFiles/
│   └── final_params.param
├── docs/
│   ├── diagrams/
│   ├── guides/
│   └── images/
