# Victoria Tjhin

Nanotechnology Engineering at the University of Waterloo. I work on both sides of the pin: RTL and analog IC design, embedded firmware, and the software that verifies it.

Currently a research assistant at the **Institute for Quantum Computing**, fabricating carbon nanotube single photon detectors and building the Python pipeline that automates our UV-Vis analysis.

**Looking for software, hardware, and electrical engineering co-op roles.**

[Portfolio](https://victoriatjhin.github.io) · [LinkedIn](https://www.linkedin.com/in/eetjhin) · eetjhin@uwaterloo.ca

---

### What I've built

**[Ethernet MAC receiver pipeline](#)** — Verilog · SystemVerilog · AXI-Stream
Full MAC receive datapath from PCS decoder to AXI-Stream output. Pipelined CRC-32 engine sustaining a 64-bit data path via byte-serial decomposition, with asynchronous FIFO clock domain crossing and testbenches covering protocol compliance and edge cases.

**[Cycle-accurate cache simulator](#)** — C++ · Intel Pin
Configurable line size, associativity, LRU and random eviction, and write-allocate policies. Trace-driven from real program memory access patterns, reporting hit rate, AMAT, and total execution cycles. Validated against hand-calculated ground truth.

**[SPI-controlled PWM peripheral](#)** — Verilog · Tiny Tapeout
Register-mapped peripheral with duty cycle generation and output enable, submitted for fabrication. Verified across a 100 kHz SPI bus and a 10 MHz system clock.

**[Two-stage CMOS operational amplifier](#)** — Xschem · Magic VLSI · Ngspice
Differential-input, single-ended-output op-amp in 130 nm, sized and biased within a 5 mW budget. Physical layout taken to DRC-clean and LVS-matched.

**[ASIC optical autoalignment system](#)** — SSCS 2026 Chipathon
Analog integrator and mixed-signal front end extracting vibration-synchronous alignment error from photodetector current, with a parallel X/Y RTL DSP pipeline for closed-loop correction.

---

### Tools

**Languages** C++, Python, SQL, MATLAB
**HDL** Verilog, SystemVerilog
**EDA** Xschem, Magic VLSI, Netgen, Ngspice, Vivado, ModelSim/VCS, GTKWave
**Hardware** KiCad, SolidWorks, ESP32, oscilloscopes and bring-up
