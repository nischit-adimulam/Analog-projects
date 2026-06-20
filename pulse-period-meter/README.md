# Digital Pulse Period Measurement Circuit

A digital circuit that measures and displays the period of an input clock pulse.

## Design
- High-frequency reference clock used as the timing base
- Gating logic enables counting only during the input pulse period
- Digital counters accumulate the count, converted to a time value
- 7-segment display shows the measured period directly in milliseconds

## Result
Accurately measured and displayed input pulse periods in the 1 ms – 7 ms range.

## Challenges
Designing the gating logic to reset and re-trigger cleanly between successive pulses without measurement glitches.

## Media
- `circuit_photo_dcs.jpg` — full digital logic build
- `demo_dcs.mp4` — working demo
