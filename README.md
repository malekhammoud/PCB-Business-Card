# PCB Business Card Project

This project documents the process of designing and manufacturing a custom PCB business card using EasyEDA and the Hack Club OnBoard grant.

## 🛠 Overview

This business card:
- Transmits a URL via NFC
- Lights up using harvested energy from a phone

---

## Components Used

| Component                     | Description                                  |
|------------------------------|----------------------------------------------|
| NT3H2111W0FHKH NFC Chip      | Handles NFC + energy harvesting              |
| 2V LED (e.g., C2296)         | Lights up using harvested energy             |
| 47Ω Resistor                 | Current-limiting resistor for the LED        |
| 220nF Capacitor              | Smoothing capacitor for energy output        |
| 25x48mm NFC Antenna (trace) | PCB trace to act as the NFC antenna          |

---

## Schematic
![image](https://github.com/user-attachments/assets/3310a814-16e0-4af0-8daa-93370ee8e47b)

Designed in EasyEDA:
- Capacitor connected between VOUT and GND
- LED + resistor between VOUT and GND
- VCC connected to VOUT
- Antenna connected between LA and LB

---

## PCB Layout

Converted schematic to PCB:
- Board Size: `88.9mm x 50.8mm`, round rectangular, 4mm radius
- 2-layer PCB (TopLayer red, BottomLayer blue)
- Components placed to avoid overlapping traces
- Auto-router + manual routing for final connections
- Custom silkscreen added for personal branding
![image](https://github.com/user-attachments/assets/358183ae-901a-4bf2-be1d-d3d8b77de8a6)
![image](https://github.com/user-attachments/assets/4c925f65-902b-420a-a2b5-894e03c152e1)
![image](https://github.com/user-attachments/assets/bc2d2551-b4d9-4752-beb3-ec0ec2fb2eec)
