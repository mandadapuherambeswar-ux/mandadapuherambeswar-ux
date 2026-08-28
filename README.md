<div align="center">

# ⚡ Herambeswar Mandadapu
### **Embedded Systems Engineer | Firmware & Edge AI Developer | IoT Architect**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/herambeswar-mandadapu-5a977a385)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mandadapuherambeswar-ux)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mandadapuherambeswar@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-6366F1?style=for-the-badge&logo=googlechrome&logoColor=white)](https://github.com/mandadapuherambeswar-ux/liquid-glass-portfolio)

<br/>

> *Electronics & Communication Engineering graduate specializing in real-time embedded firmware, bare-metal peripheral drivers, hardware-in-the-loop (HIL) automation, low-power LoRaWAN architectures, digital signal processing (DSP / EKF), and automotive diagnostic stacks (CAN / ISO-TP / OBD-II).*

</div>

---

### 🛠️ Technical Competencies

<table>
  <tr>
    <td width="30%"><strong>Microcontrollers & Hardware</strong></td>
    <td>
      <code>STM32 (ARM Cortex-M4/M3/M0)</code> • <code>ESP32 / ESP32-CAM</code> • <code>ESP8266</code> • <code>AVR ATmega328P</code> • <code>SX1276 LoRa</code>
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>Firmware, RTOS & Security</strong></td>
    <td>
      <code>FreeRTOS (Tasks, Queues, Mutexes)</code> • <code>Dual-Bank IAP Bootloaders</code> • <code>Bare-Metal Register C</code> • <code>STM32 HAL / LL</code> • <code>Watchdog (IWDG)</code>
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>Automotive & Hardware Protocols</strong></td>
    <td>
      <code>ISO 15765-2 (ISO-TP)</code> • <code>SAE J1979 / OBD-II</code> • <code>CAN Bus (ISO 11898)</code> • <code>SPI</code> • <code>I2C</code> • <code>UART / USART DMA</code>
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>Wireless, DSP & Edge AI</strong></td>
    <td>
      <code>LoRaWAN Class A (ADR / Deep Sleep)</code> • <code>Extended Kalman Filter (EKF)</code> • <code>TinyML Audio (MFCC + Quantized NN)</code> • <code>Quaternion Kinematics</code>
    </td>
  </tr>
  <tr>
    <td width="30%"><strong>Testing, HIL & Diagnostics</strong></td>
    <td>
      <code>Automated HIL Testing (PyHIL-Runner)</code> • <code>Logic Analyzer Waveform Decoding</code> • <code>Pytest</code> • <code>JTAG/SWD Debugging</code>
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

#### 1. [BareMetal-ARM-CortexM-Driver-Library](https://github.com/mandadapuherambeswar-ux/BareMetal-ARM-CortexM-Driver-Library)
> **Register-Level Bare-Metal Peripheral Driver Library for ARM Cortex-M4 (STM32F4)**
* **Architecture:** Developed 100% from scratch with zero vendor HAL dependencies. Implements atomic GPIO bit manipulation (`BSRR`), fractional USART Baud Rate Generator (`BRR`), and NVIC/SysTick timing.
* **Tech Stack:** `Bare-Metal C99`, `ARM Cortex-M4`, `Memory-Mapped Registers`, `Bitwise Optimization`.

---

#### 2. [STM32-FreeRTOS-Telemetry-Hub](https://github.com/mandadapuherambeswar-ux/STM32-FreeRTOS-Telemetry-Hub)
> **Deterministic Industrial Sensor Telemetry Hub using FreeRTOS on ARM Cortex-M4**
* **Architecture:** Multi-tasking FreeRTOS pipeline (`SensorAcq`, `TelemetryTx`, `Supervisor`) with mutex-protected I2C, CRC16-CCITT packet framing, and watchdog heartbeat supervisor.
* **Tech Stack:** `Embedded C`, `FreeRTOS`, `STM32F4`, `I2C`, `UART DMA`, `CRC16`.

---

