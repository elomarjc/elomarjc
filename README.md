<div align="center">

# Jacob El-Omar
### M.Sc. in Electronic Systems • Aalborg University
**Embedded Systems • Control & Robotics • Digital Signal Processing • High-Performance Software**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jacob-el-omar/)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/elomarjc)
[![Google Play](https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
[![Email](https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elomarjc@gmail.com)
[![Location](https://img.shields.io/badge/Location-Aalborg%2C%20Denmark-blue?style=for-the-badge&logo=google-maps&logoColor=white)](https://maps.google.com/?q=Aalborg,+Denmark)

</div>

---

## About Me

I hold a **Master of Science (M.Sc.) in Electronic Systems** and a **Bachelor of Science (B.Sc.) in Electronics & IT** (specialization in Process Control) from **Aalborg University (AAU)**, Denmark.

My work bridges physical dynamics, control theory, and digital signal processing with modern software engineering. Over 5 years of Problem-Based Learning (PBL) research and commercial engineering, I have designed and delivered end-to-end systems spanning real-time embedded firmware, hardware-accelerated algorithms, industrial automation testbeds, and production applications.

---

## Featured Flagship Projects

### [OpenMath — Desktop & Web Computer Algebra System (CAS)](https://github.com/J2KJonas/OpenMath)
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Python 3.10+, PyQt6, SymPy, Matplotlib MathText, Pyodide*

* **Architecture**: An open-source technical worksheet environment and symbolic algebra engine designed for engineering mathematics and embedded systems.
* **Capabilities**: Exact symbolic computation, multi-level section folding scopes, dynamic 2D plotting, matrix calculation wizard, and high-DPI LaTeX rendering.
* **Hardware Tooling**: Built-in IEEE-754 bit decomposition, bitfield masking, and Q-format fixed-point conversion (`to_q`, `from_q`).
* **Deployment**: Full native desktop application for macOS, Linux, and Windows, plus a zero-install browser demo.
* **Links**: [GitHub Repository](https://github.com/J2KJonas/OpenMath) • [Live Web Demo](https://j2kjonas.github.io/OpenMath/)

---

### [Grow A Fish — Production Mobile Game & Real-Time Ecosystem](https://github.com/elomarjc/grow-a-fish-case-study)
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Shipped on Google Play • Flutter, Flame, C++ FFI SoLoud, Supabase, Hive, X25519/AES-GCM*

* **Architecture**: Production cross-platform mobile game and virtual aquarium ecosystem spanning 330+ modular Dart files.
* **Low-Latency Audio**: Integrated the `SoLoud` C++ audio engine via Dart FFI with custom LRU caching, bypassing native Android platform-channel latency.
* **Deterministic Netcode**: Engineered seed-synchronized procedural generation over WebSockets to eliminate cellular packet jitter.
* **Hardware E2EE**: Client-side end-to-end encrypted messaging using X25519 ECDH key exchange backed by the Android Keystore / iOS Keychain.
* **Links**: [Technical Case Study](https://github.com/elomarjc/grow-a-fish-case-study) • [Google Play Store](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)

---

### [Active Adaptive Noise Cancellation (ANC) — Master's Thesis R&D](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)
*In collaboration with Ai Health Highway • MATLAB, Python, LMS/NLMS/RLS, FastICA, STFT*

* **Research**: Formulated and validated real-time acoustic signal enhancement algorithms for smart stethoscopes (**AiSteth**) under clinical diagnostic constraints.
* **Performance**: Benchmarked adaptive filtering (LMS, NLMS, RLS) and Blind Source Separation (FastICA), achieving up to **+34 dB SNR improvements** while preserving low-frequency cardiac valve sounds ($S_1, S_2$) and murmurs.
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

* **[AAUSAT6 CubeSat ADCS](https://github.com/elomarjc/advanced-control-digital-systems)**: Flight control and attitude stabilization architecture in LEO. Implemented B-dot magnetic detumbling, momentum wheel LQR pointing, and $H_\infty$ disturbance rejection.
* **[Indoor Positioning & AMR Fleet Integration](https://github.com/elomarjc/indoor-positioning-amr-integration)**: 9-thread concurrent sensor fusion engine in Python integrating active Ultra-Wideband (UWB) RF tags, computer vision tracking, and autonomous mobile robots (MiR200) at AAU 5G Smart Production Lab.
* **[2D Gantry Crane Anti-Sway Control](https://github.com/elomarjc/gantry-crane-anti-sway-control)**: Physical modeling and discrete cascaded PID control running on an ATmega2560 micro-controller with anti-windup and velocity estimation.
* **[FPGA Digital Design & PLC Equivalence](https://github.com/elomarjc)**: Synchronous FSMs and bus interfaces in VHDL on Intel Cyclone V FPGA (Quartus Prime / ModelSim) and hardware schematic logic on Cypress PSoC 5LP UDBs.

---

## Technical Skills

| Discipline | Core Competencies |
| :--- | :--- |
| **Languages & Scripting** | C/C++, Python, Dart, VHDL, MATLAB / Simulink, SQL, C#, JavaScript/TypeScript |
| **Control & Dynamics** | State-Space MIMO, Cascaded PID, LQR / LQG, $H_\infty$ Robust Control, Inverse Kinematics, Coleman Transform |
| **Signal Processing & DSP** | Adaptive Filtering (LMS, NLMS, RLS), FastICA, STFT, EKF / MEKF, CA/OS-CFAR, Doppler Filters |
| **Embedded & Digital** | FreeRTOS, Intel Cyclone V FPGA, ARM Cortex-M (PSoC 5LP), ATmega2560, Modbus TCP, MQTT, UWB, CAN bus |
| **Software Engineering** | PyQt6, Flutter, Flame Engine, Dart FFI (C++ interop), Supabase, WebSockets, Git, CI/CD, Docker |

---

## Contact

* **Email**: [elomarjc@gmail.com](mailto:elomarjc@gmail.com)
* **LinkedIn**: [linkedin.com/in/jacob-el-omar](https://www.linkedin.com/in/jacob-el-omar/)
* **GitHub**: [github.com/elomarjc](https://github.com/elomarjc)
* **Location**: Aalborg, North Denmark (Nordjylland)
