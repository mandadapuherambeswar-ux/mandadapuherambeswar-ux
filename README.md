<div align="center">

# ⚡ Herambeswar Mandadapu
### **Embedded Systems Engineer | Firmware & Edge AI Developer | IoT Architect**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/herambeswar-mandadapu-5a977a385)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mandadapuherambeswar-ux)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mandadapuherambeswar@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/mandadapuherambeswar-ux/liquid-glass-portfolio)

<br/>

> *Electronics & Communication Engineering graduate specializing in real-time embedded firmware, hardware-in-the-loop (HIL) automation, low-power IoT architectures, digital signal processing (DSP), and automotive/industrial bus communications (CAN/OBD-II/SPI/I2C/UART).*

</div>

---

### 🛠️ Technical Competencies

<table>
  <tr>
    <td width="30%"><strong>Microcontrollers & SoCs</strong></td>
    <td>
      <code>STM32 (ARM Cortex-M4/M3/M0)</code> • <code>ESP32 / ESP32-CAM</code> • <code>ESP8266</code> • <code>AVR ATmega328P</code>
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>Firmware, RTOS & Security</strong></td>
    <td>
      <code>FreeRTOS (Tasks, Queues, Mutexes, Semaphores)</code> • <code>Dual-Bank IAP Bootloaders</code> • <code>Bare-Metal C</code> • <code>STM32 HAL / LL</code> • <code>Watchdog (IWDG/WWDG)</code>
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>Automotive & Hardware Protocols</strong></td>
    <td>
      <code>ISO 15765-2 (ISO-TP)</code> • <code>SAE J1979 / OBD-II</code> • <code>CAN Bus (ISO 11898)</code> • <code>SPI</code> • <code>I2C</code> • <code>UART / USART</code> • <code>DMA</code>
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>DSP, Fusion & Edge AI</strong></td>
    <td>
      <code>Extended Kalman Filter (EKF)</code> • <code>Quaternion Kinematics</code> • <code>CMSIS-DSP</code> • <code>Edge AI / Embedded CV</code> • <code>Sensor Fusion</code>
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>Testing, HIL & Diagnostics</strong></td>
    <td>
      <code>Automated HIL Testing (PyHIL-Runner)</code> • <code>Protocol Sniffer GUI (UART/I2C/SPI)</code> • <code>Pytest</code> • <code>JTAG/SWD Debugging</code>
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>Languages & Developer Tools</strong></td>
    <td>
      <code>Embedded C (C99/C11)</code> • <code>C++17</code> • <code>Python 3</code> • <code>PlatformIO</code> • <code>STM32CubeIDE</code> • <code>CMake / Make</code> • <code>Git</code> • <code>KiCad</code>
    </td>
  </tr>
</table>

---

### 🚀 Flagship Engineering Projects

#### 1. [STM32-FreeRTOS-Telemetry-Hub](https://github.com/mandadapuherambeswar-ux/STM32-FreeRTOS-Telemetry-Hub)
> **Deterministic Industrial Sensor Telemetry Hub on ARM Cortex-M4 using FreeRTOS**
* **Architecture:** Multi-tasking FreeRTOS pipeline (`SensorAcq`, `TelemetryTx`, `Supervisor`) with mutex-protected I2C, CRC16-CCITT packet framing, and watchdog heartbeat.
* **Tech Stack:** `Embedded C`, `FreeRTOS`, `STM32F4`, `I2C`, `UART DMA`, `CRC16`.

---

#### 2. [Automotive-CAN-OBD2-Diagnostics-Core](https://github.com/mandadapuherambeswar-ux/Automotive-CAN-OBD2-Diagnostics-Core)
> **Automotive ISO 15765-2 (ISO-TP) Transport Stack & SAE J1979 / OBD-II Diagnostic Core**
* **Architecture:** Multi-frame segmented transport engine with Flow Control (`FC`), Mode 01 PID engine telemetry dispatcher, and Mode 03 DTC error reporting.
* **Tech Stack:** `C99`, `ISO-TP`, `OBD-II / UDS`, `CAN Bus`, `Python HIL Fuzzer`.

