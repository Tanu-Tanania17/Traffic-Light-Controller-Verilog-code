# Traffic-Light-Controller-Verilog-code
This is my first git repository.
<br>
Tanu Tanania [IIT Jammu]
<br> 
BTech., EE'27

# Traffic Light Controller (Verilog)

## 📌 Project Overview
This is a **Traffic Light Controller** implemented in Verilog HDL using **Xilinx Vivado**.  
The design controls traffic signals at a 4-way intersection using a finite state machine (FSM).

## ⚙️ Features
- Implemented as a **Moore FSM**
- Configurable timing for each light
- Synchronous reset and clock divider for human-visible light transitions
- Fully tested with simulation waveforms

## 🛠 Tools Used
- Xilinx Vivado 2023.x
- Verilog HDL

## 🔄 State Diagram
![State Diagram](docs/state_diagram.png)

## 📂 Repository Structure
- `src/` → Verilog source code  
- `tb/` → Testbenches  
- `sim/` → Simulation waveforms  
- `docs/` → Block diagrams, state diagrams, timing diagrams  

## 🖥 Simulation Results
![Waveform](sim/waveforms.png)

## 📜 How to Run
1. Open Vivado → Create new project → Add files from `src/` and `tb/`
2. Set `traffic_light_tb.v` as top for simulation
3. Run behavioral simulation

## 📌 Future Improvements
- Add pedestrian signal logic
- Add real-time parameter configuration via switches

---
💡 **Author:** Tanu (Electrical Engineering, IIT Jammu)  
📅 **Date:** Aug 2025
