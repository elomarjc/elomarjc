# 👋 Hi, I'm Jacob El-Omar

<div align="center">

# Jacob El-Omar
### M.Sc. in Electronic Systems • Aalborg University
**Software Engineer & Technical Problem Solver**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jacob-el-omar)
[![Google Play](https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
[![Email](https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elomarjc@gmail.com)

</div>

---

## 👨‍🎓 About Me

I hold an **M.Sc. in Electronic Systems** from **Aalborg University (AAU)**, with a technical focus spanning software engineering, digital signal processing, and systems design.

My coding and engineering background combines:
* **Software & Application Development**: Python (APIs, algorithmic data processing, multi-threading, automation), Dart/Flutter (full-scale cross-platform architecture, game loops, native C++ FFI), and SQL databases (PostgreSQL, Supabase). Creator and lead developer of [Grow A Fish](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish) on Google Play.
* **Signal Processing & Machine Learning**: Real-time adaptive filtering (LMS, NLMS, RLS, FastICA) and spectral analysis developed during my Master's thesis and AI/ML engineering internship at Ai Health Highway for medical-grade acoustic stethoscopes.
* **Control & Embedded Systems**: Low-level C/C++ firmware, discrete-time feedback control loops (PID, state-space), FreeRTOS, and multi-sensor robotics telemetry (UWB + Computer Vision).

---

## 🌟 Featured Engineering Showcases

### 1. 🐠 [Grow A Fish — Technical Case Study](https://github.com/elomarjc/grow-a-fish-case-study)
> **Published Commercial Mobile Game & Real-Time Multiplayer Ecosystem**  
> *Stack: Flutter • Flame Engine • Bonfire RPG • Dart FFI & C++ SoLoud • Supabase Realtime • Hive NoSQL • X25519/AES-GCM*
* **Architecture**: Engineered an end-to-end mobile game (330+ modules) published on Google Play.
* **Deterministic Networking**: Formulated deterministic seed-based procedural level generation to eliminate mobile multiplayer jitter and bandwidth overhead.
* **Low-Latency Native Audio**: Integrated the `SoLoud` C++ audio engine via Dart FFI with custom LRU caching and auto-recovery to eradicate Android audio latency.
* **Hardware-Backed Cryptography**: Implemented client-side End-to-End Encrypted (E2EE) chat using X25519 ECDH key exchange and AES-256-GCM.
* **In-Game Tooling**: Built a custom grid-based level design studio with high-speed binary Hive serialization.
* **[View Full Case Study →](https://github.com/elomarjc/grow-a-fish-case-study)** • **[Google Play Store →](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)**

---

### 2. 🫀 [Active Adaptive Noise Cancellation (ANC)](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)
> **Master's Thesis in Electronic Systems (Advanced Signal Processing) • Aalborg University**  
> *Stack: MATLAB • Python • Adaptive Filters (LMS, NLMS, RLS) • Mel-Spectrograms • STFT • In collaboration with Ai Health Highway*
* **Core Research**: Developed real-time active acoustic noise cancellation algorithms to isolate physiological stethoscope signals (heart sounds $S_1, S_2$) from ambient hospital interference.
* **Mathematical Formulations**: Implemented and benchmarked Least Mean Squares (LMS), Normalized LMS (NLMS), and Recursive Least Squares (RLS) filters.
* **Empirical Validation**: Demonstrated up to **+40 dB SNR improvements** across synthetic and physical acoustic chamber testbeds while preserving critical cardiac murmur signatures.
* **[View Thesis Repository →](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)**

---

### 3. ⚙️ [Real-Time Anti-Sway Control of a 2D Gantry Crane](https://github.com/elomarjc/gantry-crane-anti-sway-control)
> **B.Sc. Electronic Systems Project • Embedded Control Engineering • Aalborg University**  
> *Stack: Embedded C/C++ • Arduino Mega 2560 (ATmega2560) • PlatformIO • Cascaded PID • Discrete Signal Processing*
* **Physical System**: Modeled and controlled an underactuated physical 2D gantry crane with severe pendulum payload sway dynamics.
* **Control Design**: Engineered a cascaded multi-loop discrete-time PID controller: an inner loop actively damping payload swing angle ($	heta$) and an outer loop driving trolley positioning ($x, y$).
* **Firmware Implementation**: Wrote low-level C++ firmware featuring discrete low-pass sensor filtering, Forward Euler velocity estimation, actuator saturation limits, and anti-windup clamping.
* **[View Crane Control Repository →](https://github.com/elomarjc/gantry-crane-anti-sway-control)**

---

### 4. 🤖 [Multi-Sensor Positioning & AMR Fleet Integration](https://github.com/elomarjc/indoor-positioning-amr-integration)
> **AAU 5G Smart Production Lab • Industrial IoT & Autonomous Robotics**  
> *Stack: Python • Multi-Threading • Ultra-Wideband (UWB) • Computer Vision (CV) • MQTT • InfluxDB • MATLAB*
* **Sensor Fusion Hub**: Fused real-time spatial telemetry from active UWB RF tags, overhead Computer Vision tracking, and Autonomous Mobile Robots (AMRs).
* **Concurrency & Safety**: Engineered a 9-thread concurrent processing engine in Python with mutex synchronization, proximity breach warnings, and an alarm exemption engine for tagged payloads.
* **Analytics**: Integrated InfluxDB v2 time-series storage and developed empirical Cumulative Distribution Function (CDF) statistical accuracy models.
* **[View Positioning Repository →](https://github.com/elomarjc/indoor-positioning-amr-integration)**

---

### 5. 🛰️ [3-DoF Satellite Simulator CoM Calibration & Dynamics](https://github.com/elomarjc/satellite-simulator-adcs-calibration)
> **M.Sc. Electronic Systems Project • Control of Manipulators • Aalborg University**  
> *Stack: C++ • FreeRTOS • MEKF Quaternion Filtering • Rotational Dynamics • Inertial Calibration*
* Analyzed rotational mechanics, Center-of-Mass (CoM) offset estimation, and multi-axis attitude stabilization using a Multiplicative Extended Kalman Filter (MEKF) on FreeRTOS for an experimental 3-DoF air-bearing satellite simulator.
* **[View Satellite Simulator Repository →](https://github.com/elomarjc/satellite-simulator-adcs-calibration)**

---

## 🛠️ Technical Skills & Tooling

| Category | Competencies |
| :--- | :--- |
| **Programming Languages** | **Python**, **C / C++**, **Dart**, **SQL**, **MATLAB**, **TypeScript / JavaScript**, **C# / .NET** |
| **Software & Application Engineering** | Flutter, Flame Engine, Bonfire RPG, Dart FFI (C++ native interop), REST APIs, State Management (BLoC/RxDart) |
| **Databases & Cloud** | PostgreSQL, Supabase (Realtime WebSockets, Auth, RLS), InfluxDB (Time-series), Hive (Binary NoSQL), SQLite |
| **Signal Processing & ML** | Adaptive Filtering (LMS, NLMS, RLS), FastICA, STFT, Mel-Spectrograms, Bio-Acoustic Signal Validation, Noise Suppression |
| **Control & Embedded Systems** | Cascaded PID, State-Space Control, MEKF / Kalman Filtering, FreeRTOS, Arduino / PlatformIO, Sensor Interfacing (I2C, SPI, UART, MQTT) |
| **DevOps & Developer Tools** | Git / GitHub Actions (CI/CD), Linux, Docker, VS Code, Altium Designer, ComfyUI |

---

## 📬 Contact

* **Email**: [elomarjc@gmail.com](mailto:elomarjc@gmail.com)
* **LinkedIn**: [linkedin.com/in/jacob-el-omar](https://linkedin.com/in/jacob-el-omar)
* **GitHub**: [@elomarjc](https://github.com/elomarjc)
* **Google Play**: [Elomar Studio](https://play.google.com/store/apps/developer?id=Elomar+Studio)
