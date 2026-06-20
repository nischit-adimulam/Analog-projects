# Power Electronic Converter Design

A rectifier + capacitive filter + buck converter cascade delivering regulated DC output from AC mains.

## Design
- Full-wave rectifier converts 230V, 50Hz AC mains to pulsating DC
- Capacitive filter smooths the rectified output
- Buck converter steps down and regulates the output to a stable 12V DC
- Output load: 6W LED, driven at full brightness

## Result
Delivered a stable, regulated 12V DC output, confirmed via multimeter.

## Challenges
Designing and building the inductor to its calculated value and making it work.

## Media
- `circuit_photo_buck.jpg` — full cascade build
