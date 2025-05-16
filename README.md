# Sequential LED Runner Driver Circuit V1.1


 📌 Project Overview

This project is a PCB design for a **Sequential LED Runner Circuit**, which drives 10 LEDs in a running pattern using digital ICs and a timer. It is suitable for learning:

- PCB design fundamentals
- Schematic to PCB transition
- Manual routing practices
- 3D visualization in Altium Designer

This is part of my PCB design learning journey using **Altium Designer 25.2.1**.


 🎯 Features

- Drives 10 LEDs sequentially.
- Uses ICs like 555 Timer and CD4017 Decade Counter.
- Designed in a compact and symmetric layout.
- Optimized for educational and demonstration purposes.



 🧠 Learning Outcomes

- Schematic design and net connection mapping.
- Manual and auto-routing on PCB.
- Placement of components for aesthetics and function.
- 3D rendering of PCB layout in Altium Designer.



 🗂️ Files Included

| File | Description |
|------|-------------|
| `schematic.pdf` | Complete schematic diagram of the circuit |
| `routing.pdf`   | 2D PCB layout showing traces, via, and component placement |
| `raw_routing_2D.jpg` | Snapshot of the PCB routing from Altium |
| `routing3D.jpg` | 3D View of PCB layout showing physical component placement |
| `*.PrjPcb, *.PcbDoc, *.SchDoc` | [Not Uploaded] Altium Designer project files |



 🔩 Components Used

- NE555 Timer (U2)
- CD4017 Decade Counter (U1)
- 10 × Red LEDs (D1–D10)
- Resistors: R1–R13
- Capacitors: C1, C2
- Power input header (VCC, GND)



 🖥️ Software Used

- [Altium Designer 25.2.1](https://www.altium.com/)
- PDF reader for schematic/layout files



 🔧 How It Works

- The **NE555 timer** is configured as an astable multivibrator to generate a clock signal.
- This signal is fed into the **CD4017 decade counter**, which sequentially turns ON each of the 10 outputs.
- Each output drives an LED, creating a "running light" effect.



 🧑‍💻 Designed By

**Mohit Jagtap**  
Electronics & Telecommunication Engineering  
Dr. D. Y. Patil Institute of Engineering Management and Research, Akurdi, Pune


