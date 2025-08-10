#  Python–Arduino RS485 Control System for T200 Thrusters
A Python-based control and monitoring system for T200 thrusters, communicating with an Arduino Nano via UART over RS485. Designed for reliable two-way communication, enabling real-time control commands and sensor feedback.

Features:

Two-Way Communication: Send commands from Python to Arduino and receive live sensor data

RS485 Communication: Implemented with USB-to-TTL converters and MAX485 modules

Thruster Control: Control T200 thrusters via PWM from Arduino

Sensor Feedback: Monitor system status and sensor readings in real time

Hardware Used:

Arduino Nano

T200 Thrusters

MAX485 RS485 transceiver modules

USB-to-TTL converter

Power supply for thrusters and Arduino

Software Used:

Python for the control interface and serial communication

Arduino IDE for microcontroller programming

System Architecture:

Python Script: Sends UART commands over RS485 and processes received feedback

Arduino Nano: Receives commands, controls thrusters, and sends sensor data back

RS485 Interface: Enables robust, long-distance serial communication

