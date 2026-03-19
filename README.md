🧠 Dual-Port SRAM (RTL-to-GDSII) – 90nm CMOS using Cadence

📌 Project Overview

This project demonstrates the **design, verification, and physical implementation of a Dual-Port SRAM** using industry-standard **Cadence tools** in **90nm CMOS technology**.

The SRAM supports **simultaneous read/write operations through two independent ports**, making it suitable for high-performance applications such as cache memory, buffers, and embedded systems.

 🎯 Objectives

* Design a **parameterized Dual-Port SRAM** in Verilog
* Enable **simultaneous read/write operations**
* Perform **functional verification** using testbench
* Implement complete **RTL-to-GDSII flow**
* Achieve **timing closure and optimized layout**

 🧩 Architecture Overview

The Dual-Port SRAM consists of:

* **SRAM Array** – Stores data in matrix form (rows × columns)
* **Row/Column Decoders (Port A & B)** – Address selection
* **Write Drivers / Input Buffers** – Drive input data
* **Sense Amplifiers** – Read data from memory cells
* **Control Logic** – Manages operations
* **Collision Detection Unit** – Handles simultaneous access conflicts
* **Timing Control Unit** – Ensures synchronization

 ⚙️ Features

* True **Dual-Port (Read/Write on both ports)**
* Parameterized **data width and memory depth**
* **Synchronous design**
* Handles **simultaneous access scenarios**
* Fully **synthesizable RTL**
* Supports **Cadence RTL-to-GDS flow**

 🛠️ Tools & Technologies

| Stage           | Tool Used       |
| --------------- | --------------- |
| RTL Design      | Verilog HDL     |
| Simulation      | Cadence Xcelium |
| Synthesis       | Cadence Genus   |
| Physical Design | Cadence Innovus |
| Timing Analysis | Cadence Tempus  |
| Technology Node | 90nm CMOS       |

 🔄 Design Flow

RTL Design → Functional Verification → Synthesis → Floorplanning → Placement → Clock Tree Synthesis → Routing → Signoff → GDSII


 🧪 Verification Strategy

The design is verified using a testbench covering:

* Write operation (Port A / Port B)
* Read operation
* Simultaneous read/write
* Independent dual-port access
* Conflict scenarios (same address access)

 📊 Results

* Successfully synthesized design using Cadence Genus
* Completed placement and routing using Innovus
* Achieved timing closure
* Verified functionality through simulation
* Generated final **GDSII layout**

# 🔍 Waveforms Observed

* `clk`
* `we_a`, `we_b`
* `addr_a`, `addr_b`
* `din_a`, `din_b`
* `dout_a`, `dout_b`
* Internal memory (`mem[]`)

 🚀 Applications

* Cache memory
* Register files
* FIFO buffers
* Embedded SoC memory

🎓 Key Learnings

* End-to-end ASIC design flow
* Dual-port memory architecture
* Timing and physical design optimization
* Industry Cadence tool usage

 🔮 Future Enhancements

* ECC (Error Correction Code)
* Low-power design (clock gating)
* Multi-bank SRAM
* SoC integration (RISC-V)

👨‍💻 Author

ASHWIN RAO R
VLSI Design Enthusiast

This project is for academic and learning purposes.

