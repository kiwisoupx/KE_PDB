# Autonomous Cat Robot - Power Distribution & Battery Management System

This repository contains the schematic and PCB design files for the Power Distribution Board (PDB) and Battery Management System (BMS) used in our autonomous cat robot project. These systems manage and distribute power from a USB power bank to various components across the robot.

## 🐾 Project Overview

The autonomous cat robot is a collaborative robotics project that integrates mechanical design, embedded systems, and intelligent behavior. The PDB/BMS subsystem plays a critical role in ensuring reliable, safe, and efficient power delivery throughout the robot's operation.

This board handles:
- **Voltage regulation**
- **Power distribution**
- **Battery protection and monitoring**
- **System-level power architecture**

## Subsystem Description
The Power Distribution and Battery Management System (PDB/BMS) is a single integrated board that handles all power-related needs for the autonomous cat robot. It works as the electrical backbone of the system, safely managing energy flow from a USB power bank and distributing regulated power to all critical subsystems.
Rather than splitting power handling and battery safety into separate modules, this board merges them into one compact and efficient design, streamlining both wiring and system integration.

## Key Features
- Designed to be powered from a standard USB-C power bank—removing the need for custom charging hardware and making development more accessible and safe
- Features overvoltage, undervoltage, and overcurrent protection to prevent damage to the system during unexpected power conditions.
- Supplies stable power to key components such as the Raspberry Pi, sensors, and servo motors via multiple voltage rails (e.g., 5V, 3.3V).
- Includes a control signal to enable or disable power delivery across the board—useful for sequencing startup or allowing software control over the robot’s power state.
- Specifically built to support the power needs and physical constraints of a small autonomous robot, with attention paid to current capacity, mounting, and signal isolation.