---

#### 3. [Embedded-DSP-Sensor-Fusion-Kalman](https://github.com/mandadapuherambeswar-ux/Embedded-DSP-Sensor-Fusion-Kalman)
> **6-DOF IMU Attitude & Heading Reference System (AHRS) with Extended Kalman Filter**
* **Architecture:** Fast Quaternion kinematics, dynamic gyro bias estimation, linear acceleration shock rejection, and real-time Euler angle (Roll/Pitch/Yaw) output.
* **Tech Stack:** `ANSI C`, `Extended Kalman Filter (EKF)`, `Quaternion Math`, `DSP`, `Python 3D Plotter`.

---

#### 4. [STM32-Secure-DualBank-Bootloader](https://github.com/mandadapuherambeswar-ux/STM32-Secure-DualBank-Bootloader)
> **Fail-Safe Dual-Bank In-Application-Programming (IAP) Bootloader**
* **Architecture:** Dual-slot (A/B) flash partitioning, cryptographic header verification, whole-image CRC32 integrity check, automated brick-proof rollback, and vector relocation (`SCB->VTOR`).
* **Tech Stack:** `Embedded C`, `ARM Cortex-M4`, `Flash Memory Management`, `CRC32`, `Python Packager`.

---

#### 5. [Edge-AI-Safety-Node](https://github.com/mandadapuherambeswar-ux/Edge-AI-Safety-Node)
> **Multi-MCU Edge Computing Node with Automotive CAN Bus Integration**
* **Architecture:** STM32F401 (Supervisory Controller) + ESP32-CAM (Vision Inference) + MCP2515 (CAN Bus Controller over SPI).
* **Tech Stack:** `C++`, `STM32`, `ESP32-CAM`, `CAN Bus`, `SPI`, `Embedded AI`.

---

#### 6. [PyHIL-Runner](https://github.com/mandadapuherambeswar-ux/PyHIL-Runner)
> **Automated Hardware-in-the-Loop (HIL) Test & Validation Framework**
* **Architecture:** Automated serial test harness validating live microcontroller firmware against boundary cases, protocol compliance, and fault injection with Pytest.
* **Tech Stack:** `Python 3`, `Pytest`, `Serial/UART`, `Embedded C`, `CI/CD`.

---

#### 7. [PyLogic-Sniffer](https://github.com/mandadapuherambeswar-ux/PyLogic-Sniffer)
> **Microcontroller-Based Digital Logic Sniffer & Protocol Analyzer**
* **Architecture:** High-speed GPIO edge sampling engine paired with a desktop GUI for multi-protocol waveform decoding (UART, I2C, SPI).
* **Tech Stack:** `Python`, `Tkinter / PyQt`, `Microcontroller Firmware`, `UART`, `SPI`, `I2C`.

---

### 📜 Certifications & Credentials

* 🏅 **AWS Certified Cloud Practitioner** — Amazon Web Services
* 🏅 **Tessolve Level 2:** Industrial IoT (IIoT) Programming & Architecture
* 🏅 **Tessolve Level 1:** Embedded Systems & IoT Fundamentals

---

### 📊 Profile Analytics & Activity

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=mandadapuherambeswar-ux&color=6366F1&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/mandadapuherambeswar-ux)
[![Repositories](https://img.shields.io/badge/Public%20Repositories-13-238636?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mandadapuherambeswar-ux?tab=repositories)
[![Followers](https://img.shields.io/github/followers/mandadapuherambeswar-ux?style=for-the-badge&logo=github&labelColor=181717&color=0A66C2)](https://github.com/mandadapuherambeswar-ux?tab=followers)

</div>

---

<div align="center">
  <sub>Designed & Developed by <strong>Herambeswar Mandadapu</strong> • Vijayawada, India</sub>
</div>
