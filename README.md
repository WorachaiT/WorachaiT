# Hi there, I'm Worachai 👋

🎓 **4th-Year Computer Engineering Student** based in **Khon Kaen, Thailand** 🇹🇭  
🔌 Passionate about **Embedded Systems**, **Firmware Development**, and **Secure Wireless IoT**

---

### 👨‍💻 About Me

I am a Computer Engineering student specializing in embedded firmware, network interfaces, and IoT architectures. Currently developing an **Aliro Smart Lock** as my Senior Capstone Project, focusing on next-generation digital credentials, hardware security, and low-power wireless communication.

- 🔭 **Current Projects:** 
  - [Aliro-Demo](https://github.com/WorachaiT/Aliro-Demo) — Smart lock implementation based on the Aliro specification using STM32, NFC, and BLE.
  - **NFC Captive Portal** — Seamless network authentication leveraging dynamic NFC tags, OpenWrt, and Microsoft Azure serverless services.
- 🔬 **Core Focus:** Bare-metal / HAL firmware development, Clock tree architecture & PLL debugging, Hardware power sequencing, and RF communication.
- 🛠️ **Hardware Debugging:** Hands-on experience with Oscilloscopes, Logic Analyzers, and In-Circuit Debuggers for signal verification and timing analysis.

---

### 🌟 Featured Projects

#### 1. 🔐 Aliro Smart Lock (Senior Project)
> An implementation of a secure access control reader based on the **Aliro specification** (Connectivity Standards Alliance), integrating NFC and BLE for mobile digital keys.

- **Silicon & Architecture:** Developed firmware on **STM32WBA52** (ARM Cortex-M33 with TrustZone), managing advanced clock trees (HSE/HSI, PLL1 fractional synthesis) and the STM32_WPAN BLE radio subsystem.
- **RF & NFC Integration:** Interfaced NFC Reader ICs (**ST25R300 / RE41**) over SPI/I2C for ISO/IEC 14443-A smart credential detection and field polling.
- **Precision Actuation & Timing:** Designed PWM driver modules using hardware 16/32-bit timers with sub-microsecond precision for servo lock mechanisms, complete with active-low power gating.

#### 2. 📶 NFC Captive Portal
> A contactless network access solution integrating hardware tags, custom router firmware, and cloud authentication.

- Utilizes **Dynamic NFC tags** to provide one-tap, dynamic guest credentials.
- Integrated with **OpenWrt** as the network gateway to capture, route, and manage client traffic.
- Leverages **Microsoft Azure Functions** as a serverless backend to validate access tokens securely and authorize internet access.

---

### 🛠️ Tech Stack & Skills

#### 💻 Programming Languages
![C](https://img.shields.io/badge/C_(C99/C11)-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Assembly](https://img.shields.io/badge/Assembly_(ARM)-555555?style=for-the-badge&logo=assemblyscript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash/PowerShell](https://img.shields.io/badge/Shell_Scripting-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

#### 🔌 Hardware & Microcontrollers
![STM32](https://img.shields.io/badge/STM32_(Cortex--M33/M4)-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![Espressif](https://img.shields.io/badge/ESP32_/_ESP--IDF-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![ARM](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![Embedded Linux](https://img.shields.io/badge/Embedded_Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

#### 📡 Protocols, Wireless & Peripherals
- **Wireless & Standards:** Bluetooth Low Energy (BLE 5.x / STM32_WPAN), NFC (ISO/IEC 14443-A/B, ST25R, Dynamic NFC Tags), Aliro Access Control
- **Bus & Peripherals:** UART / LPUART (DMA-driven, high-speed), SPI, I2C, Hardware Timers / PWM, ADC, GPIO Power Sequencing
- **Networking & Cloud:** OpenWrt, Captive Portal routing, Microsoft Azure (Serverless Functions)
- **RTOS & System Architecture:** FreeRTOS (Tasks, Queues, Semaphores, ISR handling), Low-Power Modes (Stop/Sleep, LPM)

#### 🧰 Tools & Instrumentation
- **IDEs & Toolchains:** STM32CubeIDE, STM32CubeMX, GCC ARM Embedded Toolchain, VS Code
- **Lab Instruments:** Digital Storage Oscilloscope (DSO), Logic Analyzer, Multimeter, ST-LINK / J-Link Debugger
- **Version Control:** Git, GitHub

---

### 📫 Connect with Me

- 📧 **Email:** [wochai.te@gmail.com](mailto:wochai.te@gmail.com)
- 📍 **Location:** Khon Kaen, Thailand
