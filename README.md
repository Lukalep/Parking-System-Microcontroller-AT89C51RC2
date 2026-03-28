# Smart Parking System (Microprocessor-Based)

## Project Overview
Automated parking gate management system designed for a single-lane entry/exit scenario. [cite_start]The system ensures safe vehicle flow, prevents collisions, and tracks real-time occupancy[cite: 4, 39, 44].

### Key Features
* [cite_start]**Capacity Management:** Supports up to 15 vehicles with automated entry blocking when full[cite: 7, 29, 34].
* [cite_start]**Conflict Resolution:** Advanced logic to handle simultaneous entry/exit requests, preventing counter errors and physical collisions[cite: 39, 43, 44, 49].
* [cite_start]**Real-time Monitoring:** Occupancy status displayed via **UART interface** and LED signaling[cite: 50, 61, 62].
* [cite_start]**Gate Timing:** Automated 5-second hold intervals for safe passage[cite: 25, 52].

### Technical Implementation
The project is modularized for efficiency and reliability:
* `interrupts.obj`: Handling sensor inputs and real-time events.
* `timer.obj`: Managing gate operation delays and system clock.
* `uart.obj`: Serial communication for status reporting.
* `rampa.obj`: Control logic for the gate actuator.

### How to Use
The compiled `parking.hex` file is ready for deployment on the target microcontroller. [cite_start]Detailed logic flows and system states are available in the `docs` folder[cite: 19, 21].
