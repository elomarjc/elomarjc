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
> **Master's Thesis in Electronic Systems (50 ECTS) • Aalborg University**  
> *Pillars: Digital (DSP) • Software (Python/MATLAB)*  
> *Stack: MATLAB • Python • Adaptive Filters (LMS, NLMS, RLS) • FastICA • Mel-Spectrograms • STFT • In collaboration with Ai Health Highway*
* **Core Research**: Developed real-time active acoustic noise cancellation algorithms to isolate physiological stethoscope signals from ambient hospital interference.
* **Mathematical Formulations**: Implemented and benchmarked Least Mean Squares (LMS), Normalized LMS (NLMS), Recursive Least Squares (RLS), and FastICA source separation.
* **Empirical Validation**: Demonstrated up to **+34 dB SNR improvements** across synthetic and physical acoustic chamber testbeds while preserving critical cardiac murmur frequencies.
* **[View Thesis Repository →](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)**

---

### 3. 🛰️ [AAUSAT6 CubeSat: Attitude Determination & Control (ADCS)](https://github.com/elomarjc/advanced-control-digital-systems)
> **Master's Project (Semester 8) • Systems of Systems & Space Engineering • Aalborg University**  
> *Pillars: Regulation (Control) • Digital • Kommunikation*  
> *Stack: MATLAB • Orbital Dynamics • B-dot Detumbling • LQR Target Tracking • Momentum Wheels • $H_\infty$ Robust Control*
* **Satellite Mission**: Designed the flight control and stabilization architecture for the **AAUSAT6 CubeSat** in Low Earth Orbit (LEO).
* **Control Modes**: Implemented magnetic B-dot detumbling using magnetorquers to eliminate launch tip-off spin, LQR state-feedback with integral action for Nadir/Target pointing via momentum wheels, and robust $H_\infty$ controllers to reject aerodynamic and solar radiation disturbance torques under uncertainty.
* **[View AAUSAT6 Repository →](https://github.com/elomarjc/advanced-control-digital-systems)**

---

### 4. ⚙️ [Real-Time Anti-Sway Control of a 2D Gantry Crane](https://github.com/elomarjc/gantry-crane-anti-sway-control)
> **Bachelor's Project (Semester 6) • Electronic Systems & Control Engineering • Aalborg University**  
> *Pillars: Regulation (Control) • Automation • Digital (Embedded)*  
> *Stack: Embedded C/C++ • Arduino Mega 2560 (ATmega2560) • PlatformIO • Cascaded PID • Discrete Signal Processing*
* **Physical System**: Derived Newtonian dynamic models for the hoisting block, trolley, and pendulum. Linearized models for frequency-domain transfer functions.
* **Control Design**: Designed 3 discrete PD controllers (crane head Y-pos, trolley X-pos, head sway angle $\theta$), matched via Sensetools parameter tuning to physical step-response benchmarks.
* **Firmware Implementation**: Wrote low-level C++ firmware with discrete low-pass filtering, Forward Euler velocity estimation, actuator current saturation limits, and anti-windup.
* **[View Crane Control Repository →](https://github.com/elomarjc/gantry-crane-anti-sway-control)**

---

### 5. 🤖 [Multi-Sensor Positioning & AMR Fleet Integration](https://github.com/elomarjc/indoor-positioning-amr-integration)
> **AAU 5G Smart Production Lab • Industrial IoT & Autonomous Robotics**  
> *Pillars: Automation • Kommunikation • Software*  
> *Stack: Python • Multi-Threading • Ultra-Wideband (UWB) • Computer Vision (CV) • MQTT • InfluxDB • MATLAB*
* **Sensor Fusion Hub**: Fused real-time spatial telemetry from active UWB RF tags, overhead Computer Vision tracking, and Autonomous Mobile Robots (AMRs / MiR200).
* **Concurrency & Safety**: Engineered a 9-thread concurrent processing engine in Python with mutex synchronization, proximity breach warnings, and an alarm exemption engine for tagged payloads.
* **Analytics**: Integrated InfluxDB v2 time-series storage and developed empirical Cumulative Distribution Function (CDF) statistical accuracy models.
* **[View Positioning Repository →](https://github.com/elomarjc/indoor-positioning-amr-integration)**

---

### 6. 🛰️ [3-DoF Satellite Simulator CoM Calibration & Dynamics](https://github.com/elomarjc/satellite-simulator-adcs-calibration)
> **Master's Project (Semester 7) • Control of Manipulators • Aalborg University**  
> *Pillars: Regulation (Control) • Digital (Embedded) • Kommunikation*  
> *Stack: C++ • FreeRTOS • MEKF Quaternion Filtering • Rotational Dynamics • Inertial Calibration*
* Created dynamic center-of-mass estimation algorithms using spacecraft kinematics and Kalman filtering to eliminate gravitational disturbance torques on a 3-DoF spherical air-bearing satellite simulator.
* **[View Satellite Simulator Repository →](https://github.com/elomarjc/satellite-simulator-adcs-calibration)**

---

## 🎓 Academic Trajectory & Comprehensive Coursework

### **Master of Science (M.Sc.) in Electronic Systems** — Aalborg University (120 ECTS)

| Semester / Project | Focus & Methods Applied |
| :--- | :--- |
| **Sem 9–10: Master's Thesis** *(50 ECTS)*<br/>*Adaptive Noise Cancellation for Electronic Stethoscopes* | Real-time adaptive filtering (**LMS, NLMS, RLS**) and Independent Component Analysis (**FastICA**) for physiological signal enhancement. Evaluated SNR improvements up to 34 dB on smart medical stethoscopes in collaboration with **Ai Health Highway**. |
| **Sem 8: Systems of Systems** *(15 ECTS)*<br/>*ADCS for AAUSAT6 CubeSat* | 2U CubeSat orbital dynamics modeling, magnetic **B-dot detumbling**, **LQR state feedback** with integral action for Nadir/Target tracking, and **$H_\infty$ robust stability** analysis under space disturbance torques. |
| **Sem 7: Machine Intelligence** *(10 ECTS)*<br/>*CoM Calibration of 3-DoF Satellite Simulator* | Spacecraft kinematics, **Multiplicative Extended Kalman Filtering (MEKF)** for attitude determination, dynamic Center of Mass offset identification, and motor-driven trim actuation. |

<details>
<summary><b>📚 Master's Level Graduate Course Catalog (Click to expand)</b></summary>

| Course | Key Theoretical Concepts & Practical Methods |
| :--- | :--- |
| **Avanceret Signalbehandling (Advanced Signal Processing)** | Parametric spectral analysis (LPC, Lattice filters), adaptive signal processing (LMS, NLMS, RLS), state-space signal processing, Kalman filtering, multidimensional & statistical signal processing. |
| **Avanceret Regulering (Advanced Control)** | MIMO state-space systems, controllability, stabilizability, observability, Kalman observer synthesis, robust MIMO control, $H_\infty$ optimization, coupled large-scale control loops. |
| **Sensorer og Systemer (Sensors & Systems)** | HW/SW sensor systems design, physiological/industrial measurement, sensor data fusion, Extended Kalman Filters (EKF), Unscented Kalman Filters (UKF), Particle filters. |
| **Netværk og Systemer (Networks & Systems)** | Distributed network architectures, fault-tolerant topologies, networking protocols, edge/cloud platforms, performance modeling, and AI-enabled networked systems. |
| **Machine Learning** | Supervised learning (Logistic Regression, Support Vector Machines, Decision Trees), unsupervised learning (K-Means, Expectation-Maximization), Neural Networks, Hidden Markov Models (HMM), Bayesian decision theory, reinforcement learning. |
| **Stokastiske Systemer (Stochastic Systems)** | Wide-Sense Stationary (WSS) processes, Markov chains, Poisson and Gaussian processes, discrete-time stochastic dynamical systems, ARIMAX time-series modeling. |
| **Modellering af Fysiske Systemer (Modelling of Physical Systems)** | Rigid-body kinematics and dynamics, analytical mechanics (Lagrangian/Hamiltonian), static and dynamic friction, electromechanical energy conversion, thermodynamic balances. |
| **Kommunikationssystemer (Communication Systems)** | Wireless channel characterization, multi-user resource allocation in time/frequency/space, link- and system-level performance simulation, information theory fundamentals. |
| **Fremskridt inden for Elektroniske Systemer** | State-of-the-art research analysis across automation, control, machine learning, and next-generation wireless communications. |

</details>

---

### **Bachelor of Science (B.Sc.) in Electronic Engineering & IT** — Aalborg University (180 ECTS)
*Specialization: Control Engineering (Proceskontrol)*

| Semester / Project | Focus & Methods Applied |
| :--- | :--- |
| **Sem 6: Bachelor's Project** *(20 ECTS)*<br/>*Autonomous Control System for Model Gantry Crane* | Newtonian mechanics, model linearization, transfer functions, Sensetools parameter tuning, and **3 discrete PD controllers** with anti-windup for trolley positioning and payload anti-sway. |
| **Sem 5: Digital & Analog Systems** *(15 ECTS)*<br/>*Predictive Collision-Avoidance for Mobile Robots* | UWB localization, Kalman filtering vs. linear regression for trajectory prediction, Monte Carlo simulations, and speed adaptation trials on **MiR200** industrial robots in the AAU Smart Production Lab. |
| **Sem 4: Digital Systems Design** *(15 ECTS)*<br/>*Automatic Fall Protection for Smartphones* | Embedded C on **Cypress Semiconductor PSoC 5LP (CY8CKIT-059)**, IMU (GY-91: accelerometer + gyroscope) over I2C, **Complementary Filter** with quaternions/Euler angles, 43 ms fall response detection. |
| **Sem 3: Analog Circuits & Systems** *(15 ECTS)*<br/>*Hi-Fi Audio Amplifier* | Transistor amplifier stage design, feedback stability, component tolerance impact, and total harmonic distortion (THD $< 0.7\%$). |
| **Sem 2: Dynamic Systems** *(15 ECTS)*<br/>*Indoor Climate in Public Schools* | Sensor IoT instrumentation, classroom $CO_2$ dynamic modeling, and iterative ventilation control algorithms. |
| **Sem 1: Basic Electronic Systems** *(10 ECTS)*<br/>*Alcomatic - Epidemic Bartender* | NodeMCU-32s (ESP32) microcontroller programmed in C++, automated fluid dispensing, sensors, and actuators. |
| **Sem 0: RoboCup Tournament**<br/>🏆 **1st Place Winner** | LEGO Mindstorms EV3 programmed in **Python**. Autonomous line tracking, obstacle negotiation, bottle transport claw. Awarded 1st place tournament trophy for fastest time and highest score. |

<details>
<summary><b>📚 Bachelor's Level Foundational Course Catalog (Click to expand)</b></summary>

| Course | Key Theoretical Concepts & Practical Methods |
| :--- | :--- |
| **Lineær Algebra (Linear Algebra)** | Vector spaces, matrices, Gauss elimination, eigenvalues and eigenvectors, orthogonal bases, projection operators, least-squares approximation. |
| **Sandsynlighedsregning og Statistik** | Probability spaces, random variables, Bayes' theorem, Maximum Likelihood (ML) estimation, hypothesis testing, Gaussian/Poisson/Binomial distributions. |
| **Matriksberegning og Konveks Optimering** | Matrix norms, Singular Value Decomposition (SVD), numerical optimization (Steepest Descent, Newton, Gauss-Newton), convex sets and Lagrange multipliers. |
| **Design af Indlejret Software (Embedded Software Design)** | Real-time operating systems (RTOS), state machines (FSM), scheduling algorithms, inter-process communication (IPC), context switching, interrupt handling (ISR). |
| **Digital Design** | Digital logic circuits, Boolean algebra, FSM & FSMD design, flip-flops, LUTs, ALUs, pipelining, bus architectures, timing analysis, clock skew. |
| **Signalbehandling (Signal Processing)** | Continuous and discrete signals, Z-transform, FIR and IIR digital filter design, DFT/FFT, phase linearity, group delay, quantization effects. |
| **Kommunikation i Elektroniske Systemer** | Serial bus standards (UART, I2C, SPI, RS232, RS485), Ethernet, Bluetooth, OSI reference model, IP protocol stack, Medium Access Control (MAC). |
| **Modellering og Regulering (Control Engineering)** | Dynamic system modeling from differential equations, Laplace transforms, transfer functions, Bode plots, stability margins, lead/lag and PID controller design. |
| **Kredsløbsteori og Dynamiske Systemer** | RLC network analysis, operational amplifiers, Kirchhoff's laws, impedance calculations, frequency response, feedback and stability. |
| **Beregningsteknik 1 & 2** | Complex analysis, Cauchy-Riemann equations, Taylor & Laurent series, Fourier transforms, vector calculus, spatial integration, LTI sampling theory. |
| **Analog Kredsløbsdesign (Analog Circuit Design)** | Semiconductor physics, diodes, BJTs, MOSFETs, operational amplifiers, thermal drift, harmonic distortion, CAE circuit simulation. |
| **Calculus** | Multivariable calculus, partial differentiation, extrema optimization, first- and second-order differential equations. |
| **Elektromagnetisme (Electromagnetism)** | Maxwell's equations, Coulomb/Ampère/Biot-Savart laws, transmission lines, impedance matching, wave reflections, EMC design principles. |
| **Struktureret Systemudvikling** | Requirements engineering, system decomposition, UML use cases, interface design, subsystem integration testing and verification. |
| **Imperativ Programmering** | Algorithmic logic, control flow, data structures, memory management, sorting and searching algorithms. |
| **Problembaseret Læring (PBL)** | AAU problem-oriented project methodology, multidisciplinary team collaboration, project milestone management. |

</details>

---

## 🛠️ Technical Skills & Tooling

| Domain | Technologies, Languages & Methodologies |
| :--- | :--- |
| **💻 Software & Languages** | **Python**, **C / C++**, **Dart**, **SQL**, **C# / .NET**, **MATLAB / Simulink**, **TypeScript / JavaScript**, **PHP**, **VHDL**, **Java**, **Bash / Shell**, Flutter, Flame Engine, BLoC/RxDart, REST APIs |
| **🤖 Automation & Robotics** | Industrial IoT testbeds, Autonomous Mobile Robots (MiR200), RoboCup navigation, UWB tracking, Computer Vision telemetry, Automated test pipelines |
| **🎛️ Regulation & Control** | State-space MIMO control, Cascaded PID with anti-windup, LQR optimal control, Multiplicative Extended Kalman Filtering (MEKF), B-dot Detumbling, $H_\infty$ robust control |
| **🎚️ Digital Signal Processing** | Adaptive Filtering (LMS, NLMS, RLS), FastICA, STFT, Mel-Spectrograms, Parametric spectral estimation (LPC), EKF/UKF, FIR/IIR filter design |
| **🔌 Embedded & Hardware** | Cypress PSoC 5LP, ATmega2560 (Arduino), FreeRTOS, PlatformIO, Altium Designer, Onshape, I2C, SPI, UART, RS485, Oscilloscopes & Logic Analyzers |
| **📡 Networks & Communication** | MQTT, WebSockets, Ultra-Wideband (UWB) RF, X25519 ECDH + AES-256-GCM cryptography, OSI stack, Distributed edge/cloud systems |
| **⚙️ DevOps & Engineering Tools** | Git / GitHub Actions (CI/CD), Linux, Docker, InfluxDB, PostgreSQL, SQLite, MySQL, Supabase, VS Code, ComfyUI |
| **🗣️ Spoken Languages** | **Danish** (Native / Fluent) • **English** (Native / Fluent) • **Arabic** (Native / Fluent) • **German** (Elementary) |

---

## 📬 Contact

* **Email**: [elomarjc@gmail.com](mailto:elomarjc@gmail.com)
* **LinkedIn**: [linkedin.com/in/jacob-el-omar](https://www.linkedin.com/in/jacob-el-omar/)
* **GitHub**: [@elomarjc](https://github.com/elomarjc)
* **Google Play**: [Elomar Studio](https://play.google.com/store/apps/developer?id=Elomar+Studio)
