# Hi there, I'm Worachai 👋

🎓 **4th-Year Computer Engineering Student** based in **Khon Kaen, Thailand** 🇹🇭  
🔌 Passionate about **Embedded Systems**, **Firmware Development**, and **Secure Wireless IoT**

---

### 👨‍💻 About Me

I am a Computer Engineering student specializing in embedded firmware and IoT architectures. Currently developing an **Aliro Smart Lock** as my Senior Capstone Project, focusing on next-generation digital credentials, hardware security, and low-power wireless communication.

- 🔭 **Senior Project:** [Aliro-Demo](https://github.com/WorachaiT/Aliro-Demo) — Implementation of an Aliro-compliant smart lock leveraging STM32 wireless microcontrollers, NFC, and Bluetooth Low Energy (BLE).
- 🔬 **Core Focus:** Bare-metal / HAL firmware development, Clock tree architecture & PLL debugging, Hardware power sequencing, and RF communication.
- 🛠️ **Hardware Debugging:** Hands-on experience with Oscilloscopes, Logic Analyzers, and In-Circuit Debuggers for signal verification and timing analysis.

---

### 🌟 Featured Project: Aliro Smart Lock

> An implementation of a secure access control reader based on the **Aliro specification** (Connectivity Standards Alliance), integrating NFC and BLE for mobile digital keys.

**Key Engineering Highlights & Insights Gained:**
- **Silicon & Architecture:** Developed firmware on **STM32WBA55** (ARM Cortex-M33 with TrustZone), managing advanced clock trees (HSE/HSI, PLL1 fractional synthesis) and the STM32_WPAN BLE radio subsystem.
- **RF & NFC Integration:** Interfaced NFC Reader ICs (**ST25R3916 / RE41**) over SPI/I2C for ISO/IEC 14443-A smart credential detection and field polling.
- **Precision Actuation & Timing:** Designed PWM driver modules using hardware 16/32-bit timers with sub-microsecond precision for servo lock mechanisms, complete with active-low power gating.
- **Root-Cause Hardware Debugging:**
  - Diagnosed clock-drift anomalies using an **oscilloscope**, tracing baud-rate framing errors ($921.6\text{ kbps}$) and PWM dilation ($100\ \mu\text{s} \to 225\ \mu\text{s}$) to PLL unlock states and VCO boundary constraints.
  - Resolved Cold Boot vs. Warm Reset transients, crystal stabilization delays, and SRAM memory retention quirks across system resets.
- **Embedded Toolchains & VCS:** Managed modular firmware architecture, CMSIS Device dependencies, and vendor SDK git structures.

---

### 🛠️ Tech Stack & Skills

#### 💻 Programming Languages
![C](https://img.shields.io/badge/C_(C99/C11)-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash/PowerShell](https://img.shields.io/badge/Shell_Scripting-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

#### 🔌 Hardware & Microcontrollers
![STM32](https://img.shields.io/badge/STM32_(Cortex--M33/M4)-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Espressif](https://img.shields.io/badge/ESP32_/_ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![ARM](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![Embedded Linux](https://img.shields.io/badge/Embedded_Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

#### 📡 Protocols, Wireless & Peripherals
- **Wireless & Standards:** Bluetooth Low Energy (BLE 5.x / STM32_WPAN), NFC (ISO/IEC 14443-A/B, ST25R), Aliro Access Control
- **Bus & Peripherals:** UART / LPUART (DMA-driven, high-speed), SPI, I2C, Hardware Timers / PWM, ADC, GPIO Power Sequencing
- **RTOS & System Architecture:** FreeRTOS (Tasks, Queues, Semaphores, ISR handling), Low-Power Modes (Stop/Sleep, LPM)

#### 🧰 Tools & Instrumentation
- **IDEs & Toolchains:** STM32CubeIDE, STM32CubeMX, GCC ARM Embedded Toolchain, VS Code
- **Lab Instruments:** Digital Storage Oscilloscope (DSO), Logic Analyzer, Multimeter, ST-LINK / J-Link Debugger
- **Version Control:** Git, GitHub

---

### 📫 Connect with Me

- 📧 **Email:** [wochai.te@gmail.com](mailto:wochai.te@gmail.com)
- 📍 **Location:** Khon Kaen, Thailand
- 💼 **LinkedIn:** [linkedin.com/in/your-profile](https://linkedin.com) *(Optional)*
