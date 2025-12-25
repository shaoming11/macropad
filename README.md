# Shaoming's Macropad
This is my first project that involved the use of KiCad and Fusion 360. 

# Features
- 4 keyboard buttons
- RP2040 microcontroller
- Firmware connected to QMK
- 3D Printable Case using Fusino 360
- PCB designed using KiCad

# PCB

Schematic Layout

<img width="680" height="467" alt="Screenshot 2025-12-24 at 10 10 59 PM" src="https://github.com/user-attachments/assets/675ac9a5-b819-45ea-bb6b-55a1a7b2cb75" />

PCB Layout

<img width="429" height="592" alt="Screenshot 2025-12-24 at 10 11 38 PM" src="https://github.com/user-attachments/assets/aeed4dde-3e8a-4591-a26b-d55d1d3c5e41" />

Dimensions: 42.862 x 62.930 mm



# CAD Model

Model

<img width="619" height="452" alt="Screenshot 2025-12-24 at 10 09 05 PM" src="https://github.com/user-attachments/assets/38c45b0f-5f9f-45c2-bb0e-5f82b8ebbdd0" />

Sketches

<img width="615" height="520" alt="Screenshot 2025-12-24 at 10 09 57 PM" src="https://github.com/user-attachments/assets/b07be496-77a1-4e9e-9cfc-3e7e5917b4f7" />


# Bill of Materials

Seeed XIAO RP2040 - since you're soldering, you can mount it SMD style! Please note it is significantly harder than doing it through-hole, so if it's your first time soldering I would avoid it.

Through-hole 1N4148 Diodes (Max 20x)

MX-Style switches (Max 16x)

EC11 Rotary encoders (Max 2x)

0.91 inch OLED displays (Max 1x) (make sure the pin order is GND-VCC-SCL-SDA, otherwise it WILL NOT WORK)

Blank DSA keycaps (White)

SK6812 MINI-E LEDs (Max 16x)

M3x16mm screws

M3x5mx4mm heatset inserts

# What I learned
I learned about the basics of PCB design through KiCad, exclusively working on schematics and PCB layout. Performing DRC helped me understand how to turn schematics into a printable PCB layout.
