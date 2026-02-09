# \# Custom Flight Controller (STM32F411) 🚁

# 

# A custom-designed flight controller PCB for autonomous drone stabilization and telemetry, powered by the \*\*STM32F411\*\* microcontroller.

# 

# \## 📷 Board Preview

# \### Top View

# \### Bottom View

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

# 

# \## 📂 Project Structure

# This repository contains all necessary files for manufacturing and review:

# \* \*\*`/Altium\_Project\_Files`\*\*: Source files (`.PrjPcb`, `.SchDoc`, `.PcbDoc`).

# \* \*\*`/Manufacturing`\*\*: Production-ready Gerber files, NC Drill, and Pick \& Place data.

# 

# \## 📐 Schematic Diagram

# ---

# \*Designed by \[Yusuf Kerem Yayla]\*

