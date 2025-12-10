
# SPI Master–Slave Verification Project (SystemVerilog)

## 📘 Overview
This project implements a **Serial Peripheral Interface (SPI)** Master with a corresponding
verification testbench written in **SystemVerilog**.  
The design focuses on correct SPI clock generation, data shifting, and transaction control,
while the testbench exercises the interface and validates data transfers in a self-checking manner.

This project demonstrates **RTL design + verification skills**, suitable for VLSI and
verification-oriented roles.

---

## ✅ Features
- SPI **Master** implementation  
- 8-bit serial data transfer  
- Clock-driven serial shifting using **SCLK**
- Active-low reset support  
- Controlled transfer start using `newd` signal  
- Internal counters for bit-level transfer tracking  
- Self-checking testbench to verify correct SPI functionality  

---

## 📁 Repository Structure

---

## 🛠️ How to Run / Simulate

You can simulate this design using any SystemVerilog-compatible simulator
(ModelSim, Questa, VCS, Xcelium, etc.).

```bash
# Compile RTL and testbench
vlog design.sv tb.sv

# Run simulation
vsim -c work.tb -do "run -all; quit"


