# Traffic Light Using micro:bit

## Project Image

(Project image will be added soon.)

## Project Overview

This project demonstrates how a traffic light system can be simulated using the BBC micro:bit.

The micro:bit automatically changes between red, yellow, and green signals using programmed timing sequences.

## Learning Objectives

- Understand traffic signal systems.
- Learn sequencing and timing concepts.
- Explore LED output control.
- Build a real-world simulation project.

## Components Required

| Component | Quantity |
|------------|----------|
| BBC micro:bit | 1 |
| USB Cable | 1 |
| Battery Pack | 1 |

## Working Principle

1. The program starts with the red signal.
2. After a delay, the signal changes to yellow.
3. The signal then changes to green.
4. The cycle repeats continuously.

## MakeCode Program

```javascript
basic.forever(function () {
    basic.showString("R")
    basic.pause(3000)

    basic.showString("Y")
    basic.pause(1000)

    basic.showString("G")
    basic.pause(3000)
})
```

## Applications

- Traffic signal simulation
- Smart city education
- STEM learning
- Programming practice

## Future Improvements

- Pedestrian crossing button
- Smart traffic control
- Sensor-based traffic lights
- Wireless communication

## Author

AnanyaLabs
