<div align="center">

# 👋 Hi, I'm Jacob El-Omar
### M.Sc. in Electronic Systems • Aalborg University
**Software • Embedded Systems • Control & Robotics • Signal Processing & DSP**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jacob-el-omar/)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elomarjc)
[![Google Play](https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
[![Email](https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elomarjc@gmail.com)
[![Location](https://img.shields.io/badge/Location-Aalborg%2C%20Denmark-blue?style=for-the-badge&logo=google-maps&logoColor=white)](https://maps.google.com/?q=Aalborg,+Denmark)

</div>

---

## 👨‍🎓 About Me

Electronic Systems Engineer with an **M.Sc. in Electronic Systems** (Graduated June 2025, 120 ECTS) and **B.Sc. in Electronics & IT – Process Control** (Graduated August 2023, 180 ECTS) from **Aalborg University (AAU)**, Denmark.

I build systems across the hardware-software boundary — from real-time embedded firmware and feedback control to desktop mathematical software and interactive engineering simulators:

* 💻 **Software & Tools**: Cross-platform desktop & mobile (Python/PyQt6, Dart/Flutter with native C++ FFI), WebAssembly, and backend APIs.
* 🎛️ **Control & Robotics**: State-space MIMO, discrete cascaded PID with anti-windup, LQR, Kalman filtering (EKF/MEKF), and Autonomous Mobile Robots (AMRs / MiR200).
* 🎚️ **DSP & Audio**: Adaptive filtering (LMS, NLMS, RLS), blind source separation (FastICA), spectral analysis, and noise cancellation.
* ⚡ **Embedded & FPGA**: C/C++, FreeRTOS, Cypress PSoC 5LP (UDB schematic capture), ATmega2560 PlatformIO, and VHDL on Intel Cyclone V FPGAs.

---

## 🌟 Interactive Engineering Simulators & Digital Twins

A suite of real-time mathematical simulators and physical modeling testbenches running in the browser:

| Digital Twin & Architecture | Focus Domain | Core Engineering Stack | Live Simulator |
|---|---|---|:---:|
| **1. 5G/6G RF Channel Studio**<br>TDL Fading, Clarke Doppler, 256-QAM, EVM sweeps | **Telecom / RF** | DSP • Canvas • Web Workers | [🚀 Live Demo](https://elomarjc.github.io/5g-rf-channel-studio/) |
| **2. CubeSat AOCS Flight Simulator**<br>RK4 numerical integration, B-dot detumbling | **Aerospace** | Dynamics • Three.js • LEO Orbit | [🚀 Live Demo](https://elomarjc.github.io/cubesat-aocs-simulator/) |
| **3. Industrial SCADA Digital Twin**<br>ISA-101 HMI, IEC 61131-3 Structured Text, PID | **Automation** | SCADA • Modbus TCP • OT Security | [🚀 Live Demo](https://elomarjc.github.io/industrial-scada-digital-twin/) |
| **4. Hearing Aid DSP Studio**<br>Differential beamformer, NLMS feedback, 6-band WDRC | **Audio / MedTech** | DSP • Web Audio API • Filters | [🚀 Live Demo](https://elomarjc.github.io/hearing-aid-dsp-studio/) |
| **5. Wind Turbine Load Control**<br>15 MW turbine, Coleman MBC, Individual Pitch Control | **Renewable Energy** | Control • Fatigue Reduction | [🚀 Live Demo](https://elomarjc.github.io/turbine-load-control-twin/) |
| **6. PMSM FOC Drive Twin**<br>Space Vector PWM, Sliding Mode Observer, Clarke/Park | **Power Electronics** | Control • SVPWM • Motor Drives | [🚀 Live Demo](https://elomarjc.github.io/pmsm-foc-drive-twin/) |
| **7. Industrial Pump Hydrodynamics**<br>Affinity Laws, NPSHa vs NPSHr, MCSA stator FFT | **Fluid Systems** | Hydrodynamics • Cavitation • FFT | [🚀 Live Demo](https://elomarjc.github.io/pump-hydrodynamics-digital-twin/) |
| **8. Naval Radar Signal Studio**<br>Cell-Averaging CFAR, MTI Doppler clutter filter | **Defense & Radar** | DSP • CA-CFAR • PPI Radar Display | [🚀 Live Demo](https://elomarjc.github.io/naval-radar-signal-studio/) |
| **9. Cobot Kinematics & Observer**<br>6-DOF UR5e arm, DLS singularity solver, collision observer | **Robotics** | Kinematics • ISO/TS 15066 Safety | [🚀 Live Demo](https://elomarjc.github.io/cobot-kinematics-momentum-twin/) |

---

## 💻 Featured Projects & Open Source

### 📐 [OpenMath — Desktop & Web Computer Algebra System (CAS)](https://github.com/elomarjc/openmath)
> *Python 3.10+ • PyQt6 • SymPy • Matplotlib MathText • WebAssembly (Pyodide)*
* **Interactive Document Worksheet**: Chronologically stacked calculation cells with high-DPI LaTeX formulas, exact/numeric toggles (2–50 digits), and worksheet export to compilable LaTeX (`.tex`) and Markdown.
* **Symbolic Math & Matrix Wizard**: Visual dialog for arbitrary $M \times N$ matrices, determinants, eigenvalues/eigenvectors, RREF, differential equations (`dsolve`), and series expansions.
* **Embedded Hardware Engine**: Integrated tooling for bitwise masks, floating-point to Q-format fixed-point conversion (`to_q`, `from_q`), and IEEE-754 single/double precision sign/exponent/mantissa inspection.
* [GitHub Repository →](https://github.com/elomarjc/openmath) • [Live Web App on GitHub Pages →](https://j2kjonas.github.io/OpenMath/)

### 🐠 [Grow A Fish — Commercial Mobile Game & Real-Time Ecosystem](https://github.com/elomarjc/grow-a-fish-case-study)
> *Flutter • Flame Engine • Dart FFI & C++ SoLoud • Supabase Realtime • X25519/AES-GCM*
* Published mobile game on Google Play (330+ modules) featuring zero-latency native audio via Dart FFI and deterministic procedural level generation.
* Implemented client-side End-to-End Encrypted (E2EE) chat using X25519 ECDH key exchange and AES-256-GCM.
* [View Technical Case Study →](https://github.com/elomarjc/grow-a-fish-case-study) • [Google Play Store →](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)

### 🫀 [Active Adaptive Noise Cancellation (ANC)](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)
> *Master's Thesis (Aalborg University & Ai Health Highway) • MATLAB • Python • LMS/NLMS/RLS • FastICA*
* Researched and implemented real-time active acoustic noise cancellation to isolate physiological stethoscope signals from ambient hospital noise.
* Preserved low-frequency cardiac valve sounds ($S_1, S_2$) while achieving up to **+34 dB SNR improvement** across acoustic benchmarks.
* [View Thesis Repository →](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)

### 🛰️ [AAUSAT6 CubeSat: Attitude Determination & Control (ADCS)](https://github.com/elomarjc/advanced-control-digital-systems)
> *Aalborg University Satellite Mission • MATLAB • Orbital Dynamics • B-dot • LQR • $H_\infty$*
* Designed flight stabilization in LEO: B-dot magnetic detumbling using magnetorquers to eliminate launch tip-off spin, and LQR momentum wheel control for 3-axis target pointing.
* [View AAUSAT6 Repository →](https://github.com/elomarjc/advanced-control-digital-systems)

### ⚙️ [Real-Time Anti-Sway Control of a 2D Gantry Crane](https://github.com/elomarjc/gantry-crane-anti-sway-control)
> *Bachelor's Project • Embedded C/C++ • ATmega2560 • PlatformIO • Cascaded PID*
* Derived dynamic Newtonian models and designed discrete cascaded controllers suppressing pendulum sway during transit on a physical laboratory crane.
* Low-level C++ firmware implementation with anti-windup, Forward Euler velocity filtering, and motor current saturation limits.
* [View Crane Control Repository →](https://github.com/elomarjc/gantry-crane-anti-sway-control)

---

## 🛠️ Technical Matrix

| Discipline | Technologies & Frameworks |
|---|---|
| **Programming** | C / C++, Python, Dart, C#, JavaScript / TypeScript, MATLAB / Simulink, VHDL, SQL |
| **Embedded & Hardware** | FreeRTOS, Cypress PSoC 5LP (UDB Schematic Capture), ATmega2560, PlatformIO, STM32, ESP32, Intel Cyclone V FPGA (Terasic DE0-CV) |
| **Control & Automation** | State-Space MIMO, Cascaded PID, LQR / LQG, $H_\infty$ Robust Control, Kalman Filtering (EKF/MEKF), IEC 61131-3 (ST, FBD, LD), MiR200 AMRs |
| **Signal Processing & DSP** | Adaptive Filters (LMS, NLMS, RLS), FastICA, STFT, FFT, CA/OS-CFAR, MTI Doppler, Spectral Analysis, WDRC |
| **Protocols & Communication** | Modbus TCP, MQTT, WebSockets, CAN bus, I2C, SPI, UART, RS485, UWB Positioning, Cryptography (X25519, AES-256-GCM) |
| **Software & UI** | PyQt6, Flutter / Flame Engine, Dart FFI (Native C++), WebAssembly (Pyodide), Three.js, Node.js, Git, Docker |
| **EDA & Prototyping** | Intel Quartus Prime, ModelSim, Autodesk EAGLE, LTspice, Altium Designer, Onshape (3D CAD & Rapid Prototyping) |

---

<div align="center">

### 📬 Connect With Me
**[LinkedIn](https://www.linkedin.com/in/jacob-el-omar/)** • **[Email](mailto:elomarjc@gmail.com)** • **[Google Play](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)** • **[GitHub](https://github.com/elomarjc)**  
*Aalborg, Denmark*

</div>
