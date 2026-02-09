# \# Custom Flight Controller (STM32F411) 🚁

# 

# A custom-designed flight controller PCB for autonomous drone stabilization and telemetry, powered by the \*\*STM32F411\*\* microcontroller.

# 

# \## 📷 Board Preview 


# \### Top View <img width="1199" height="717" alt="Screenshot 2026-02-09 232850" src="https://github.com/user-attachments/assets/f8cfeea4-9032-4728-bca8-26d6a97b3762" />


# \### Bottom View <img width="1042" height="693" alt="Screenshot 2026-02-09 233143" src="https://github.com/user-attachments/assets/d4a41496-4427-48cb-bc20-f028c7578eb9" />


# ---

# 

# \## 🛠 Technical Specifications

# Based on the provided schematic and PCB layout, the board features:

# 

# \### 🧠 Core System

# \* \*\*MCU:\*\* STM32F411CEU6 (ARM Cortex-M4, 100MHz)

# \* \*\*RTC:\*\* DS3231 Real-Time Clock with Battery Backup (CR1220)

# \* \*\*Storage:\*\* Onboard \*\*EEPROM\*\* (AT24C128C) \& \*\*MicroSD Card\*\* Slot (SPI) for Blackbox logging.

# 

# \### 🧭 Sensors \& Positioning

# \* \*\*IMU:\*\* MPU6050 (6-Axis Gyroscope \& Accelerometer) via I2C.

# \* \*\*Barometer:\*\* BMP388 (High-precision Pressure Sensor) for altitude hold.

# \* \*\*GPS:\*\* U-Blox NEO-M8N GNSS Module support (UART).

# 

# \### 📡 Connectivity \& Power

# \* \*\*Telemetry:\*\* Socket for \*\*XBee PRO S2C\*\* (Wireless Communication).

# \* \*\*Power Management:\*\*

# &nbsp;   \* Dual Regulation: L7805 (5V) and LD1086-3.3 (3.3V) Linear Regulators.

# &nbsp;   \* Separate Power inputs for ESCs and Backup systems.

# \* \*\*PCB Design:\*\* 2-Layer (Double-Sided) PCB with optimized signal routing.

## 🧩 PCB Layout <img width="1311" height="816" alt="Screenshot 2026-02-09 232418" src="https://github.com/user-attachments/assets/e349d22b-5b6a-400d-8760-02143cba8d5d" />

# 

# \## 📂 Project Structure

# This repository contains all necessary files for manufacturing and review:

# \* \*\*`/Altium\_Project\_Files`\*\*: Source files (`.PrjPcb`, `.SchDoc`, `.PcbDoc`).

# \* \*\*`/Manufacturing`\*\*: Production-ready Gerber files, NC Drill, and Pick \& Place data.

# 

# \## 📐 Schematic Diagram <img width="1230" height="863" alt="Screenshot 2026-02-09 232234" src="https://github.com/user-attachments/assets/8156aa4a-477f-4508-ad63-6c0003e6ef0e" />


# ---

# \*Designed by \[Yusuf Kerem Yayla]\*