#### 3. [Automotive-CAN-OBD2-Diagnostics-Core](https://github.com/mandadapuherambeswar-ux/Automotive-CAN-OBD2-Diagnostics-Core)
> **Automotive ISO 15765-2 (ISO-TP) Transport Stack & SAE J1979 / OBD-II Diagnostic Core**
* **Architecture:** Multi-frame segmented transport engine with Flow Control (`FC`), Mode 01 PID engine telemetry dispatcher, and Mode 03 DTC error reporting with Python virtual ECU test harness.
* **Tech Stack:** `C99`, `ISO-TP`, `OBD-II / UDS`, `CAN Bus`, `Python HIL Fuzzer`.

---

#### 4. [LowPower-LoRaWAN-Environmental-Node](https://github.com/mandadapuherambeswar-ux/LowPower-LoRaWAN-Environmental-Node)
> **Ultra-Low-Power LoRaWAN Environmental Sensor Node (5+ Years Battery Life)**
* **Architecture:** LoRaWAN Class A uplink serialization with Adaptive Data Rate (ADR), microamp-level deep sleep duty cycling (2.2 µA), and battery longevity mathematical modeling.
* **Tech Stack:** `Embedded C`, `LoRaWAN Class A`, `RF / Wireless`, `Power Optimization`, `Python Packet Decoder`.

---

#### 5. [TinyML-Audio-Keyword-Spotter](https://github.com/mandadapuherambeswar-ux/TinyML-Audio-Keyword-Spotter)
> **Real-Time Edge AI Audio Keyword Spotting & MFCC Feature Extractor**
* **Architecture:** Mel-Frequency Cepstral Coefficients (MFCC) DSP extraction pipeline (Windowing, FFT, Mel filterbanks, DCT) feeding an 8-bit quantized neural network classifier (<14 ms latency).
* **Tech Stack:** `C99`, `TinyML`, `MFCC DSP`, `Quantized Neural Networks`, `ARM Cortex-M4`.

---

#### 6. [Embedded-DSP-Sensor-Fusion-Kalman](https://github.com/mandadapuherambeswar-ux/Embedded-DSP-Sensor-Fusion-Kalman)
> **6-DOF IMU Attitude & Heading Reference System (AHRS) with Extended Kalman Filter**
* **Architecture:** Fast unit quaternion kinematics, dynamic gyro bias estimation, shock rejection, and 6-DOF Extended Kalman Filter (EKF) with real-time Euler angle output.
* **Tech Stack:** `ANSI C`, `Extended Kalman Filter (EKF)`, `Quaternion Math`, `DSP`, `Python 3D Plotter`.

---

#### 7. [STM32-Secure-DualBank-Bootloader](https://github.com/mandadapuherambeswar-ux/STM32-Secure-DualBank-Bootloader)
> **Fail-Safe Dual-Bank In-Application-Programming (IAP) Bootloader**
* **Architecture:** Dual-slot (A/B) flash partitioning, cryptographic header verification, whole-image CRC32 integrity check, automated brick-proof rollback, and vector table relocation (`SCB->VTOR`).
* **Tech Stack:** `Embedded C`, `ARM Cortex-M4`, `Flash Memory Management`, `CRC32`, `Python Packager`.

---

### 📜 Certifications & Credentials

* 🏅 **AWS Certified Cloud Practitioner** — Amazon Web Services
* 🏅 **Tessolve Level 2:** Industrial IoT (IIoT) Programming & Architecture
* 🏅 **Tessolve Level 1:** Embedded Systems & IoT Fundamentals

---

### 📊 Profile Analytics & Activity

<div align="center">

[![Profile Views](https://komarev.com/ghpvc/?username=mandadapuherambeswar-ux&color=6366F1&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/mandadapuherambeswar-ux)
[![Repositories](https://img.shields.io/badge/Public%20Repositories-16-238636?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mandadapuherambeswar-ux?tab=repositories)
[![Followers](https://img.shields.io/github/followers/mandadapuherambeswar-ux?style=for-the-badge&logo=github&labelColor=181717&color=0A66C2)](https://github.com/mandadapuherambeswar-ux?tab=followers)

</div>

---

<div align="center">
  <sub>Designed & Developed by <strong>Herambeswar Mandadapu</strong> • Vijayawada, India</sub>
</div>
