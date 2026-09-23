<div align="center">

# Jacob El-Omar

<a href="https://github.com/elomarjc">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=1000&color=38BDF8&center=true&vCenter=true&multiline=true&width=720&height=70&lines=Software+Engineer+%26+Systems+Architect;Full-Stack+Desktop+%26+Cross-Platform+Mobile;Medical+AI%2FML+%26+Real-Time+Signal+Processing;Autonomous+Robotics+%26+Control+Engineering" alt="Jacob El-Omar Typing Headline" />
</a>

<p align="center">
  <a href="https://www.linkedin.com/in/jacob-el-omar/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/elomarjc"><img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://play.google.com/store/apps/details?id=com.elomarstudio.growafish"><img src="https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white" alt="Google Play" /></a>
  <a href="mailto:elomarjc@gmail.com"><img src="https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://maps.google.com/?q=Aalborg,+Denmark"><img src="https://img.shields.io/badge/Location-Aalborg%2C%20Denmark-blue?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location" /></a>
</p>

<!-- Live Animated Signal & Telemetry Monitor -->
<p align="center">
  <img src="assets/system_wave.svg" alt="Real-time System Waveform Telemetry" width="100%" />
</p>

</div>

---

## Interactive Workstation Console

<details open>
<summary><b>▶ Terminal: <code>jacob --status --overview</code></b> <i>(Click to collapse/expand system profile)</i></summary>

```text
┌──[guest@jacob-workstation]─[~]
└──$ jacob --status --overview
[● ONLINE     ] Jacob El-Omar — M.Sc. in Electronic Systems | Aalborg University
[● DISCIPLINES] Full-Stack Software • Mobile Engines • Medical AI/ML & DSP • Robotics
[● CO-DEV     ] OpenMath CAS (Desktop + Web) & Grow A Fish (Google Play) w/ @J2KJonas
[● PERFORMANCE] +34 dB Medical Audio SNR | Sub-1ms Binary Chunks | Zero-Lag C++ Audio FFI
[● ARCHITECTURE] 330+ Dart Modules | 9 Real-Time Digital Twins | FreeRTOS & Cyclone V FPGA
```

</details>

<details>
<summary><b>▶ Terminal: <code>jacob --skills --matrix</code></b> <i>(Click to view full stack & tooling breakdown)</i></summary>

```text
┌──[guest@jacob-workstation]─[~]
└──$ jacob --skills --matrix
LANGUAGES       :: Python, C/C++, Dart, C#/.NET Core, TypeScript/JavaScript, VHDL, SQL, MATLAB
FRAMEWORKS      :: PyQt6, Flutter, Flame Engine, Dart FFI (Native C++), Streamlit, Node.js
AI / ML & DSP   :: Adaptive Filtering (LMS/NLMS/RLS), FastICA, STFT, RapidOCR, LLM APIs / Ollama
ROBOTICS / CTRL :: Mobile Robots (MiR200), State-Space MIMO, Cascaded PID, LQR/LQG, Kalman (EKF/UKF)
EMBEDDED / IOT  :: FreeRTOS, ARM Cortex-M, Intel Cyclone V FPGA, ESP32, ATmega2560, Modbus, MQTT
DATA / CLOUD    :: Supabase Realtime, PostgreSQL, InfluxDB v2, Hive NoSQL, Docker, Git, CI/CD
```

</details>

<details>
<summary><b>▶ Terminal: <code>jacob --achievements --awards</code></b> <i>(Click to view honors and milestones)</i></summary>

```text
┌──[guest@jacob-workstation]─[~]
└──$ jacob --achievements --awards
[★ 1ST PLACE ] AAU RoboCup Autonomous Robotics Tournament Champion
[★ MASTER'S  ] 50 ECTS Thesis R&D with Ai Health Highway: Real-Time Adaptive Noise Cancellation (+34dB SNR)
[★ SHIPPED   ] Grow A Fish: Commercial Mobile Game & Real-Time Multiplayer Ecosystem on Google Play
[★ HARDWARE  ] Full PLC IEC 61131-3 Equivalence on Cypress PSoC 5LP UDBs & Intel Cyclone V FPGA
```

</details>

---

## Flagship Software & Systems Projects

### [OpenMath — Desktop & Web Computer Algebra System (CAS)](https://github.com/J2KJonas/OpenMath)
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Python 3.10+, PyQt6, SymPy, Matplotlib MathText, WebAssembly (Pyodide)*

