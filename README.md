<div align="center">

# 👋 Hi, I'm Jacob El-Omar
### M.Sc. in Electronic Systems • Aalborg University
**Software • Automation • Regulation (Control) • Digital Systems & DSP • Communication**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/jacob-el-omar)
[![Google Play](https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
[![Email](https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elomarjc@gmail.com)

</div>

---

## 👨‍🎓 About Me

I hold an **M.Sc. in Electronic Systems** from **Aalborg University (AAU)**. My engineering and development profile bridges rigorous systems engineering with end-to-end software development across five core disciplines:

* 💻 **Software**: Full-lifecycle application engineering. Production cross-platform mobile apps in Dart/Flutter with native C++ FFI, Python backend services, multi-threaded pipelines, and relational database architecture (SQL, PostgreSQL, Supabase). Creator of [Grow A Fish](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish) on Google Play.
* 🤖 **Automation**: Industrial IoT testbeds, Autonomous Mobile Robot (AMR) fleet tracking, automated testing, and autonomous path planning (1st Place, AAU RoboCup Tournament).
* 🎛️ **Regulation (Control Engineering)**: Mathematical modeling and closed-loop regulation of physical dynamic systems: cascaded discrete PID controllers with anti-windup, state-space feedback, anti-sway crane stabilization, and satellite attitude control.
* 📟 **Digital (DSP & Embedded)**: Digital Signal Processing and embedded hardware: real-time adaptive filtering (LMS, NLMS, RLS, FastICA) and spectral analysis (STFT, Mel-spectrograms) developed during my Master's thesis and AI/ML internship at Ai Health Highway for medical stethoscopes. Firmware on ATmega2560 and FreeRTOS.
* 📡 **Kommunikation (Communication & Networks)**: Networked systems and telemetry protocols: MQTT message brokering, real-time WebSockets, Ultra-Wideband (UWB) RF spatial tracking, and cryptographic communications (X25519 ECDH + AES-256-GCM authenticated encryption).

---

## 🌟 Featured Engineering Showcases

### 1. 🐠 [Grow A Fish — Technical Case Study](https://github.com/elomarjc/grow-a-fish-case-study)
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

### 2. 🫀 [Active Adaptive Noise Cancellation (ANC)](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)
> **Master's Thesis in Electronic Systems • Aalborg University**  
> *Pillars: Digital (DSP) • Software (Python/MATLAB)*  
> *Stack: MATLAB • Python • Adaptive Filters (LMS, NLMS, RLS) • Mel-Spectrograms • STFT • In collaboration with Ai Health Highway*
* **Core Research**: Developed real-time active acoustic noise cancellation algorithms to isolate physiological stethoscope signals (heart sounds $S_1, S_2$) from ambient hospital interference.
* **Mathematical Formulations**: Implemented and benchmarked Least Mean Squares (LMS), Normalized LMS (NLMS), and Recursive Least Squares (RLS) filters.
* **Empirical Validation**: Demonstrated up to **+40 dB SNR improvements** across synthetic and physical acoustic chamber testbeds while preserving critical cardiac murmur signatures.
* **[View Thesis Repository →](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)**

---

### 3. ⚙️ [Real-Time Anti-Sway Control of a 2D Gantry Crane](https://github.com/elomarjc/gantry-crane-anti-sway-control)
> **B.Sc. Electronic Systems Project • Aalborg University**  
> *Pillars: Regulation (Control) • Automation • Digital (Embedded)*  
> *Stack: Embedded C/C++ • Arduino Mega 2560 (ATmega2560) • PlatformIO • Cascaded PID • Discrete Signal Processing*
* **Physical System**: Modeled and controlled an underactuated physical 2D gantry crane with severe pendulum payload sway dynamics.
* **Control Design**: Engineered a cascaded multi-loop discrete-time PID controller: an inner loop actively damping payload swing angle ($	heta$) and an outer loop driving trolley positioning ($x, y$).
* **Firmware Implementation**: Wrote low-level C++ firmware featuring discrete low-pass sensor filtering, Forward Euler velocity estimation, actuator saturation limits, and anti-windup clamping.
* **[View Crane Control Repository →](https://github.com/elomarjc/gantry-crane-anti-sway-control)**

---

### 4. 🤖 [Multi-Sensor Positioning & AMR Fleet Integration](https://github.com/elomarjc/indoor-positioning-amr-integration)
> **AAU 5G Smart Production Lab • Industrial IoT & Autonomous Robotics**  
> *Pillars: Automation • Kommunikation • Software*  
> *Stack: Python • Multi-Threading • Ultra-Wideband (UWB) • Computer Vision (CV) • MQTT • InfluxDB • MATLAB*
* **Sensor Fusion Hub**: Fused real-time spatial telemetry from active UWB RF tags, overhead Computer Vision tracking, and Autonomous Mobile Robots (AMRs).
* **Concurrency & Safety**: Engineered a 9-thread concurrent processing engine in Python with mutex synchronization, proximity breach warnings, and an alarm exemption engine for tagged payloads.
* **Analytics**: Integrated InfluxDB v2 time-series storage and developed empirical Cumulative Distribution Function (CDF) statistical accuracy models.
* **[View Positioning Repository →](https://github.com/elomarjc/indoor-positioning-amr-integration)**

---

### 5. 🛰️ [3-DoF Satellite Simulator CoM Calibration & Dynamics](https://github.com/elomarjc/satellite-simulator-adcs-calibration)
> **M.Sc. Electronic Systems Project • Aalborg University**  
> *Pillars: Regulation (Control) • Digital (Embedded) • Kommunikation*  
> *Stack: C++ • FreeRTOS • MEKF Quaternion Filtering • Rotational Dynamics • Inertial Calibration*
* Analyzed rotational mechanics, Center-of-Mass (CoM) offset estimation, and multi-axis attitude stabilization using a Multiplicative Extended Kalman Filter (MEKF) on FreeRTOS for an experimental 3-DoF air-bearing satellite simulator.
* **[View Satellite Simulator Repository →](https://github.com/elomarjc/satellite-simulator-adcs-calibration)**

---

## 🛠️ Technical Skills & Tooling

| Core Engineering Pillar | Technologies, Frameworks & Methodologies |
| :--- | :--- |
| **💻 Software & Code** | **Python**, **C / C++**, **Dart**, **SQL**, **MATLAB**, **TypeScript / JavaScript**, **C# / .NET**, Flutter, Flame, BLoC/RxDart, REST APIs |
| **🤖 Automation** | Industrial IoT testbeds, Autonomous Mobile Robots (AMR / MiR200), RoboCup navigation, Automated validation pipelines |
| **🎛️ Regulation (Control)** | Cascaded PID control, Anti-windup, State-space regulation, Multiplicative Extended Kalman Filtering (MEKF), Dynamic modeling |
| **📟 Digital (DSP & Embedded)** | Adaptive Filtering (LMS, NLMS, RLS), FastICA, STFT, Mel-Spectrograms, ATmega2560, FreeRTOS, PlatformIO, Altium Designer |
| **📡 Kommunikation** | MQTT message brokers, Realtime WebSockets, Ultra-Wideband (UWB) RF, X25519 ECDH + AES-256-GCM cryptography, SPI, I2C, UART |
| **⚙️ Tools & DevOps** | Git / GitHub Actions (CI/CD), Linux, Docker, InfluxDB, PostgreSQL / Supabase, VS Code, ComfyUI |

---

## 📬 Contact

* **Email**: [elomarjc@gmail.com](mailto:elomarjc@gmail.com)
* **LinkedIn**: [linkedin.com/in/jacob-el-omar](https://linkedin.com/in/jacob-el-omar)
* **GitHub**: [@elomarjc](https://github.com/elomarjc)
* **Google Play**: [Elomar Studio](https://play.google.com/store/apps/developer?id=Elomar+Studio)
