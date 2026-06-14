# Industrial-Elevator-Control-System-Simulation---Siemens-TIA-Portal-Factory-I-O
Designed and simulated a comprehensive multi-floor elevator control logic using Ladder Diagram (LD) in Siemens TIA Portal.  Integrated the PLC controller with Factory I/O to simulate real-time physical kinematics and validate system responsiveness.  Programmed robust safety interlocks and emergency stop protocols prior to executing network
# Industrial Elevator Control System 

## 📝 Project Overview
A comprehensive simulation of an industrial elevator control system. This project demonstrates the integration of programmable logic controllers (PLC) with 3D factory simulation to handle multi-floor elevator operations, call prioritization, and strict safety interlocks.

## 🛠️ Tools & Technologies Used
*   **PLC Programming:** Siemens TIA Portal (Ladder Logic)
*   **3D Simulation Environment:** Factory I/O
*   **Controller:** Siemens S7-1200 / S7-1500 (Virtual PLC via PLCSIM)

## ✨ Key Features
*   **Dynamic Floor Calls:** Efficiently handles internal cabin requests and external floor calls.
*   **Safety Interlocks:** Prevents door operation while the elevator is in motion.
*   **Emergency Stop Logic:** Robust E-stop protocols that immediately halt the system and trigger safety alarms.
*   **Real-time Tag Mapping:** Seamless communication between TIA Portal and Factory I/O sensors/actuators.

## 📸 Demonstration
<img width="802" height="377" alt="image" src="https://github.com/user-attachments/assets/75a873b7-5b80-46f3-b3a0-0e3e45a13818" />

## 📂 Repository Contents
*   `TIA_Portal_Project/`: Contains the complete Siemens TIA Portal project files.
*   `FactoryIO_Scene/`: The simulation environment file.
*   `Elevator_Ladder_Logic.pdf`: A readable PDF export of the complete Ladder Diagram networks.
