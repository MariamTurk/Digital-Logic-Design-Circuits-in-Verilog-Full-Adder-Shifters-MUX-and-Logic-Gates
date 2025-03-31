# Digital Logic Design Circuits in Verilog

This project showcases the implementation of fundamental digital logic components using Verilog. It includes the design and simulation of arithmetic, logic, and data manipulation modules such as full adders, shifters, multiplexers, and basic logic gates.

## 👤 Author
- **Name**: Mariam Turk  


## 🔧 Implemented Components

### ➕ Full Adder
- A combinational logic circuit that adds two binary digits and a carry-in bit.
- Produces a sum and carry-out output.

### ⏪ Left and Right Shifters
- **LEFT_SHIFT**: Shifts input bits to the left by one or more positions.
- **RIGHT_SHIFT**: Shifts input bits to the right by one or more positions.

### 🎛️ 8-to-1 Multiplexer (MUX8-1)
- Selects one of eight input signals and forwards it to a single output line.
- Controlled by 3 selection bits.

### ➗ Arithmetic Units
- **DIV**: Computes `(X / 2) + Y`
- **SUB**: Computes `X - (Y / 2)`

### 🔘 Basic Logic Gates
- **NAND Gate**: Outputs LOW only if all inputs are HIGH.
- **NOR Gate**: Outputs HIGH only if all inputs are LOW.
- **NOT Gate**: Inverts the input signal.
- **XOR Gate**: Outputs HIGH if an odd number of inputs are HIGH.

---

## 🧪 Simulation & Testing
Each module is individually tested using Verilog testbenches. Simulation results validate the correct logical behavior of all designed circuits.

> 📸 Simulation waveform snapshots and detailed outputs were included in the original report.

---

## 📂 Folder Structure (Suggested)
digital-logic-project/ ├── full_adder.v ├── left_shift.v ├── right_shift.v ├── mux8_1.v ├── div_add.v ├── sub_half.v ├── gates/ │ ├── nand_gate.v │ ├── nor_gate.v │ ├── not_gate.v │ └── xor_gate.v ├── testbenches/ │ ├── full_adder_tb.v │ ├── mux_tb.v │ └── ... ├── waveform_screenshots/ │ └── *.png ├── README.md └── digital-report.pdf


---

## 📌 Tools & Technologies
- **HDL**: Verilog
- **Simulation Software**: ModelSim / Vivado / Icarus Verilog

---

## 📈 Future Enhancements
- Combine all components into a functional ALU
- Add GUI simulation using GTKWave
- Implement 4-bit or 8-bit versions of arithmetic units

---

## 📜 License
This project is for academic use only. All rights reserved by the author.

---

## 🧾 Acknowledgments
Thanks to the course instructor and teaching assistants for their guidance throughout the project.


