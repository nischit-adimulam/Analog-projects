# Real-Time Voltage Analyser

A low-cost PC-based oscilloscope built using a PIC18F452 and an ESP32.

## Design
- PIC18F452 samples the analog input via its onboard 10-bit ADC
- Sampled data streamed over UART to an ESP32
- ESP32 relays the data to a PC over USB
- Python script (Matplotlib) reconstructs and plots the waveforms

## Result
Successfully reconstructed input waveforms in real time on the PC, validated against a reference oscilloscope.

## Challenges
Matching the UART baud rate and buffer handling between the PIC and ESP32 to avoid sample loss at higher input frequencies.

## Media
![PIC18F452 + ESP32 + PC setup](setup_photo_pc_oscilloscope.jpg)
[working demo](demo_pc_1.mp4)
