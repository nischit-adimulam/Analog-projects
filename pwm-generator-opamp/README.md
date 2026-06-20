# PWM Pulse Generator using Op-Amps

A two-IC741 op-amp circuit designed from scratch to generate a tunable PWM waveform.

## Design
- Astable multivibrator core built around two 741 op-amps
- Asymmetric diode feedback paths allow independent control of duty cycle
- Series resistor enables frequency tuning across 100 Hz – 10 kHz
- Non-inverting amplifier stage allows amplitude adjustment from 5V to 15V

## Result
Stable, independently tunable frequency and duty cycle confirmed on oscilloscope.

## Challenges
Maintaining clean switching at the upper end and lower end of the frequency range and duty ratio. 

## Media
- `circuit_photo_pwm.jpeg` — breadboard build
- `scope_output.jpg` — waveform output
- `simulation_pwm.jpg` — simulation
