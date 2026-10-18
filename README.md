# Victoria Tjhin

Nanotechnology Engineering at the University of Waterloo. I work on both sides of the pin: RTL and analog IC design, embedded firmware, and the software that verifies it.

Currently a research assistant at the **Institute for Quantum Computing**, fabricating carbon nanotube single photon detectors and building the Python pipeline that automates our UV-Vis analysis.

**Looking for software, hardware, and electrical engineering co-op roles.**

[Portfolio](https://victoriatjhin.github.io) · [LinkedIn](https://www.linkedin.com/in/eetjhin) · eetjhin@uwaterloo.ca

---

### What I've built

**[SafeStep](https://devpost.com/software/safestep-a-safer-step-toward-independent-living)** — React Native · TypeScript · Python · Node.js · YOLO · Twilio · Hack the Valley 11
An AI-powered accessibility and safety app for blind and low-vision users. I built the React Native interface, integrated YOLO object detection for environmental awareness, optimized accelerometer fall detection to cut false positives by 30%, and built a Twilio SMS workflow that alerts a caregiver when a fall check-in goes unanswered for 10 seconds.

[![SafeStep demo video](https://img.youtube.com/vi/3eUGVj-XgpQ/hqdefault.jpg)](https://www.youtube.com/watch?v=3eUGVj-XgpQ)
▶ [Watch the demo](https://www.youtube.com/watch?v=3eUGVj-XgpQ) · [Devpost](https://devpost.com/software/safestep-a-safer-step-toward-independent-living)

**[ASIC optical autoalignment system](https://github.com/victoriatjhin/Probton)** — SSCS 2026 Chipathon · **Nominated by IEEE for tape-out**
Analog integrator and mixed-signal front end extracting vibration-synchronous alignment error from photodetector current, with a parallel X/Y RTL DSP pipeline that updates position every dither cycle at 50 MHz. Restructured inter-module handshaking to cut end-to-end latency by 40%.

**[Ethernet MAC receiver pipeline](https://github.com/victoriatjhin/10G-Ethernet-Parser)** — Verilog · SystemVerilog · AXI-Stream
Full MAC receive datapath from PCS decoder to AXI-Stream output. Pipelined CRC-32 engine carrying 64-bit beats at 156.25 MHz for a 10 Gb/s line rate, with asynchronous FIFO clock domain crossing and randomized and directed testbenches that caught CRC defects before integration.

**[Cycle-accurate cache simulator](https://github.com/victoriatjhin/cache-simulator)** — C++ · Intel Pin
Configurable line size, associativity, LRU and random eviction, and write-allocate policies. Trace-driven from real program memory access patterns, reporting hit rate, AMAT, and total execution cycles. Optimized address decoding and memory access for a 4× runtime reduction.

**[SPI-controlled PWM peripheral](https://github.com/victoriatjhin/SPI-Controlled-16-Channel-PWM-Peripheral-)** — Verilog · Tiny Tapeout
Register-mapped SPI slave and 8-bit PWM generator with duty and output-enable control, submitted for fabrication. Verified across all 256 duty settings on a 100 kHz SPI bus and 10 MHz clock.

**[Two-stage CMOS operational amplifier](https://github.com/victoriatjhin/vik_lyn__Analog_Bootcamp)** — Xschem · Magic VLSI · Ngspice
Differential-input, single-ended-output op-amp in 130 nm, sized and biased within a 5 mW budget. Physical layout taken to DRC-clean and LVS-matched.

**[STM32 PCB project](https://github.com/victoriatjhin/STM32_PCB_Project)** — KiCad
Custom board design and layout around an STM32 microcontroller.

---

### Tools

**Languages** Python, C++, TypeScript, SQL, MATLAB
**Frameworks** React Native, Node.js, NumPy, SciPy, Pandas, YOLO, Intel Pin
**HDL** Verilog, SystemVerilog
**EDA** Xschem, Magic VLSI, Netgen, Ngspice, Vivado, ModelSim/VCS, GTKWave
**Hardware** KiCad, SolidWorks, ESP32, oscilloscopes and bring-up