```
[ Desktop App: macOS | Linux | Windows ] ────── [ Zero-Install Web Demo on GitHub Pages ]
```

* **Application Architecture**: An open-source interactive computer algebra system (CAS) and worksheet document environment designed for engineering mathematics and symbolic computing.
* **Symbolic Engine & UI**: Stateful evaluation engine, multi-level hierarchical section folding (`1. Section`, `1.1 Subsection`) with continuous visual scope brackets, arbitrary-precision arithmetic (2 to 50 digits), interactive 2D function plotter, and visual matrix creation wizard.
* **Embedded Hardware Math**: Native utilities for bitwise logic masking, IEEE-754 single/double precision bit decomposition, and Q-format fixed-point conversion (`to_q`, `from_q`).
* **Deployment**: Packaged for macOS, Linux, and Windows with 1-click launchers, alongside a zero-install client-side browser demo running on GitHub Pages via Pyodide.
* **Launch**: [GitHub Repository](https://github.com/J2KJonas/OpenMath) • [Live Web Demo](https://j2kjonas.github.io/OpenMath/)

---

### [Grow A Fish — Production Mobile Game & Real-Time Ecosystem](https://github.com/elomarjc/grow-a-fish-case-study)
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Published on Google Play • Flutter, Flame Engine, C++ FFI SoLoud, Supabase Realtime, Hive NoSQL, X25519/AES-GCM*

```
[ Google Play Store Release ] ────────────────── [ Technical Whitepaper Case Study ]
```

* **Full-Stack Mobile Architecture**: Commercial cross-platform mobile game and virtual aquarium ecosystem spanning 330+ modular Dart files, featuring live social tank visits, battle pass progression, and 7 arcade minigames.
* **Native Low-Latency Audio (Dart FFI & C++)**: Bypassed native Android platform-channel audio latency by integrating the C++ `SoLoud` audio library directly via Dart FFI with custom LRU sound caching and automated dead-engine recovery.
* **Deterministic Real-Time Netcode**: Eliminated cellular multiplayer jitter and bandwidth overhead by implementing 64-bit seed-synchronized procedural level generation over Supabase WebSockets.
* **Hardware-Backed E2EE Chat**: Client-side end-to-end encrypted messaging using X25519 elliptic-curve Diffie-Hellman (ECDH) key exchange and AES-256-GCM authenticated encryption backed by the Android Keystore and iOS Keychain.
* **Launch**: [Technical Case Study](https://github.com/elomarjc/grow-a-fish-case-study) • [Google Play Store](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)

---

### [Medical Acoustic Signal Enhancement — Master's Thesis R&D](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)
*In collaboration with Ai Health Highway & Prof. Jan Østergaard (AAU) • Python, MATLAB, Adaptive Filters (LMS, NLMS, RLS), FastICA, STFT*

* **Clinical R&D**: Developed real-time signal enhancement algorithms for smart electronic stethoscopes (**AiSteth**) to cancel ambient hospital acoustic noise.
* **Algorithm Performance**: Benchmarked stochastic gradient descent filters (LMS, NLMS, RLS) and Blind Source Separation (FastICA), achieving up to **+34 dB SNR improvements** while preserving low-frequency cardiac valve sounds ($S_1, S_2$) and murmurs at sub-millisecond execution latency.
* **Launch**: [Thesis Repository](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)

---

### [Indoor Positioning & AMR Fleet Integration](https://github.com/elomarjc/indoor-positioning-amr-integration)
*AAU 5G Smart Production Lab • Autonomous Robotics & Sensor Fusion • 1st Place AAU RoboCup Winner*

* **Sensor Fusion Engine**: Engineered a 9-thread concurrent Python processing engine fusing real-time spatial telemetry from active Ultra-Wideband (UWB) RF tags, overhead Computer Vision tracking, and Autonomous Mobile Robots (MiR200).
* **Predictive Collision Avoidance**: Implemented trajectory prediction, time-to-collision calculation, and dynamic velocity throttling to govern robot navigation over REST APIs.
* **Telemetry & Analytics**: Integrated InfluxDB v2 time-series storage and generated empirical Cumulative Distribution Function (CDF) positioning accuracy models.
* **Launch**: [Positioning Repository](https://github.com/elomarjc/indoor-positioning-amr-integration)

---

## Interactive Digital Twins Control Room

A suite of 9 real-time mathematical digital twins, physical modeling testbenches, and interactive browser simulators. Click to launch any simulator directly in your browser:

| Domain | Digital Twin & Architecture | Mathematical Models & Focus | Mission Control |
| :--- | :--- | :--- | :--- |
| **RF / Telecom** | **5G/6G RF Channel Studio** | TDL Fading, Clarke/Jakes Doppler, 256-QAM, EVM | [Launch Simulator](https://elomarjc.github.io/5g-rf-channel-studio/) • [Source](https://github.com/elomarjc/5g-rf-channel-studio) |
| **Aerospace** | **CubeSat AOCS Flight Simulator** | RK4 orbit integration, quaternion kinematics, B-dot | [Launch Simulator](https://elomarjc.github.io/cubesat-aocs-simulator/) • [Source](https://github.com/elomarjc/cubesat-aocs-simulator) |
| **Automation** | **Industrial SCADA & Process Twin** | ISA-101 HMI, IEC 61131-3 Structured Text, Modbus TCP | [Launch Simulator](https://elomarjc.github.io/industrial-scada-digital-twin/) • [Source](https://github.com/elomarjc/industrial-scada-digital-twin) |
| **Audio DSP** | **Hearing Aid Adaptive Beamforming** | Head shadow diffraction, NLMS cancellation, 6-band WDRC | [Launch Simulator](https://elomarjc.github.io/hearing-aid-dsp-studio/) • [Source](https://github.com/elomarjc/hearing-aid-dsp-studio) |
| **Clean Energy** | **Wind Turbine Load Control Twin** | 15 MW offshore turbine, Coleman MBC, Pitch Control | [Launch Simulator](https://elomarjc.github.io/turbine-load-control-twin/) • [Source](https://github.com/elomarjc/turbine-load-control-twin) |
| **Power Drives** | **PMSM Field-Oriented Control (FOC)** | Clarke/Park transforms, Space Vector PWM, SMO observer | [Launch Simulator](https://elomarjc.github.io/pmsm-foc-drive-twin/) • [Source](https://github.com/elomarjc/pmsm-foc-drive-twin) |
| **Hydrodynamics**| **Industrial Pump Hydrodynamics** | Affinity Laws, Thoma cavitation factor, MCSA stator FFT | [Launch Simulator](https://elomarjc.github.io/pump-hydrodynamics-digital-twin/) • [Source](https://github.com/elomarjc/pump-hydrodynamics-digital-twin) |
| **Defense / Radar**| **Naval Radar CFAR & Doppler Studio** | CA/OS-CFAR detection, 3-pulse MTI clutter filter | [Launch Simulator](https://elomarjc.github.io/naval-radar-signal-studio/) • [Source](https://github.com/elomarjc/naval-radar-signal-studio) |
| **Robotics** | **Cobot Kinematics & Momentum Twin** | 6-DOF UR5e arm, Damped Least-Squares solver, ISO/TS 15066 | [Launch Simulator](https://elomarjc.github.io/cobot-kinematics-momentum-twin/) • [Source](https://github.com/elomarjc/cobot-kinematics-momentum-twin) |

---

## AI Tools, Automation & Embedded Systems

* **[AI Media & Document Intelligence Tools](https://github.com/elomarjc)**: Developed Python & Streamlit applications utilizing RapidOCR, Apple Silicon Metal & NVIDIA NVENC hardware-accelerated video rendering via FFmpeg, and local LLM backends (Ollama).
* **[AAUSAT6 CubeSat Flight Control (ADCS)](https://github.com/elomarjc/advanced-control-digital-systems)**: Spacecraft attitude determination and control architecture in LEO utilizing magnetic B-dot detumbling, momentum wheel LQR pointing, and $H_\infty$ robust control.
* **[Gantry Crane Motion & Anti-Sway Control](https://github.com/elomarjc/gantry-crane-anti-sway-control)**: B.Sc. thesis project modeling multi-axis Newtonian crane dynamics and implementing discrete cascaded PID controllers with anti-windup on an ATmega2560 microcontroller.
* **[FPGA Digital Design & PLC Equivalence](https://github.com/elomarjc)**: Synchronous FSMs and bus interfaces in VHDL on Intel Cyclone V FPGA (`5CEBA4F23C7N`), and visual hardware circuit design on Cypress PSoC 5LP UDBs (direct structural equivalence to industrial PLC Function Block Diagrams and Ladder Diagrams) with FreeRTOS.

---

## Technical Skills Matrix

| Domain | Core Technologies & Tooling |
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
