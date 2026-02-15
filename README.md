# Autonomous Mini-Rover

## Overview
This project implements an autonomous mini-rover controlled via a microcontroller and monitored using a Python GUI. The rover can read sensor inputs, navigate autonomously, and communicate telemetry to a PC interface.

## Features
- Embedded firmware for motor control and sensor readings
- Real-time telemetry displayed in a Python GUI (Tkinter)
- Autonomous behaviors (e.g., obstacle avoidance, line following)
- Modular design for easy expansion (add more sensors or behaviors)

## Hardware Requirements (if using physical rover)
- Microcontroller (Raspberry Pi Pico, Arduino, or similar)
- Motors and motor driver
- Distance or line sensors
- USB cable or wireless connection (UART/Wi-Fi)

## Software Requirements
- Python 3.x
- Tkinter (for GUI)
- PySerial (for microcontroller communication)

## Setup Instructions

### 1. Firmware
1. Connect microcontroller to PC
2. Upload `firmware/main.py` (and associated files) to the device
3. Configure pins in `config.py`

### 2. GUI
1. Install Python dependencies
```bash
pip install pyserial
