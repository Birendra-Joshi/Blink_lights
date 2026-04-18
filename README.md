# Blink_lights
🦇 Batman LED Chaser
Project Overview
This project explores custom PCB design by combining creativity with electronics. It features a Batman logo–shaped PCB that drives 10 LEDs in a smooth “Knight Rider”–style chasing sequence. The system is powered by an NE555 timer acting as a clock source and a CD4017 decade counter handling the LED sequencing.
How It Works
The NE555 timer generates a continuous pulse signal, which is fed into the CD4017 counter. With each clock pulse, the counter activates the next output pin, creating a sequential lighting effect across the LEDs. A potentiometer is included to adjust the speed of the animation.
Development Process
1. Schematic Design
The circuit was first designed in EasyEDA, connecting the timer IC, counter IC, LEDs, resistors, capacitors, and control components to define the logic flow.
2. Custom PCB Design
A Batman logo silhouette was imported and used as a guide to trace a unique board outline. Components were carefully placed to fit within the shape while maintaining functionality.
3. Routing
Connections between components were established using the auto-router, ensuring efficient and clean copper trace paths across the PCB.
4. Fabrication
Gerber files were generated and submitted to JLCPCB for manufacturing, bringing the digital design into a physical board.
Bill of Materials (BOM)
CD4017 Decade Counter (CD4017BCN)
NE555 Timer IC (C46749)
Power Header (C492401)
Debug Header (C81276)
Electrolytic Capacitor (C62934)
Ceramic Capacitor (C249157)
1kΩ Resistor (C713997)
470Ω Resistor (C58592)
Potentiometer – Speed Control (C118912)
LEDs ×10 (C2895480)
Project Assets
Schematic Design: 
PCB Layout: Custom Batman-shaped physical design
