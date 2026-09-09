<div align="center">

# 👋 Hi, I'm Jacob El-Omar
### M.Sc. in Electronic Systems • Aalborg University
**Software • Automation • Regulation (Control) • Digital Systems & DSP • Communication**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jacob-el-omar/)
[![Google Play](https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
[![Email](https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elomarjc@gmail.com)
[![Location](https://img.shields.io/badge/Location-Aalborg%2C%20Denmark-blue?style=for-the-badge&logo=google-maps&logoColor=white)](https://maps.google.com/?q=Aalborg,+Denmark)

</div>

---

## 👨‍🎓 About Me

I hold a **Master of Science (M.Sc.) in Electronic Systems** and a **Bachelor of Science (B.Sc.) in Electronics & IT** (Specialization in Control Engineering) from **Aalborg University (AAU)**, Denmark. 

My engineering background combines 5 years of Aalborg University's Problem-Based Learning (PBL) model with modern software engineering across five core disciplines:

* 💻 **Software**: Cross-platform application engineering (Dart/Flutter with native C++ FFI), backend and script engineering (Python, C#, Node.js, REST APIs), and databases (PostgreSQL, Supabase, SQLite, MySQL, InfluxDB). Creator of [Grow A Fish](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish) on Google Play.
* 🤖 **Automation**: Industrial robotics, Autonomous Mobile Robots (MiR200), smart production testbeds (AAU 5G Smart Production Lab), and path planning (1st Place, AAU RoboCup Tournament; Predictive Collision Avoidance).
* 🎛️ **Regulation (Control Engineering)**: Dynamic systems modeling and closed-loop feedback control: state-space MIMO control, discrete cascaded PID with anti-windup, LQR optimal control, and spacecraft attitude control (AAUSAT6 CubeSat ADCS & 3-DoF Satellite Simulator).
* 🎚️ **Digital (DSP & Embedded Systems)**: Digital signal processing (LMS, NLMS, RLS adaptive filters, FastICA, STFT, Mel-spectrograms), parametric spectral estimation, sensor data fusion (EKF/UKF/MEKF), and embedded firmware (C/C++, FreeRTOS, Cypress PSoC 5LP, ATmega2560).
* 📡 **Kommunikation (Communication & Networks)**: Telemetry and network protocols: MQTT message brokering, real-time WebSockets, Ultra-Wideband (UWB) RF positioning, bus architectures (I2C, SPI, UART, RS485, CAN), and cryptographic communications (X25519 ECDH + AES-256-GCM).

---

## 💼 Experience & R&D

* **AI/ML & Signal Processing Engineer (Internship / Thesis R&D)** — *Ai Health Highway* (Sep 2024 – Jun 2025)
  * Developed real-time signal enhancement algorithms for **AiSteth** smart stethoscopes using adaptive filtering (**LMS, NLMS, RLS**) and Blind Source Separation (**FastICA**) to cancel ambient acoustic interference.
  * Preserved crucial low-frequency cardiac valve sounds ($S_1, S_2$) and murmurs, improving SNR by up to **+34 dB**.
  * Collaborated with international research teams to validate screening models for cardiovascular and pulmonary conditions under medical-grade diagnostic constraints.
* **IT & Web Developer (Volunteer)** — *Dawah Danmark* (Jan 2026 – Present)
  * Modernized and optimized platform performance, database integration, and reliability.

---

## 🌟 Featured Engineering Showcases

### 1. 📡 [5G/6G RF Channel & Constellation Studio](https://github.com/elomarjc/5g-rf-channel-studio) • [🚀 Live WebApp](https://elomarjc.github.io/5g-rf-channel-studio/)
> **Interactive Physical-Layer (PHY) Channel Emulator & Automated 3GPP TS 38.104 Testbench**  
> *Pillars: Software • Digital (DSP) • Kommunikation*  
> *Stack: Vanilla ES6 • HTML5 Canvas (60 FPS Phosphor Scope) • 3GPP TDL Fading • Clarke/Jakes Doppler • AWGN • BPSK-256QAM • OFDM*
* **Real-Time Instrumentation**: High-performance in-browser Vector Signal Analyzer (VSA) running at 60 FPS with digital phosphor persistence and interactive 5G NR OFDM resource grid (14 symbols $\times$ 24 subcarriers).
* **3GPP Radio Channel Emulation**: Mathematically modeled Rayleigh/Rician multipath fading with tunable $K$-factor, vehicle Doppler frequency shifts up to 300+ km/h at 3.5 GHz mid-band, local oscillator phase noise, and transceiver mixer I/Q imbalance.
* **Automated Compliance Verification**: Implemented automated Monte Carlo sweeps benchmarking empirical Bit Error Rates against closed-form theoretical AWGN error functions ($\text{erfc}$ / $Q$-function) and official 3GPP TS 38.104 EVM limits ($<3.5\%$ for 256-QAM, $<8\%$ for 64-QAM).
* **Dataset Generation**: Built-in one-click telemetry export to Keysight PathWave-compatible CSV logs and structured JSON datasets for offline AI/ML channel estimation.
* **[🚀 Launch Live WebApp →](https://elomarjc.github.io/5g-rf-channel-studio/)** • **[View Repository →](https://github.com/elomarjc/5g-rf-channel-studio)**

---

### 2. 🛰️ [CubeSat AOCS Flight Simulator](https://github.com/elomarjc/cubesat-aocs-simulator) • [🚀 Live WebApp](https://elomarjc.github.io/cubesat-aocs-simulator/)
> **3D Interactive Spacecraft Attitude Determination & Control System (AOCS) & LEO Orbit Simulator**  
> *Pillars: Regulation (Control) • Software • Digital • Space Systems*  
> *Stack: Vanilla ES6 • Three.js (WebGL) • RK4 Numerical Integrator • Quaternion Kinematics • B-dot Detumble • Reaction Wheels*
* **3D Interactive Space Operations**: High-detail procedural 3U CubeSat with gold MLI foil, solar panels, internal flywheels, and Earth globe with sidereal spin, atmospheric glow, and Aalborg Ground Station ($57.05^\circ\text{N}, 9.92^\circ\text{E}$) acquisition-of-signal (AOS) tracking beam.
* **Rigid Body Dynamics & RK4 Integrator**: 10-state differential equation solver propagating unit quaternions $[\mathbf{q}]$, angular rates $[\boldsymbol{\omega}]$, and wheel speeds $[\boldsymbol{\omega}_{rw}]$, coupled with gravity gradient, aerodynamic drag, and solar radiation pressure torques.
* **Flight Computer FSM**: Implemented magnetic B-dot detumbling ($\mathbf{m} = -k \dot{\mathbf{B}}$) to damp tip-off tumble rates ($40^\circ/\text{s} \to <0.5^\circ/\text{s}$), Nadir Earth-pointing PD control in LVLH frame, Sun tracking mode, dynamic Aalborg ground station slew, and cross-product reaction wheel desaturation.
* **Mission Telemetry & CSP Export**: Real-time angular velocity damping strip chart, reaction wheel RPM bars (up to 6500 RPM), and one-click telemetry export formatted for GomSpace CSP (CubeSat Space Protocol) / CAN bus logs.
* **[🚀 Launch Live WebApp →](https://elomarjc.github.io/cubesat-aocs-simulator/)** • **[View Repository →](https://github.com/elomarjc/cubesat-aocs-simulator)**

---

### 3. 🐠 [Grow A Fish — Technical Case Study](https://github.com/elomarjc/grow-a-fish-case-study)
> **Published Commercial Mobile Game & Real-Time Multiplayer Ecosystem**  
> *Pillars: Software • Kommunikation • Digital*  
> *Stack: Flutter • Flame Engine • Bonfire RPG • Dart FFI & C++ SoLoud • Supabase Realtime • Hive NoSQL • X25519/AES-GCM*
* **Architecture**: Engineered an end-to-end mobile game (330+ modules) published on Google Play.
* **Deterministic Networking**: Formulated deterministic seed-based procedural level generation to eliminate mobile multiplayer jitter and bandwidth overhead.
* **Low-Latency Native Audio**: Integrated the `SoLoud` C++ audio engine via Dart FFI with custom LRU caching and auto-recovery to eradicate Android audio latency.
* **Hardware-Backed Cryptography**: Implemented client-side End-to-End Encrypted (E2EE) chat using X25519 ECDH key exchange and AES-256-GCM.
* **In-Game Tooling**: Built a custom grid-based level design studio with high-speed binary Hive serialization.
* **[View Full Case Study →](https://github.com/elomarjc/grow-a-fish-case-study)** • **[Google Play Store →](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)**

---

### 4. 🫀 [Active Adaptive Noise Cancellation (ANC)](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)
> **Master's Thesis in Electronic Systems • Aalborg University**  
> *Pillars: Digital (DSP) • Software (Python/MATLAB)*  
> *Stack: MATLAB • Python • Adaptive Filters (LMS, NLMS, RLS) • FastICA • Mel-Spectrograms • STFT • In collaboration with Ai Health Highway*
* **Core Research**: Developed real-time active acoustic noise cancellation algorithms to isolate physiological stethoscope signals from ambient hospital interference.
* **Mathematical Formulations**: Implemented and benchmarked Least Mean Squares (LMS), Normalized LMS (NLMS), Recursive Least Squares (RLS), and FastICA source separation.
* **Empirical Validation**: Demonstrated up to **+34 dB SNR improvements** across synthetic and physical acoustic chamber testbeds while preserving critical cardiac murmur frequencies.
* **[View Thesis Repository →](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)**

---

### 5. 🛰️ [AAUSAT6 CubeSat: Attitude Determination & Control (ADCS)](https://github.com/elomarjc/advanced-control-digital-systems)
> **Master's Project (Semester 8) • Systems of Systems & Space Engineering • Aalborg University**  
> *Pillars: Regulation (Control) • Digital • Kommunikation*  
> *Stack: MATLAB • Orbital Dynamics • B-dot Detumbling • LQR Target Tracking • Momentum Wheels • $H_\infty$ Robust Control*
* **Satellite Mission**: Designed the flight control and stabilization architecture for the **AAUSAT6 CubeSat** in Low Earth Orbit (LEO).
* **Control Modes**: Implemented magnetic B-dot detumbling using magnetorquers to eliminate launch tip-off spin, LQR state-feedback with integral action for Nadir/Target pointing via momentum wheels, and robust $H_\infty$ controllers to reject aerodynamic and solar radiation disturbance torques under uncertainty.
* **[View AAUSAT6 Repository →](https://github.com/elomarjc/advanced-control-digital-systems)**

---

### 6. ⚙️ [Real-Time Anti-Sway Control of a 2D Gantry Crane](https://github.com/elomarjc/gantry-crane-anti-sway-control)
> **Bachelor's Project (Semester 6) • Electronic Systems & Control Engineering • Aalborg University**  
> *Pillars: Regulation (Control) • Automation • Digital (Embedded)*  
> *Stack: Embedded C/C++ • Arduino Mega 2560 (ATmega2560) • PlatformIO • Cascaded PID • Discrete Signal Processing*
* **Physical System**: Derived Newtonian dynamic models for the hoisting block, trolley, and pendulum. Linearized models for frequency-domain transfer functions.
* **Control Design**: Designed 3 discrete PD controllers (crane head Y-pos, trolley X-pos, head sway angle $\theta$), matched via Sensetools parameter tuning to physical step-response benchmarks.
* **Firmware Implementation**: Wrote low-level C++ firmware with discrete low-pass filtering, Forward Euler velocity estimation, actuator current saturation limits, and anti-windup.
* **[View Crane Control Repository →](https://github.com/elomarjc/gantry-crane-anti-sway-control)**

---

### 7. 🤖 [Multi-Sensor Positioning & AMR Fleet Integration](https://github.com/elomarjc/indoor-positioning-amr-integration)
> **AAU 5G Smart Production Lab • Industrial IoT & Autonomous Robotics**  
> *Pillars: Automation • Kommunikation • Software*  
> *Stack: Python • Multi-Threading • Ultra-Wideband (UWB) • Computer Vision (CV) • MQTT • InfluxDB • MATLAB*
* **Sensor Fusion Hub**: Fused real-time spatial telemetry from active UWB RF tags, overhead Computer Vision tracking, and Autonomous Mobile Robots (AMRs / MiR200).
* **Concurrency & Safety**: Engineered a 9-thread concurrent processing engine in Python with mutex synchronization, proximity breach warnings, and an alarm exemption engine for tagged payloads.
* **Analytics**: Integrated InfluxDB v2 time-series storage and developed empirical Cumulative Distribution Function (CDF) statistical accuracy models.
* **[View Positioning Repository →](https://github.com/elomarjc/indoor-positioning-amr-integration)**

---

### 8. 🛰️ [3-DoF Satellite Simulator CoM Calibration & Dynamics](https://github.com/elomarjc/satellite-simulator-adcs-calibration)
> **Master's Project (Semester 7) • Control of Manipulators • Aalborg University**  
> *Pillars: Regulation (Control) • Digital (Embedded) • Kommunikation*  
> *Stack: MATLAB • Simulink • FreeRTOS • Cypress PSoC 5LP • Spherical Air Bearing • MEKF Sensor Fusion*
* **Experimental Testbed**: Designed Center-of-Mass (CoM) auto-balancing algorithms for a 3-DoF spherical air-bearing satellite simulator.
* **State Estimation**: Formulated Multiplicative Extended Kalman Filters (MEKF) fusing IMU rate gyros, accelerometers, and 3-axis magnetometers.
* **Embedded Control**: Developed real-time FreeRTOS C tasks on Cypress PSoC 5LP for automated stepper counterweight actuation.
* **[View Calibration Repository →](https://github.com/elomarjc/satellite-simulator-adcs-calibration)**

---

### 9. 🎛️ [Multivariable Distillation Column LQR State-Space Control](https://github.com/elomarjc/multivariable-distillation-column-control)
> **Master's Project (Semester 7) • Advanced Control Engineering • Aalborg University**  
> *Pillars: Regulation (Control) • Software (MATLAB)*  
> *Stack: MATLAB • MIMO State-Space • LQR Optimal Control • Kalman Filter Observer • Decoupling*
* **Chemical Process**: Modeled non-linear binary distillation dynamics (Wood-Berry column benchmark).
* **MIMO Regulation**: Designed optimal Linear Quadratic Regulators (LQR) with integral tracking and steady-state decoupling to eliminate cross-channel product impurity disturbances.
* **[View Distillation Repository →](https://github.com/elomarjc/multivariable-distillation-column-control)**

---

## 🛠️ Technical Matrix

| Discipline | Core Technologies, Frameworks & Protocols |
|---|---|
| **Programming & Scripting** | Python, C/C++, Dart, C#, JavaScript/TypeScript (ES6+), MATLAB / Simulink, SQL |
| **Regulation & Control** | State-Space MIMO, Cascaded PID, LQR / LQG, $H_\infty$ Robust Control, B-dot Magnetic Detumbling, Anti-Windup |
| **Signal Processing & DSP** | Adaptive Filtering (LMS, NLMS, RLS), Blind Source Separation (FastICA), STFT, FFT, Mel-Spectrograms, EKF / UKF / MEKF |
| **Embedded & Hardware** | FreeRTOS, Cypress PSoC 5LP, ATmega2560, Arduino Mega, PlatformIO, STM32 |
| **Kommunikation & Networks** | 3GPP 5G NR PHY, OFDM, BPSK/QAM, MQTT, WebSockets, Ultra-Wideband (UWB), CAN bus, I2C, SPI, UART, RS485 |
| **Software & Cross-Platform** | Flutter, Flame Game Engine, Dart FFI (Native C++ interop), Node.js, HTML5 Canvas / WebGL |
| **Databases & DevOps** | PostgreSQL, Supabase, InfluxDB, SQLite, Hive NoSQL, Git, GitHub Actions, Docker |

---

## 📬 Contact & Connect

* **Email**: [elomarjc@gmail.com](mailto:elomarjc@gmail.com)
* **LinkedIn**: [linkedin.com/in/jacob-el-omar](https://www.linkedin.com/in/jacob-el-omar/)
* **Google Play**: [El-Omar Studio](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
* **Location**: Aalborg, North Denmark (Nordjylland)
