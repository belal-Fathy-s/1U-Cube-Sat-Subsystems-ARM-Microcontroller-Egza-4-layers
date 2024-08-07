# 1U CubeSat Subsystems ARM Microcontroller Project

## Table of Contents
1. [Project Overview](#project-overview)
2. [Hardware](#hardware)
   - [PCB Designs](#pcb-designs)
   - [Subsystems](#subsystems)
3. [Software](#software)
   - [Subsystems](#subsystems-1)
4. [Getting Started](#getting-started)
5. [Contact](#contact)

## Project Overview

This project was my graduation project, done in cooperation with the Egyptian Space Agency. It aims to develop a 1U CubeSat with ARM microcontrollers managing its five primary subsystems. The repository contains both the hardware PCB designs and the software needed for each subsystem, providing a comprehensive guide for anyone interested in CubeSat technology. This project serves as a prototype using materials suitable for Earth-based testing.

## Hardware

### PCB Designs

The hardware section contains the PCB designs for each of the five subsystems. These designs are created using Altium Designer and each subsystem is a four-layer board.

### Subsystems

1. **Electrical Power System (EPS)**
    - **Description**: Manages the power distribution and energy storage for the CubeSat.
    - **PCB Design**: [EPS PCB Design](1U%20Cube-Sat%20PCB%20Designs/EPS%20ARM)

2. **Communication Subsystem (COMM)**
    - **Description**: Handles the transmission and reception of data between the CubeSat and ground stations.
    - **PCB Design**: [COMM PCB Design](1U%20Cube-Sat%20PCB%20Designs/COMM%20ARM)

3. **Attitude Determination and Control Subsystem (ADCS)**
    - **Description**: Maintains the orientation and stability of the CubeSat in orbit.
    - **PCB Design**: [ADCS PCB Design](1U%20Cube-Sat%20PCB%20Designs/ADCS%20ARM)

4. **Payload Subsystem (PLD)**
    - **Description**: Contains the scientific instruments and sensors for the mission-specific objectives.
    - **PCB Design**: [PLD PCB Design](1U%20Cube-Sat%20PCB%20Designs/PAYLOAD%20Subsystem)

5. **On-Board Computer Subsystem (OBC)**
    - **Description**: The central processing unit that coordinates the operations of all subsystems.
    - **PCB Design**: [OBC PCB Design](1U%20Cube-Sat%20PCB%20Designs/OBC%20ARM)

## Software

### Subsystems

Each subsystem has dedicated software to manage its operations. The software is written primarily in C/C++ for ARM microcontrollers, ensuring efficient and real-time performance. CubeMX was used to auto-generate much of the functionality, facilitating the development process.

1. **Electrical Power System (EPS)**
    - **Software**: [EPS Software](1U%20Cube-Sat%20Software/EPS_Software)

2. **Communication Subsystem (COMM)**
    - **Software**: [COMM Software](1U%20Cube-Sat%20Software/COMM_Software)

3. **Attitude Determination and Control Subsystem (ADCS)**
    - **Software**: [ADCS Software](1U%20Cube-Sat%20Software/ADCS_Software)

4. **Payload Subsystem (PLD)**
    - **Software**: [PLD Software](1U%20Cube-Sat%20Software/PLD_Software)

5. **On-Board Computer Subsystem (OBC)**
    - **Software**: [OBC Software](1U%20Cube-Sat%20Software/OBC_Software)

## Getting Started

To view and understand this project, follow these steps:

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/1U-Cube-Sat-Subsystems-ARM-Microcontroller-4-layers.git
    cd 1U-Cube-Sat-Subsystems-ARM-Microcontroller-4-layers
    ```

2. **Review the PCB Designs**:
    - The PCB design files are located in the `1U Cube-Sat PCB Designs` directory.

3. **Review the Software**:
    - The software files are located in the `1U Cube-Sat Software` directory.

## Contact

For any questions or inquiries, please contact:

- **Name**: Eng \ Belal Fathy Sayed
- **Email**: belalfathy1999@gmail.com
- **GitHub**: https://github.com/belal-Fathy-s
