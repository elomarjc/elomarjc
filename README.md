<div align="center">

# Jacob El-Omar

<p align="center">
  <a href="https://github.com/elomarjc"><img src="assets/typing_title.svg" alt="Jacob El-Omar Typing Headline" width="800" /></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jacob-el-omar/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/elomarjc"><img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://play.google.com/store/apps/details?id=com.elomarstudio.growafish"><img src="https://img.shields.io/badge/Google_Play-Grow_A_Fish-34A853?style=for-the-badge&logo=google-play&logoColor=white" alt="Google Play" /></a>
  <a href="mailto:elomarjc@gmail.com"><img src="https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://maps.google.com/?q=Aalborg,+Denmark"><img src="https://img.shields.io/badge/Location-Aalborg%2C%20Denmark-blue?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location" /></a>
</p>

<!-- Live Animated Grow A Fish Simulation Banner (Borderless) -->
<p align="center">
  <a href="https://github.com/elomarjc/grow-a-fish-case-study"><img src="assets/aquarium_pure.gif" alt="Grow A Fish Live Aquarium Simulation Engine" width="100%" /></a>
</p>

</div>

## About Me

I am a Software Engineer and Systems Architect with a **Master of Science in Engineering (Civilingeniør, cand.polyt.) in Electronic Systems** and a **Bachelor of Science in Electronics & IT (Process Control)** from Aalborg University.

My work spans the full spectrum of software and systems engineering: bridging bare-metal silicon, real-time operating systems, and mathematical signal processing with high-performance desktop and mobile applications. Whether optimizing sub-millisecond adaptive filters on embedded ARM processors, engineering cross-platform game engines with custom native C++ audio backends, or designing desktop symbolic algebra environments, I focus on building performant, reliable, and mathematically rigorous systems.

## Flagship Products & Visual Showcase

### OpenMath — Desktop & Web Computer Algebra System (CAS)
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Python 3.10+, PyQt6, SymPy, Matplotlib MathText, WebAssembly (Pyodide)*

<table>
  <tr>
    <td width="55%" valign="top">
      <p>An open-source interactive computer algebra system (CAS) and technical worksheet document environment engineered for symbolic calculus, dynamic 2D graphing, matrix computations, and arbitrary precision engineering mathematics.</p>
      <p>
        <a href="https://j2kjonas.github.io/OpenMath/"><img src="https://img.shields.io/badge/Launch-Web_Demo-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Launch Web Demo" /></a>
        <a href="https://github.com/J2KJonas/OpenMath"><img src="https://img.shields.io/badge/Source-GitHub_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo" /></a>
      </p>
    </td>
    <td width="45%" align="center">
      <a href="https://github.com/J2KJonas/OpenMath">
        <img src="assets/openmath_dark_showcase.gif" width="400" alt="OpenMath Dynamic App Showcase" style="border-radius: 12px; border: 1px solid #334155; box-shadow: 0 10px 30px rgba(0,0,0,0.5);" />
      </a>
      <br/><sub><i>OpenMath Desktop: Symbolic Calculus, Dark Mode CAS, &amp; High-Precision Computing</i></sub>
    </td>
  </tr>
</table>

---

