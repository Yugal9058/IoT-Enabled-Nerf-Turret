# IoT-Enabled-Nerf-Turret
Smart Shot is an IoT-enabled automated Nerf turret designed as both a prototype for military system upgrades and a modular educational tool for STEM learning. It provides an affordable and adaptable platform for remote targeting and firing, controlled via Bluetooth

1. Project Overview
Smart Shot is an IoT-enabled Nerf turret designed as a prototype for military system upgrades and a modular STEM educational tool. It allows for real-time remote targeting and firing via a smartphone interface.

3. Features
Wireless Control: Real-time command input via HC-05 Bluetooth module with 100–200ms latency.
Precision Movement: 2-axis pan-and-tilt mechanism (0∘to 90∘) using MG90s metal-geared servos.
High-Speed Firing: Dual Type 130 DC motors powering a flywheel propulsion system with a 4–6 meter range.
Modular Power: Independent power stages for logic and motors using LM2596 buck converters to prevent system resets.

4. Hardware Components
Microcontroller: Arduino Nano R3.
Communication: HC-05 Bluetooth Module.
Actuators: 3x MG90s Servos (Pan, Tilt, Feed).
Motors: 2x Type 130 Brushed DC Motors.
Power: 9V DC Adapter, USB Cable, and LM2596 Buck Converters.
Chassis: Custom 3D-printed mechanical frame.

5. Software Requirements
Language: C++.
IDE: Arduino IDE.
Libraries: Servo.h (for PWM control) and SoftwareSerial (for Bluetooth communication).

6. Future Roadmap
Integration of computer vision for autonomous target tracking.
AI-driven targeting algorithms.
Cloud-based remote telemetry and control.

Recommended Folder Hierarchy

├── Firmware/             # Arduino (.ino) source code
├── Hardware/             # Circuit diagrams (Fritzing/Schematics)
├── Mechanical/           # STL files for 3D printing
├── Docs/                 # PDF of the SSRN publication
└── README.md             # Project documentation


![69423c05-e9c4-4cf8-af80-ad996a0f7f73](https://github.com/user-attachments/assets/1517cb47-221d-4212-911c-abdd45b4a19e)
![fb97c1e6-9a8e-47df-af20-10564a73d50f](https://github.com/user-attachments/assets/8e4c9dee-a211-4ea9-959c-e25e6e9c5e13)
![5680a868-87f4-418b-b93c-172e4bf59f35](https://github.com/user-attachments/assets/eb654bda-2fd3-4126-a63b-e73c70f145d3)
![0d93b755-18f3-4618-9b83-66158a1d9b6f](https://github.com/user-attachments/assets/0891c8e6-deec-4f7b-be82-a3952923d9b9)
![f23065af-b16a-4b0a-a008-846295b6e588](https://github.com/user-attachments/assets/ad669446-d38e-4676-ab7d-fa0107207ba8)
![30457923-a0ee-49f3-8b7a-e5c09554be71](https://github.com/user-attachments/assets/85deac96-6617-436a-b3a0-0f0812a5c997)


https://github.com/user-attachments/assets/c4f09b4d-325f-47c4-b05a-ecfb66d03fd1


