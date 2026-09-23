<div align="center">

# Jacob El-Omar

### Software & Systems Engineer • M.Sc. Graduate from Aalborg University
**Full-Stack & Desktop Software • Mobile & Real-Time Systems • AI/ML & Signal Processing • Robotics & Automation**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jacob-el-omar/)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elomarjc)
[![Google Play](https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
[![Email](https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elomarjc@gmail.com)
[![Location](https://img.shields.io/badge/Location-Aalborg%2C%20Denmark-blue?style=for-the-badge&logo=google-maps&logoColor=white)](https://maps.google.com/?q=Aalborg,+Denmark)

</div>

---

## About Me

I am a software and systems engineer holding an **M.Sc. in Electronic Systems** and a **B.Sc. in Electronics & IT** (specialization in Process Control) from **Aalborg University (AAU)**, Denmark.

I specialize in building complete software products that connect complex mathematical algorithms, real-time infrastructure, and user experiences. Across 5 years of university engineering and independent development, I have:
* Architected and shipped commercial applications spanning **PyQt6 desktop software**, **cross-platform mobile engines on Google Play**, and **cloud backends** (C#/.NET, Node.js, Supabase).
* Engineered real-time **AI/ML and DSP algorithms** for medical-grade audio diagnostics, achieving up to +34 dB SNR improvements.
* Built autonomous **robotics, multi-sensor tracking, and industrial automation** pipelines in the AAU 5G Smart Production Lab (1st Place, AAU RoboCup Tournament).
* Implemented deterministic low-level systems using **C/C++, FreeRTOS, and VHDL on FPGAs**.

---

## Flagship Software & Systems Projects

### [OpenMath — Desktop & Web Computer Algebra System (CAS)](https://github.com/J2KJonas/OpenMath)
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Python 3.10+, PyQt6, SymPy, Matplotlib MathText, WebAssembly (Pyodide)*

* **Application Architecture**: An open-source interactive computer algebra system (CAS) and worksheet document environment designed for engineering mathematics and symbolic computing.
* **Symbolic Engine & UI**: Stateful evaluation engine, multi-level hierarchical section folding (`1. Section`, `1.1 Subsection`) with continuous visual scope brackets, arbitrary-precision arithmetic (2 to 50 digits), interactive 2D function plotter, and visual matrix creation wizard.
* **Embedded Hardware Math**: Native utilities for bitwise logic masking, IEEE-754 single/double precision bit decomposition, and Q-format fixed-point conversion (`to_q`, `from_q`).
* **Deployment**: Packaged for macOS, Linux, and Windows with 1-click launchers, alongside a zero-install client-side browser demo running on GitHub Pages via Pyodide.
* **Links**: [GitHub Repository](https://github.com/J2KJonas/OpenMath) • [Live Web Demo](https://j2kjonas.github.io/OpenMath/)

---

### [Grow A Fish — Production Mobile Game & Real-Time Ecosystem](https://github.com/elomarjc/grow-a-fish-case-study)
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Published on Google Play • Flutter, Flame Engine, C++ FFI SoLoud, Supabase Realtime, Hive NoSQL, X25519/AES-GCM*

* **Full-Stack Mobile Architecture**: Commercial cross-platform mobile game and virtual aquarium ecosystem spanning 330+ modular Dart files, featuring live social tank visits, battle pass progression, and 7 arcade minigames.
* **Native Low-Latency Audio (Dart FFI & C++)**: Bypassed native Android platform-channel audio latency by integrating the C++ `SoLoud` audio library directly via Dart FFI with custom LRU sound caching and automated dead-engine recovery.
* **Deterministic Real-Time Netcode**: Eliminated cellular multiplayer jitter and bandwidth overhead by implementing 64-bit seed-synchronized procedural level generation over Supabase WebSockets.
* **Hardware-Backed E2EE Chat**: Client-side end-to-end encrypted messaging using X25519 elliptic-curve Diffie-Hellman (ECDH) key exchange and AES-256-GCM authenticated encryption backed by the Android Keystore and iOS Keychain.
* **Links**: [Technical Case Study](https://github.com/elomarjc/grow-a-fish-case-study) • [Google Play Store](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)

---

### [Medical Acoustic Signal Enhancement — Master's Thesis R&D](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)
*In collaboration with Ai Health Highway & Prof. Jan Østergaard (AAU) • Python, MATLAB, Adaptive Filters (LMS, NLMS, RLS), FastICA, STFT*

* **Clinical R&D**: Developed real-time signal enhancement algorithms for smart electronic stethoscopes (**AiSteth**) to cancel ambient hospital acoustic noise.
* **Algorithm Performance**: Benchmarked stochastic gradient descent filters (LMS, NLMS, RLS) and Blind Source Separation (FastICA), achieving up to **+34 dB SNR improvements** while preserving low-frequency cardiac valve sounds ($S_1, S_2$) and murmurs at sub-millisecond execution latency.
* **Links**: [Thesis Repository](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)

---

### [Indoor Positioning & AMR Fleet Integration](https://github.com/elomarjc/indoor-positioning-amr-integration)
*AAU 5G Smart Production Lab • Autonomous Robotics & Sensor Fusion • 1st Place AAU RoboCup Winner*

* **Sensor Fusion Engine**: Engineered a 9-thread concurrent Python processing engine fusing real-time spatial telemetry from active Ultra-Wideband (UWB) RF tags, overhead Computer Vision tracking, and Autonomous Mobile Robots (MiR200).
* **Predictive Collision Avoidance**: Implemented trajectory prediction, time-to-collision calculation, and dynamic velocity throttling to govern robot navigation over REST APIs.
* **Telemetry & Analytics**: Integrated InfluxDB v2 time-series storage and generated empirical Cumulative Distribution Function (CDF) positioning accuracy models.
* **Links**: [Positioning Repository](https://github.com/elomarjc/indoor-positioning-amr-integration)

---

## Interactive Digital Twins & Simulators

A suite of 9 real-time mathematical digital twins, physical modeling testbenches, and interactive browser simulators:

| Digital Twin | Domain | Focus Area & Key Algorithms | Access |
| :--- | :--- | :--- | :--- |
| **5G/6G RF Channel Studio** | Telecommunications | TDL Fading, Clarke/Jakes Doppler, 256-QAM, 3GPP EVM sweeps | [Live Simulator](https://elomarjc.github.io/5g-rf-channel-studio/) • [Source](https://github.com/elomarjc/5g-rf-channel-studio) |
| **CubeSat AOCS Flight Simulator** | Aerospace & Control | RK4 orbit integration, quaternion kinematics, B-dot detumbling | [Live Simulator](https://elomarjc.github.io/cubesat-aocs-simulator/) • [Source](https://github.com/elomarjc/cubesat-aocs-simulator) |
| **Industrial SCADA & Process Twin** | Industrial Automation | ISA-101 HMI, IEC 61131-3 Structured Text runtime, Modbus TCP | [Live Simulator](https://elomarjc.github.io/industrial-scada-digital-twin/) • [Source](https://github.com/elomarjc/industrial-scada-digital-twin) |
| **Hearing Aid Adaptive Beamforming** | Audio DSP | Head shadow diffraction, NLMS feedback cancellation, 6-band WDRC | [Live Simulator](https://elomarjc.github.io/hearing-aid-dsp-studio/) • [Source](https://github.com/elomarjc/hearing-aid-dsp-studio) |
| **Wind Turbine Load Control Twin** | Renewable Energy | 15 MW offshore model, Coleman MBC transform, Individual Pitch Control | [Live Simulator](https://elomarjc.github.io/turbine-load-control-twin/) • [Source](https://github.com/elomarjc/turbine-load-control-twin) |
| **PMSM Field-Oriented Control (FOC)** | Power & Drive Systems | Clarke/Park transforms, Space Vector PWM, Sliding Mode Observer | [Live Simulator](https://elomarjc.github.io/pmsm-foc-drive-twin/) • [Source](https://github.com/elomarjc/pmsm-foc-drive-twin) |
| **Industrial Pump Hydrodynamics** | Fluid Dynamics | Affinity Laws, Thoma cavitation factor, MCSA stator FFT sidebands | [Live Simulator](https://elomarjc.github.io/pump-hydrodynamics-digital-twin/) • [Source](https://github.com/elomarjc/pump-hydrodynamics-digital-twin) |
| **Naval Radar CFAR & Doppler Studio** | Defense & Radar | Cell-Averaging & Ordered-Statistic CFAR, 3-pulse MTI clutter filter | [Live Simulator](https://elomarjc.github.io/naval-radar-signal-studio/) • [Source](https://github.com/elomarjc/naval-radar-signal-studio) |
| **Cobot Kinematics & Momentum Twin** | Robotics & Safety | 6-DOF UR5e arm, Damped Least-Squares solver, ISO/TS 15066 safety | [Live Simulator](https://elomarjc.github.io/cobot-kinematics-momentum-twin/) • [Source](https://github.com/elomarjc/cobot-kinematics-momentum-twin) |

---

## AI Tools, Automation & Embedded Systems

* **[AI Media & Document Intelligence Tools](https://github.com/elomarjc)**: Developed Python & Streamlit applications utilizing RapidOCR, Apple Silicon Metal & NVIDIA NVENC hardware-accelerated video rendering via FFmpeg, and local LLM backends (Ollama).
* **[AAUSAT6 CubeSat Flight Control (ADCS)](https://github.com/elomarjc/advanced-control-digital-systems)**: Spacecraft attitude determination and control architecture in LEO utilizing magnetic B-dot detumbling, momentum wheel LQR pointing, and $H_\infty$ robust control.
* **[Gantry Crane Motion & Anti-Sway Control](https://github.com/elomarjc/gantry-crane-anti-sway-control)**: B.Sc. thesis project modeling multi-axis Newtonian crane dynamics and implementing discrete cascaded PID controllers with anti-windup on an ATmega2560 microcontroller.
* **[FPGA Digital Design & PLC Equivalence](https://github.com/elomarjc)**: Synchronous FSMs and bus interfaces in VHDL on Intel Cyclone V FPGA (`5CEBA4F23C7N`), and visual hardware circuit design on Cypress PSoC 5LP UDBs (direct structural equivalence to industrial PLC Function Block Diagrams and Ladder Diagrams) with FreeRTOS.

---

## Technical Skills

| Category | Technologies, Frameworks & Tooling |
| :--- | :--- |
| **Software Development** | Python (PyQt6, Streamlit, SymPy), Dart / Flutter, C# / .NET Core, TypeScript / JavaScript, Node.js, C/C++ |
| **AI, ML & Signal Processing** | Adaptive Filtering (LMS, NLMS, RLS), FastICA, STFT, Mel-Spectrograms, Computer Vision, RapidOCR, LLM APIs / Ollama |
| **Robotics & Control Systems** | Mobile Industrial Robots (MiR200), State-Space MIMO, Cascaded PID, LQR / LQG, $H_\infty$ Control, Kalman Filters (EKF/UKF/MEKF) |
| **Embedded & Real-Time** | FreeRTOS, ARM Cortex-M (PSoC 5LP), ATmega2560, Intel Cyclone V FPGA (VHDL), ESP32, PlatformIO |
| **Data, Cloud & Protocols** | Supabase, PostgreSQL, InfluxDB v2, Hive NoSQL, Modbus TCP, MQTT, WebSockets, CAN bus, UWB, Docker, Git, CI/CD |

---

## Education

* **M.Sc. in Engineering — Electronic Systems (Civilingeniør, cand.polyt.)**  
  Aalborg University (2023 – 2025) • 120 ECTS  
  *Focus on Advanced Signal Processing, Control Engineering, Spacecraft Dynamics, and Real-Time Systems.*

* **B.Sc. in Engineering — Electronics & IT (Process Control Specialization)**  
  Aalborg University (2020 – 2023) • 180 ECTS  
  *Focus on Closed-Loop Control, Industrial Automation, Digital Hardware (VHDL/FPGA), and Embedded Software.*

---

## Contact

* **Email**: [elomarjc@gmail.com](mailto:elomarjc@gmail.com)
* **LinkedIn**: [linkedin.com/in/jacob-el-omar](https://www.linkedin.com/in/jacob-el-omar/)
* **GitHub**: [github.com/elomarjc](https://github.com/elomarjc)
* **Location**: Aalborg, Denmark
