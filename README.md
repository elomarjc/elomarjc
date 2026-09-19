# Jacob El-Omar

**Electronic Systems Engineer (M.Sc., Aalborg University)**  
*Software • Embedded Systems • Control & Automation • Signal Processing*

[LinkedIn](https://www.linkedin.com/in/jacob-el-omar/) • [Google Play](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish) • [Email](mailto:elomarjc@gmail.com)

---

I build systems where software interacts directly with physical hardware — from embedded firmware and closed-loop control to desktop mathematical tools and interactive simulators.

### What I Work With
* **Embedded & Hardware:** C/C++, FreeRTOS, ARM Cortex-M, Cypress PSoC 5LP, FPGA/VHDL (Intel Cyclone V), PlatformIO
* **Control & Robotics:** State-space modeling, discrete PID, LQR, Kalman filtering (EKF/MEKF), autonomous mobile robots (AMRs)
* **Signal Processing:** Adaptive filtering (LMS, NLMS, RLS), blind source separation (FastICA), spectral analysis, audio pipelines
* **Software & Systems:** Python, PyQt6, Flutter/Dart (native C++ FFI), WebAssembly, Git, Linux

---

## Featured Projects

### [OpenMath](https://github.com/elomarjc/openmath)
A desktop and web-based computer algebra system focused on symbolic computation, typeset mathematics, and embedded systems arithmetic.
* Built with Python, PyQt6, SymPy, and Matplotlib; runs client-side in the browser via Pyodide and WebAssembly.
* Includes an interactive matrix wizard alongside dedicated tools for fixed-point Q-format arithmetic, IEEE-754 inspection, and bitwise logic.
* [GitHub Repository](https://github.com/elomarjc/openmath) • [Live Web App](https://j2kjonas.github.io/OpenMath/)

### [Adaptive Noise Cancellation for Stethoscopes](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)
Master's thesis research in active acoustic noise reduction to preserve heart and lung sounds in noisy clinical environments.
* Implemented and evaluated LMS, NLMS, RLS, and FastICA algorithms in Python and MATLAB.
* Preserved subtle low-frequency valve sounds ($S_1, S_2$) while achieving up to +34 dB SNR improvement across test recordings.
* [GitHub Repository](https://github.com/elomarjc/adaptive-noise-cancellation-dsp)

### [Grow A Fish](https://github.com/elomarjc/grow-a-fish-case-study)
A 2D mobile game and real-time multiplayer ecosystem published on Google Play.
* Built with Flutter and Flame, integrating the C++ `SoLoud` audio engine via Dart FFI for zero-latency mobile audio.
* Includes client-side end-to-end encrypted messaging (X25519 ECDH + AES-256-GCM) and deterministic procedural generation.
* [Technical Case Study](https://github.com/elomarjc/grow-a-fish-case-study) • [Google Play Store](https://play.google.com/store/apps/details?id=com.elomarstudio.growafish)

### [AAUSAT6 CubeSat: Attitude Determination & Control](https://github.com/elomarjc/advanced-control-digital-systems)
Flight control and attitude stabilization design for the AAUSAT6 CubeSat mission in Low Earth Orbit.
* Modeled orbital kinematics and developed magnetic B-dot detumbling to eliminate post-deployment tip-off spin.
* Designed LQR state-feedback with momentum wheels for target pointing and analyzed $H_\infty$ disturbance rejection.
* [GitHub Repository](https://github.com/elomarjc/advanced-control-digital-systems)

### [Real-Time Anti-Sway Gantry Crane Control](https://github.com/elomarjc/gantry-crane-anti-sway-control)
A physical laboratory gantry crane running discrete feedback control to suppress pendulum sway during fast transit.
* Linearized dynamic equations of motion derived from first principles and tuned cascaded controllers against physical step responses.
* Written in embedded C++ for the ATmega2560 with anti-windup, velocity filtering, and motor current saturation limits.
* [GitHub Repository](https://github.com/elomarjc/gantry-crane-anti-sway-control)

---

## Interactive Simulators & Digital Twins

Browser-based engineering models built with Three.js, WebGL, and Canvas:

* **[Industrial SCADA Digital Twin](https://github.com/elomarjc/industrial-scada-digital-twin)** — IEC 61131-3 Structured Text runtime, ISA-101 HMI, and Modbus TCP. ([Live Simulator](https://elomarjc.github.io/industrial-scada-digital-twin/))
* **[CubeSat 3D AOCS Flight Simulator](https://github.com/elomarjc/cubesat-aocs-simulator)** — Real-time orbital propagation, magnetic detumbling, and attitude control. ([Live Simulator](https://elomarjc.github.io/cubesat-aocs-simulator/))
* **[5G RF Channel & Constellation Studio](https://github.com/elomarjc/5g-rf-channel-studio)** — 3GPP fading channel models, EVM sweeps, and constellation analysis. ([Live Simulator](https://elomarjc.github.io/5g-rf-channel-studio/))
* **[Hearing Aid DSP Studio](https://github.com/elomarjc/hearing-aid-dsp-studio)** — Differential microphone beamforming, feedback cancellation, and dynamic range compression. ([Live Simulator](https://elomarjc.github.io/hearing-aid-dsp-studio/))
* **[UR5e Cobot Kinematics & Observer](https://github.com/elomarjc/cobot-kinematics-momentum-twin)** — Damped least-squares inverse kinematics and sensorless collision detection. ([Live Simulator](https://elomarjc.github.io/cobot-kinematics-momentum-twin/))

---

## Other Engineering Projects

* **[Multi-Sensor AMR Fleet Positioning](https://github.com/elomarjc/indoor-positioning-amr-integration)** — Multi-threaded sensor fusion engine tracking autonomous mobile robots via Ultra-Wideband (UWB) and overhead cameras.
* **[3-DoF Satellite Simulator Balancing](https://github.com/elomarjc/satellite-simulator-adcs-calibration)** — Automatic center-of-mass balancing on a spherical air bearing using Cypress PSoC 5LP, FreeRTOS, and MEKF estimation.
* **[Multivariable Distillation Column Control](https://github.com/elomarjc/multivariable-distillation-column-control)** — MIMO state-space decoupling and LQR control for the Wood-Berry benchmark system.

---

## Contact

* **Email:** [elomarjc@gmail.com](mailto:elomarjc@gmail.com)
* **LinkedIn:** [linkedin.com/in/jacob-el-omar](https://www.linkedin.com/in/jacob-el-omar/)
* **Location:** Aalborg, Denmark
