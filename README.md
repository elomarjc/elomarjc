# 👋 Hi, I'm Jacob El-Omar

<div align="center">

# Jacob El-Omar
### Electronic Systems Engineer • Embedded & Systems Software Developer
**M.Sc. in Electronic Systems • Aalborg University (AAU), Denmark**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Google Play](https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
[![Email](https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:elomarjc@gmail.com)

</div>

---

## 👨‍🎓 About Me

I am an **Electronic Systems Engineering graduate** from **Aalborg University (AAU)** with a dual passion for:
1. **Mathematical Systems Engineering**: Digital Signal Processing (DSP), discrete-time feedback control theory, embedded firmware, and multi-sensor robotics integration.
2. **High-Performance Software & Game Architecture**: Architecting cross-platform consumer applications, real-time multiplayer networking, native C++ interop (FFI), and applied hardware-backed cryptography.

I believe the strongest engineers are those who understand both the low-level physical dynamics (signals, feedback loops, hardware latency, registers) and high-level software abstractions (clean architecture, event-driven state machines, secure cloud synchronization).

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

### 2. 🫀 [Active Adaptive Noise Cancellation (ANC)](https://github.com/elomarjc/new_adaptivefilter)
> **Master's Thesis in Electronic Systems (Advanced Signal Processing) • Aalborg University**  
> *Stack: MATLAB • Adaptive Filters (LMS, NLMS, RLS) • Mel-Spectrograms • STFT • In collaboration with Ai Highway Inc*
* **Core Research**: Developed real-time active acoustic noise cancellation algorithms to isolate physiological stethoscope signals (heart sounds $S_1, S_2$) from ambient hospital interference.
* **Mathematical Formulations**: Implemented and benchmarked Least Mean Squares (LMS), Normalized LMS (NLMS), and Recursive Least Squares (RLS) filters.
* **Empirical Validation**: Demonstrated up to **+40 dB SNR improvements** across synthetic and physical acoustic chamber testbeds while preserving critical cardiac murmur signatures.
* **[View Thesis Repository →](https://github.com/elomarjc/new_adaptivefilter)**

---

### 3. ⚙️ [Real-Time Anti-Sway Control of a 2D Gantry Crane](https://github.com/elomarjc/P6-Crane-612)
> **B.Sc. Electronic Systems Project • Embedded Control Engineering • Aalborg University**  
> *Stack: Embedded C/C++ • Arduino Mega 2560 (ATmega2560) • PlatformIO • Cascaded PID • Discrete Signal Processing*
* **Physical System**: Modeled and controlled an underactuated physical 2D gantry crane with severe pendulum payload sway dynamics.
* **Control Design**: Engineered a cascaded multi-loop discrete-time PID controller: an inner loop actively damping payload swing angle ($	heta$) and an outer loop driving trolley positioning ($x, y$).
* **Firmware Implementation**: Wrote low-level C++ firmware featuring discrete low-pass sensor filtering, Forward Euler velocity estimation, actuator saturation limits, and anti-windup clamping.
* **[View Crane Control Repository →](https://github.com/elomarjc/P6-Crane-612)**

---

### 4. 🤖 [Multi-Sensor Positioning & AMR Fleet Integration](https://github.com/elomarjc/positioning-integration)
> **AAU 5G Smart Production Lab • Industrial IoT & Autonomous Robotics**  
> *Stack: Python • Multi-Threading • Ultra-Wideband (UWB) • Computer Vision (CV) • MQTT • InfluxDB • MATLAB*
* **Sensor Fusion Hub**: Fused real-time spatial telemetry from active UWB RF tags, overhead Computer Vision tracking, and Autonomous Mobile Robots (AMRs).
* **Concurrency & Safety**: Engineered a 9-thread concurrent processing engine with mutex synchronization, proximity breach warnings, and an alarm exemption engine for tagged payloads.
* **Analytics**: Integrated InfluxDB v2 time-series storage and developed empirical Cumulative Distribution Function (CDF) statistical accuracy models.
* **[View Positioning Repository →](https://github.com/elomarjc/positioning-integration)**

---

### 5. 🛰️ [3-DoF Satellite Simulator CoM Calibration & Dynamics](https://github.com/elomarjc/P7-CoM)
> **M.Sc. Electronic Systems Project • Control of Manipulators • Aalborg University**  
> *Stack: C++ • Rotational Dynamics • Inertial Calibration • Euler Angles*
* Analyzed rotational mechanics, Center-of-Mass (CoM) offset estimation, and multi-axis attitude stabilization for an experimental 3-DoF air-bearing satellite simulator.
* **[View Satellite Simulator Repository →](https://github.com/elomarjc/P7-CoM)**

---

## 🛠️ Technical Competencies

| Domain | Technologies & Methodologies |
| :--- | :--- |
| **Programming Languages** | C, C++, Dart, Python, MATLAB, TypeScript, SQL, TeX |
| **Control & Embedded** | Discrete-time PID, State-Space Control, Kalman Filtering, ATmega2560, PlatformIO, ADC/PWM Drivers |
| **Digital Signal Processing** | Adaptive Filtering (LMS, NLMS, RLS), STFT, Mel-Spectrograms, FIR/IIR Filter Design, SNR Analysis |
| **Mobile & Game Engineering** | Flutter, Flame Engine, Bonfire RPG, Dart FFI (Native C++ interop), State Management (BLoC/RxDart) |
| **Networking & Security** | Deterministic Seed Networking, Supabase Realtime (WebSockets), MQTT, X25519 ECDH, AES-256-GCM |
| **Data & Storage** | InfluxDB (Time-series), PostgreSQL / Supabase, Hive (Binary NoSQL), Hardware Keystore / Keychain |
| **Tools & Environments** | Git, Linux, Docker, PlatformIO, VS Code, ComfyUI Generative Pipelines |

---

## 📬 Get In Touch

* **Email**: [elomarjc@gmail.com](mailto:elomarjc@gmail.com)
* **GitHub**: [@elomarjc](https://github.com/elomarjc)
* **Google Play Store**: [Grow A Fish](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)
