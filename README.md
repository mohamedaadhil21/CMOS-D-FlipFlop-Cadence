🔷 CMOS Based Positive Edge Triggered D Flip-Flop
Full Custom VLSI Design using Cadence Virtuoso

👨‍💻 Author
Mohamed Athil S
B.E Mechatronics Engineering
Nehru Institute of Engineering and Technology

📌 Project Overview
This project presents the transistor-level design, simulation, layout, and physical verification of a CMOS-based Positive Edge Triggered D Flip-Flop using Cadence Virtuoso.

The design follows the complete Full Custom VLSI Design Flow, including:
Schematic Design
Functional Simulation
Layout Implementation
Design Rule Check (DRC)
Layout Versus Schematic (LVS) Verification
The circuit successfully passes both DRC and LVS with zero errors, ensuring fabrication readiness.

🎯 Objectives
Design a CMOS Positive Edge Triggered D Flip-Flop
Implement Master-Slave architecture
Perform transient simulation
Create optimized physical layout
Verify design using DRC and LVS
Understand full-custom VLSI flow

🧠 Theory Background
A D Flip-Flop is a sequential logic circuit that stores one bit of data.
It transfers input D to output Q only at the rising edge of the clock.
Why CMOS?
CMOS technology is used because it offers:
Low power consumption
High noise immunity
Full voltage swing
Scalability for VLSI systems
The design uses:
CMOS Inverters
Transmission Gates
Master-Slave Configuration

⚙️ Design Methodology
1️⃣ Schematic Design
The circuit was designed at transistor level using PMOS and NMOS transistors.
Master latch active when CLK = 0
Slave latch active when CLK = 1
Output updates only at rising clock edge

2️⃣ Simulation
Transient analysis was performed using ADE.
Simulation Conditions:
VDD = 1.8V
Pulse clock input
Alternating data input
Observation:
Output changes only at positive clock edge
No glitches
Stable logic levels

3️⃣ Layout Design
Layout was implemented following SCMOS design rules:
PMOS placed in N-well
NMOS in P-substrate
Proper metal routing
Power rails (VDD & GND) defined
Optimized transistor placement
🧪 Verification Results

✅ DRC (Design Rule Check)
Errors: 0
Layout satisfies fabrication rules

✅ LVS (Layout Versus Schematic)
Netlist Match: Successful
No mismatches found
✔ Design is physically and logically verified

📊 Results
The CMOS Positive Edge Triggered D Flip-Flop:
Captures input at rising clock edge
Shows correct sequential behavior
Fully verified at schematic and layout level
Ready for fabrication

📂 Project Structure
Copy code

📁 CMOS_DFF_Project
 ├── Schematic Design
 ├── Simulation Results
 ├── Layout Design
 ├── DRC Report
 ├── LVS Report
 └── Project Report PDF

🚀 Applications
Registers
Counters
Shift Registers
Memory Circuits
Microprocessors
Digital Signal Processing Systems

🛠 Tools Used
Cadence Virtuoso
Analog Design Environment (ADE)
DRC & LVS Verification Tools

📈 Skills Demonstrated
CMOS Circuit Design
Sequential Logic Design
Full Custom VLSI Layout
DRC & LVS Verification
Transient Simulation Analysis

🏁 Conclusion
This project demonstrates complete understanding of CMOS sequential logic design and full custom VLSI flow using Cadence tools.
The successful DRC and LVS verification confirms both logical and physical correctness of the design.

## 📊 Simulation Waveform

The transient simulation confirms that the output Q changes only at the rising edge of the clock signal.

<p align="center">
  <img src="waveform.png" width="700"/>
</p>
