# Verilog Masterclass Assignments

Assignments from the **Verilog Masterclass** conducted by **Hariprasad Sir** organized by **Anmaya Technologies**.

This repository contains Verilog codes, testbenches, and waveform screenshots for various digital design assignments.

---

## 📚 Assignments Overview

### 🔸 Assignment 1: 4:1 Multiplexer
- **Design File**: `mux4to1.v`
- **Testbench**: `mux4to1_tb.v`
- **Screenshot**: `mux4to1_waveform.png`

### 🔸 Assignment 2: Full Adder
- **Design File**: `full_adder.v`
- **Testbench**: `full_adder_tb.v`
- **Screenshot**: `full_adder_waveform.png`

### 🔸 Assignment 3: 2:1 Multiplexer
- **Design File**: `mux2to1.v`
- **Testbench**: `mux2to1_tb.v`
- **Screenshot**: `mux2to1_waveform.png`

### 🔸 Assignment 4: Up-Down Counter with Reset
- **Design File**: `up_down_counter.v`
- **Testbench**: `up_down_counter_tb.v`
- **Screenshot**: `up_down_counter_waveform.png`

---

## 📦 How to Simulate

You can run all testbenches using [EDA Playground](https://edaplayground.com/) or locally using **Icarus Verilog**:

```bash
# Compile
iverilog -o tb_mux mux4to1.v mux4to1_tb.v

# Simulate
vvp tb_mux

# View Waveform
gtkwave dump.vcd