### Grow A Fish — Production Mobile Game & Real-Time Ecosystem
*Co-developed with [J2KJonas](https://github.com/J2KJonas) • Shipped on Google Play • Flutter, Flame Engine, C++ FFI SoLoud, Supabase, Hive, X25519/AES-GCM*

<table>
  <tr>
    <td width="38%" align="center">
      <a href="https://github.com/elomarjc/grow-a-fish-case-study">
        <img src="assets/grow_a_fish_mobile_showcase.gif" width="280" alt="Grow A Fish Live Mobile Showcase" style="border-radius: 16px; border: 1px solid #334155; box-shadow: 0 10px 30px rgba(0,0,0,0.5);" />
      </a>
      <br/><sub><i>Grow A Fish: Aquarium Simulation, Match-3, Exploration, &amp; Progression</i></sub>
    </td>
    <td width="62%" valign="top">
      <p>A full-stack mobile game published on Google Play combining an organic virtual aquarium simulator with 7 arcade minigames, social tank visits, and real-time multiplayer lobbies. Features 330+ Dart modules, deterministic WebSocket netcode, hardware-backed E2EE, and a zero-latency C++ <code>SoLoud</code> audio engine integrated directly via Dart FFI.</p>
      <p>
        <a href="https://play.google.com/store/apps/details?id=com.elomarstudio.growafish"><img src="https://img.shields.io/badge/Google_Play-Install_App-34A853?style=for-the-badge&logo=googleplay&logoColor=white" alt="Google Play" /></a>
        <a href="https://github.com/elomarjc/grow-a-fish-case-study"><img src="https://img.shields.io/badge/Architecture-Technical_Whitepaper-6366F1?style=for-the-badge&logo=flutter&logoColor=white" alt="Case Study" /></a>
      </p>
    </td>
  </tr>
</table>

---

## Applied Research & Autonomous Systems

### Medical Acoustic DSP Engine — Smart Stethoscope Platform
*Master's Thesis R&D in collaboration with Ai Health Highway & Prof. Jan Østergaard (Aalborg University)*

<p>
  <a href="https://github.com/elomarjc/adaptive-noise-cancellation-dsp"><img src="https://img.shields.io/badge/Research-Thesis_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Thesis Repo" /></a>
</p>

* **Adaptive Filtering Core:** Engineered real-time LMS, Normalized LMS (NLMS), and Recursive Least Squares (RLS) adaptive noise cancellation filters with FastICA blind source separation for electronic stethoscopes (**AiSteth**).
* **Clinical Performance:** Validated up to **+34 dB SNR improvement** in physical acoustic testbeds, isolating diagnostic low-frequency cardiac valve sounds (S1, S2) and respiratory acoustics under high ambient clinic noise.
* **Embedded Silicon:** Deployed on **ARM Cortex-M4**, meeting sub-millisecond execution constraints with deterministic fixed-point buffers and zero dynamic heap allocation during acquisition.

---

### Autonomous AMR Multi-Sensor Fusion & Fleet Navigation
*AAU 5G Smart Production Lab • 1st Place AAU RoboCup Winner*

<p>
  <a href="https://github.com/elomarjc/indoor-positioning-amr-integration"><img src="https://img.shields.io/badge/Robotics-Positioning_Repository-181717?style=for-the-badge&logo=github&logoColor=white" alt="Robotics Repo" /></a>
</p>

* **Multi-Modal Sensor Fusion:** Concurrent 9-thread C++ sensor fusion engine integrating active Ultra-Wideband (UWB) RF tags, overhead Computer Vision tracking, and industrial **MiR200 Autonomous Mobile Robots**.
* **Safety & Navigation Governors:** Real-time trajectory prediction, time-to-collision safety governors, and automated velocity throttling via REST API dispatch.
* **Factory Telemetry Analytics:** High-throughput InfluxDB time-series streaming for real-time fleet analytics, positional error profiling, and latency tracking across the smart factory floor.

---

## Interactive Digital Twins Mission Control

A suite of 9 real-time mathematical digital twins, physical modeling testbenches, and interactive browser simulators. Click **Launch Simulator** to run any testbench directly in your browser:

<table width="100%">
  <tr>
    <td width="33%" valign="top">
      <h4>5G/6G RF Channel Studio</h4>
      <p><b>Domain:</b> RF &amp; Telecommunications</p>
      <p>TDL fading channels, Clarke/Jakes Doppler spectrum, 256-QAM constellation, and EVM distortion analysis.</p>
      <p>
        <a href="https://elomarjc.github.io/5g-rf-channel-studio/"><img src="https://img.shields.io/badge/Launch-Simulator-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Launch" /></a>
        <a href="https://github.com/elomarjc/5g-rf-channel-studio"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" /></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h4>CubeSat AOCS Flight Sim</h4>
      <p><b>Domain:</b> Aerospace Systems</p>
      <p>4th-order Runge-Kutta (RK4) orbit integration, quaternion attitude kinematics, and B-dot magnetic detumbling.</p>
      <p>
        <a href="https://elomarjc.github.io/cubesat-aocs-simulator/"><img src="https://img.shields.io/badge/Launch-Simulator-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Launch" /></a>
        <a href="https://github.com/elomarjc/cubesat-aocs-simulator"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" /></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h4>Industrial SCADA Process Twin</h4>
      <p><b>Domain:</b> Industrial Automation</p>
      <p>ISA-101 high-performance HMI, IEC 61131-3 Structured Text logic engine, and Modbus TCP telemetry.</p>
      <p>
        <a href="https://elomarjc.github.io/industrial-scada-digital-twin/"><img src="https://img.shields.io/badge/Launch-Simulator-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Launch" /></a>
        <a href="https://github.com/elomarjc/industrial-scada-digital-twin"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h4>Hearing Aid DSP Studio</h4>
      <p><b>Domain:</b> Audio &amp; Acoustic DSP</p>
      <p>Head shadow diffraction modeling, NLMS acoustic feedback cancellation, and 6-band WDRC dynamic compression.</p>
      <p>
        <a href="https://elomarjc.github.io/hearing-aid-dsp-studio/"><img src="https://img.shields.io/badge/Launch-Simulator-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Launch" /></a>
        <a href="https://github.com/elomarjc/hearing-aid-dsp-studio"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" /></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h4>Wind Turbine Load Control</h4>
      <p><b>Domain:</b> Clean Energy &amp; Power</p>
      <p>15 MW offshore aeroelastic modeling, Coleman multi-blade coordinate (MBC) transforms, and IPC pitch regulation.</p>
      <p>
        <a href="https://elomarjc.github.io/turbine-load-control-twin/"><img src="https://img.shields.io/badge/Launch-Simulator-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Launch" /></a>
        <a href="https://github.com/elomarjc/turbine-load-control-twin"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" /></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h4>PMSM Field-Oriented Control</h4>
      <p><b>Domain:</b> Electric Drives &amp; Motion</p>
      <p>Clarke/Park coordinate transforms, Space Vector PWM (SVPWM), and sliding mode observer (SMO) flux estimation.</p>
      <p>
        <a href="https://elomarjc.github.io/pmsm-foc-drive-twin/"><img src="https://img.shields.io/badge/Launch-Simulator-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Launch" /></a>
        <a href="https://github.com/elomarjc/pmsm-foc-drive-twin"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" /></a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h4>Pump Hydrodynamics Twin</h4>
      <p><b>Domain:</b> Fluid Systems &amp; Maintenance</p>
      <p>Affinity laws, Thoma cavitation factor analysis, and motor current signature analysis (MCSA) stator FFT.</p>
      <p>
        <a href="https://elomarjc.github.io/pump-hydrodynamics-digital-twin/"><img src="https://img.shields.io/badge/Launch-Simulator-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Launch" /></a>
        <a href="https://github.com/elomarjc/pump-hydrodynamics-digital-twin"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" /></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h4>Naval Radar Signal Studio</h4>
      <p><b>Domain:</b> Defense &amp; Radar Systems</p>
      <p>Cell-Averaging (CA-CFAR) and Ordered-Statistic (OS-CFAR) detection with 3-pulse MTI clutter rejection.</p>
      <p>
        <a href="https://elomarjc.github.io/naval-radar-signal-studio/"><img src="https://img.shields.io/badge/Launch-Simulator-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Launch" /></a>
        <a href="https://github.com/elomarjc/naval-radar-signal-studio"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" /></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h4>Cobot Kinematics &amp; Momentum</h4>
      <p><b>Domain:</b> Industrial Robotics</p>
      <p>6-DOF UR5e forward/inverse kinematics, Damped Least-Squares (DLS) singularity solver, and ISO/TS 15066 safety envelopes.</p>
      <p>
        <a href="https://elomarjc.github.io/cobot-kinematics-momentum-twin/"><img src="https://img.shields.io/badge/Launch-Simulator-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="Launch" /></a>
        <a href="https://github.com/elomarjc/cobot-kinematics-momentum-twin"><img src="https://img.shields.io/badge/Source-181717?style=flat-square&logo=github&logoColor=white" alt="Source" /></a>
      </p>
    </td>
  </tr>
</table>

## Technical Skills Matrix

<div align="center">

### Core Programming Languages
[![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)](https://en.wikipedia.org/wiki/C_(programming_language))
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org/)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![VHDL](https://img.shields.io/badge/VHDL-5C6BC0?style=for-the-badge)](https://en.wikipedia.org/wiki/VHDL)
[![MATLAB](https://img.shields.io/badge/MATLAB-ED8B00?style=for-the-badge&logo=mathworks&logoColor=white)](https://mathworks.com/)
[![Maple](https://img.shields.io/badge/Maple-D32F2F?style=for-the-badge)](https://www.maplesoft.com/)
[![Structured Text](https://img.shields.io/badge/Structured_Text_(ST)-1B365D?style=for-the-badge)](https://en.wikipedia.org/wiki/Structured_text)
[![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://en.wikipedia.org/wiki/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://en.wikipedia.org/wiki/CSS)
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white)](https://www.latex-project.org/)

### Frameworks, Engines & Real-Time Kernels
[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Flame Engine](https://img.shields.io/badge/Flame_Engine-FF6F00?style=for-the-badge)](https://flame-engine.org/)
[![PyQt6](https://img.shields.io/badge/PyQt6-41CD52?style=for-the-badge&logo=qt&logoColor=white)](https://riverbankcomputing.com/software/pyqt/)
[![.NET Core](https://img.shields.io/badge/.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![FreeRTOS](https://img.shields.io/badge/FreeRTOS-2E7D32?style=for-the-badge)](https://www.freertos.org/)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)](https://pytest.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org/)
[![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)](https://ffmpeg.org/)

### Embedded, Industrial Hardware & Protocols
[![Intel FPGA](https://img.shields.io/badge/Intel_Cyclone_V-0071C5?style=for-the-badge&logo=intel&logoColor=white)](https://www.intel.com/)
[![Cypress PSoC](https://img.shields.io/badge/Cypress_PSoC_5LP-003366?style=for-the-badge)](https://www.infineon.com/)
[![ARM Cortex](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=for-the-badge&logo=arm&logoColor=white)](https://www.arm.com/)
[![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)](https://www.espressif.com/)
[![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)](https://www.arduino.cc/)
[![MiR200](https://img.shields.io/badge/MiR200_AMR-EF4444?style=for-the-badge)](https://www.mobile-industrial-robots.com/)
[![Modbus](https://img.shields.io/badge/Modbus_TCP%2FRTU-005B94?style=for-the-badge)](https://modbus.org/)
[![CAN Bus](https://img.shields.io/badge/CAN_Bus-FF8C00?style=for-the-badge)](https://en.wikipedia.org/wiki/CAN_bus)
[![WebSockets](https://img.shields.io/badge/WebSockets-010101?style=for-the-badge&logo=socketdotio&logoColor=white)](https://websockets.spec.whatwg.org/)
[![MQTT](https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=eclipsemqtt&logoColor=white)](https://mqtt.org/)

### Cloud, EDA, Tooling & DevOps
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.kernel.org/)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/features/actions)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![PlatformIO](https://img.shields.io/badge/PlatformIO-F3811E?style=for-the-badge&logo=platformio&logoColor=white)](https://platformio.org/)
[![Quartus Prime](https://img.shields.io/badge/Quartus_Prime-0071C5?style=for-the-badge&logo=intel&logoColor=white)](https://www.intel.com/)
[![Onshape](https://img.shields.io/badge/Onshape_3D_CAD-1B72E8?style=for-the-badge)](https://www.onshape.com/)
[![Altium](https://img.shields.io/badge/Altium_Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white)](https://www.altium.com/)
[![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)](https://www.wireshark.org/)

</div>

## Education

* **M.Sc. in Engineering — Electronic Systems (Civilingeniør, cand.polyt.)**  
  Aalborg University (2023 – 2025) • 120 ECTS  
  *Focus on Advanced Signal Processing, Control Engineering, Spacecraft Dynamics, and Real-Time Systems.*

* **B.Sc. in Engineering — Electronics & IT (Process Control Specialization)**  
  Aalborg University (2020 – 2023) • 180 ECTS  
  *Focus on Closed-Loop Control, Industrial Automation, Digital Hardware (VHDL/FPGA), and Embedded Software.*

## Contact

<p align="center">
  <a href="mailto:elomarjc@gmail.com"><img src="https://img.shields.io/badge/Email-elomarjc%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/jacob-el-omar/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/elomarjc"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>
