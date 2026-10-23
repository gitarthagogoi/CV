# Gitartha Gogoi

**Embedded firmware engineer** · real-time control on STM32 and ESP32 · FreeRTOS · C  
M.Tech, Digital Communication & Signal Processing · Ahmedabad, India

I write firmware for industrial control hardware, mostly the parts where timing, sensor noise and power failures meet. My background in signal processing and wireless research shows up in how I approach filtering, control loops and debugging.

---

### Now

**Embedded Firmware & Hardware Design Engineer, 4Climate** (Jan 2026 – present)

I work on firmware for a dual-MCU inline fertigation controller, which mixes nutrients and acid into water and irrigates field zones on a schedule.

- **STM32L471 + FreeRTOS:** the real-time dosing and irrigation state machine, EC/pH dosing control (feedforward with PI trim), power-cut recovery, and EEPROM persistence
- **ESP32-S3:** the LVGL touch UI, Wi-Fi, and AWS IoT (MQTT, Device Shadow), linked to the STM32 over a framed UART protocol
- **Validation:** bench endurance testing, and oscilloscope-level debugging of EMI and ground noise on the controller board

*The company's code is proprietary and isn't on this profile.*

---

### Research

I published two papers on IRS-assisted multi-user MISO downlink systems during my M.Tech:

- **Optimizing energy and spectral efficiency in hybrid IRS-assisted MU-MISO systems through power-aware element allocation**  
  G. Gogoi, A. K. Singh, P. Vishwakarma, S. N. Sur. *Physical Communication* (Elsevier), 2026.  
  [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1874490726002648) · [Baseline code](https://github.com/gitarthagogoi/Optimizing-energy-and-spectral-efficiency-in-hybrid-IRS-assisted-MU-MISO-systems)

- **Performance analysis of active IRS-assisted MU-MISO system**  
  G. Gogoi, T. Bose, P. Vishwakarma, S. N. Sur. *International Journal of Information Technology* (Springer), vol. 17, pp. 5135–5146, 2025.  
  [Paper](https://doi.org/10.1007/s41870-025-02663-1) · [Code](https://github.com/gitarthagogoi/Active-IRS-Aided-Wireless-Communication-System)

I was also a peer reviewer for ICCDN (2025–26).

---

### Open work on this profile

| Repository | What it is |
|---|---|
| [CAN-BUS-Embedded-Guide](https://github.com/gitarthagogoi/CAN-BUS-Embedded-Guide) | A practical guide to debugging CAN: bit timing, physical-layer faults, and TEC/REC error counters. STM32 and ESP32 (TWAI) examples are in progress. |
| [Hybrid IRS baseline code](https://github.com/gitarthagogoi/Optimizing-energy-and-spectral-efficiency-in-hybrid-IRS-assisted-MU-MISO-systems) | MATLAB benchmark precoders and channel model for the *Physical Communication* paper. |
| [Active IRS MU-MISO](https://github.com/gitarthagogoi/Active-IRS-Aided-Wireless-Communication-System) | Alternating optimization of IRS phase shifts with WMMSE precoding. |
| [Hybrid IRS simulation framework](https://github.com/gitarthagogoi/Joint-Beamforming-and-Optimization-for-Hybrid-IRS-assisted-Wireless-Communication-System) | A modular MATLAB testbed for active and passive IRS, including power-consumption modelling (work in progress). |

---

### Tools

- **Languages:** C, C++, Python, MATLAB
- **Embedded:** STM32 (HAL, STM32CubeIDE), ESP32 / ESP32-S3 (ESP-IDF, LVGL), FreeRTOS, Raspberry Pi CM4
- **Interfaces:** UART, I2C, SPI, LoRa, GSM, Wi-Fi, MQTT, AWS IoT Core
- **Control & signal:** feedforward/PI control, adaptive filtering, sensor validation, model-based design, MIMO precoding
- **Debug:** oscilloscope, ST-LINK/SWD, Git

---

### Contact

[gitarthaqwerty@gmail.com](mailto:gitarthaqwerty@gmail.com) · [LinkedIn](https://www.linkedin.com/in/gitartha-gogoi/) · [Website](https://gitarthagogoi.github.io/)
