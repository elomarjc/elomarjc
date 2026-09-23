<div align="center">

# Jacob El-Omar

### M.Sc. in Electronic Systems • Aalborg University
**Embedded Software • Digital Signal Processing • Control & Automation • Real-Time Systems**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jacob-el-omar/)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elomarjc)
[![Google Play](https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
[![Email](https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elomarjc@gmail.com)
[![Location](https://img.shields.io/badge/Location-Aalborg%2C%20Denmark-blue?style=for-the-badge&logo=google-maps&logoColor=white)](https://maps.google.com/?q=Aalborg,+Denmark)

</div>

---

## Executive Summary

I hold a **Master of Science (M.Sc.) in Electronic Systems** and a **Bachelor of Science (B.Sc.) in Electronics & IT** (specialization in Process Control) from **Aalborg University (AAU)**, Denmark.

My engineering work connects physical dynamic systems, control theory, and digital signal processing with modern high-performance software. Over 5 years of Problem-Based Learning (PBL) and commercial engineering, I have delivered end-to-end solutions spanning embedded firmware (FreeRTOS, ARM Cortex-M, FPGA/VHDL), real-time signal enhancement algorithms (adaptive filtering, blind source separation), industrial automation testbeds, and production mobile and desktop applications.

---

## Flagship Engineering Projects

### [OpenMath — Desktop & Web Computer Algebra System (CAS)](https://github.com/J2KJonas/OpenMath)
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Python 3.10+, PyQt6, SymPy, Matplotlib MathText, Pyodide*

* **Architecture**: An open-source interactive computer algebra system and technical worksheet environment designed for engineering mathematics, calculus, and embedded systems.
* **Symbolic Math Core**: Exact symbolic computation, hierarchical section folding scopes, dynamic 2D graph plotting, visual matrix wizard, and high-DPI LaTeX typeset rendering.
* **Embedded Hardware Tooling**: Integrated IEEE-754 single/double precision bit decomposition, bitwise logic masking, and Q-format fixed-point conversions (`to_q`, `from_q`).
* **Cross-Platform**: Distributed as a native desktop application (macOS, Linux, Windows) alongside an in-browser Web Demo running via client-side WebAssembly.
* **Links**: [GitHub Repository](https://github.com/J2KJonas/OpenMath) • [Live Web Demo](https://j2kjonas.github.io/OpenMath/)

---

### [Grow A Fish — Production Mobile Game & Real-Time Ecosystem](https://github.com/elomarjc/grow-a-fish-case-study)
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Shipped on Google Play • Flutter, Flame Engine, C++ FFI SoLoud, Supabase, Hive, X25519/AES-GCM*

* **Architecture**: Commercial cross-platform virtual pet simulator and real-time arcade ecosystem spanning 330+ modular Dart files.
* **Native Low-Latency Audio**: Integrated the `SoLoud` C++ audio engine directly into Flutter via Dart FFI with custom LRU caching and auto-recovery, completely bypassing Android platform-channel latency.
* **Deterministic Netcode**: Engineered 64-bit seed-synchronized procedural generation over WebSockets to eliminate mobile packet jitter and reduce bandwidth to discrete event flags.
* **Hardware-Backed Cryptography**: Implemented client-side End-to-End Encrypted (E2EE) chat using X25519 ECDH key exchange and AES-256-GCM backed by the Android Keystore / iOS Keychain.
* **Links**: [Technical Case Study](https://github.com/elomarjc/grow-a-fish-case-study) • [Google Play Store](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)

---

### [Active Adaptive Noise Cancellation (ANC) — Master's Thesis R&D](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)
*Master's Thesis in collaboration with Ai Health Highway & Prof. Jan Østergaard • MATLAB, Python, LMS/NLMS/RLS, FastICA, STFT*

* **Research**: Developed and validated real-time acoustic signal enhancement algorithms for smart digital stethoscopes (**AiSteth**) under clinical diagnostic constraints.
* **Acoustic Filtering**: Implemented and benchmarked Least Mean Squares (LMS), Normalized LMS (NLMS), Recursive Least Squares (RLS), and FastICA Blind Source Separation.
* **Empirical Results**: Achieved up to **+34 dB SNR improvements** across physical acoustic chamber testbeds while preserving crucial low-frequency cardiac valve sounds ($S_1, S_2$) and murmurs.
* **Links**: [Thesis Repository](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)

---

## Interactive Digital Twins & Simulators

A suite of 9 real-time mathematical digital twins, physical modeling testbenches, and interactive browser simulators:

| Digital Twin | Focus Area & Key Algorithms | Access |
| :--- | :--- | :--- |
| **5G/6G RF Channel Studio** | TDL Fading, Clarke/Jakes Doppler, 256-QAM, 3GPP EVM sweeps | [Live Simulator](https://elomarjc.github.io/5g-rf-channel-studio/) • [Source](https://github.com/elomarjc/5g-rf-channel-studio) |
| **CubeSat AOCS Flight Simulator** | RK4 orbit integration, quaternion kinematics, B-dot detumbling | [Live Simulator](https://elomarjc.github.io/cubesat-aocs-simulator/) • [Source](https://github.com/elomarjc/cubesat-aocs-simulator) |
| **Industrial SCADA & Process Twin** | ISA-101 HMI, IEC 61131-3 Structured Text runtime, Modbus TCP | [Live Simulator](https://elomarjc.github.io/industrial-scada-digital-twin/) • [Source](https://github.com/elomarjc/industrial-scada-digital-twin) |
| **Hearing Aid Adaptive Beamforming** | Head shadow diffraction, NLMS feedback cancellation, 6-band WDRC | [Live Simulator](https://elomarjc.github.io/hearing-aid-dsp-studio/) • [Source](https://github.com/elomarjc/hearing-aid-dsp-studio) |
| **Wind Turbine Load Control Twin** | 15 MW offshore model, Coleman MBC transform, Individual Pitch Control | [Live Simulator](https://elomarjc.github.io/turbine-load-control-twin/) • [Source](https://github.com/elomarjc/turbine-load-control-twin) |
| **PMSM Field-Oriented Control (FOC)** | Clarke/Park transforms, Space Vector PWM, Sliding Mode Observer | [Live Simulator](https://elomarjc.github.io/pmsm-foc-drive-twin/) • [Source](https://github.com/elomarjc/pmsm-foc-drive-twin) |
| **Industrial Pump Hydrodynamics** | Affinity Laws, Thoma cavitation factor, MCSA stator FFT sidebands | [Live Simulator](https://elomarjc.github.io/pump-hydrodynamics-digital-twin/) • [Source](https://github.com/elomarjc/pump-hydrodynamics-digital-twin) |
| **Naval Radar CFAR & Doppler Studio** | Cell-Averaging & Ordered-Statistic CFAR, 3-pulse MTI clutter filter | [Live Simulator](https://elomarjc.github.io/naval-radar-signal-studio/) • [Source](https://github.com/elomarjc/naval-radar-signal-studio) |
| **Cobot Kinematics & Momentum Twin** | 6-DOF UR5e arm, Damped Least-Squares solver, ISO/TS 15066 safety | [Live Simulator](https://elomarjc.github.io/cobot-kinematics-momentum-twin/) • [Source](https://github.com/elomarjc/cobot-kinematics-momentum-twin) |

---

## Selected Academic & Research Engineering

* **[AAUSAT6 CubeSat: Attitude Determination & Control (ADCS)](https://github.com/elomarjc/advanced-control-digital-systems)**: Flight control and attitude stabilization architecture in LEO. Implemented B-dot magnetic detumbling via magnetorquers, momentum wheel LQR pointing, and $H_\infty$ robust disturbance rejection.
* **[Indoor Positioning & AMR Fleet Integration](https://github.com/elomarjc/indoor-positioning-amr-integration)**: 9-thread concurrent sensor fusion engine in Python integrating active Ultra-Wideband (UWB) RF tags, computer vision tracking, and Autonomous Mobile Robots (MiR200) at the AAU 5G Smart Production Lab (1st Place, AAU RoboCup Tournament).
* **[Real-Time Anti-Sway Control of a 2D Gantry Crane](https://github.com/elomarjc/gantry-crane-anti-sway-control)**: B.Sc. thesis project deriving Newtonian dynamic models and implementing discrete cascaded PID controllers with anti-windup on an ATmega2560 micro-controller.
* **[FPGA Digital Design & PLC Equivalence](https://github.com/elomarjc)**: Synchronous FSMs and bus interfaces in VHDL on Intel Cyclone V FPGA (`5CEBA4F23C7N`, Quartus Prime / ModelSim) and hardware schematic logic on Cypress PSoC 5LP UDBs (1:1 equivalent to industrial PLC FBD and Ladder Diagrams) with FreeRTOS.

---

## Technical Core Competencies

| Domain | Key Technologies, Frameworks & Hardware |
| :--- | :--- |
| **Languages & Scripting** | C/C++, Python, Dart, VHDL, MATLAB / Simulink, SQL, C#, JavaScript/TypeScript, LaTeX |
| **Control & Robotics** | State-Space MIMO, Discrete Cascaded PID, LQR / LQG, $H_\infty$ Robust Control, B-dot Detumbling, DLS Kinematics, MiR200 AMRs |
| **Signal Processing & DSP** | Adaptive Filters (LMS, NLMS, RLS), Blind Source Separation (FastICA), STFT, Mel-Spectrograms, EKF / MEKF, CA/OS-CFAR |
| **Embedded & Digital Systems** | FreeRTOS, Intel Cyclone V FPGA, ARM Cortex-M (PSoC 5LP), ATmega2560, PlatformIO, Digilent Analog Discovery 2 |
| **Industrial Networks & Telemetry** | Modbus TCP, MQTT, WebSockets, Ultra-Wideband (UWB), CAN bus, I2C, SPI, UART, RS485, X25519 / AES-256-GCM |
| **Software Architecture** | PyQt6, Flutter, Flame Engine, Dart FFI (C++ native interop), Supabase, WebAssembly, Hive NoSQL, Git, Docker |

---

## Education

* **M.Sc. in Electronic Systems (Civilingeniør, cand.polyt.)** — Aalborg University (2023 – 2025)
  * Specialization in Advanced Signal Processing, Control Systems, Spacecraft ADCS, and Embedded Firmware.
* **B.Sc. in Electronics & IT (Process Control)** — Aalborg University (2020 – 2023)
  * Specialization in Closed-Loop Regulation, Industrial Automation, Digital Hardware (VHDL/FPGA), and Sensor Fusion.

---

## Contact

* **Email**: [elomarjc@gmail.com](mailto:elomarjc@gmail.com)
* **LinkedIn**: [linkedin.com/in/jacob-el-omar](https://www.linkedin.com/in/jacob-el-omar/)
* **GitHub**: [github.com/elomarjc](https://github.com/elomarjc)
* **Location**: Aalborg, Denmark
