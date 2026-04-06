# 🚧 Under Active Development 🚧

# J.O.L.T ⚡

### Joint Operated Legged Terrain-walker

## Overview

JOLT is a fully custom quadruped robot inspired by the [MIT Cheetah](https://news.mit.edu/2019/mit-mini-cheetah-first-four-legged-robot-to-backflip-0304), designed and built from scratch. Every component — from the PCB to the frame to the firmware — was designed, sourced, and assembled independently.

![alt text](<assets/Screenshot from 2026-04-05 14-22-15.png>) ![alt text](<assets/Screenshot from 2026-04-05 14-22-29.png>) ![alt text](<assets/Screenshot from 2026-03-24 19-16-09.png>)

## Hardware

### Actuators

| Joint     | Servo  | Count |
| --------- | ------ | ----- |
| Hip yaw   | MG996R | 4     |
| Hip pitch | MG996R | 4     |
| Knee      | MG996R | 4     |

### Custom Devboard

| Component    | Part                         |
| ------------ | ---------------------------- |
| MCU          | STM32-F405RGT6               |
| IMU          | ICM42688-P                   |
| Servo driver | PCA9685                      |
| Power        | LDO 5V + LDO 3.3V            |
| Debug        | ST-Link                      |
| Input        | XT-60 connector (2S/3S LiPo) |

[BOM](<assets/J.O.L.T (Joint Operated Legged Terrain-walker)-bom.csv>)

## Build Progress 🛠️

- [x] Inverse kinematics
- [x] Tibia CAD
- [x] Femur CAD
- [x] Hip bracket CAD
- [ ] ~~Body plate~~
- [x] Chassis finalization
- [x] Devboard schematic
- [x] Devboard PCB layout
- [ ] Firmware — IK implementation
- [ ] Firmware — gait algorithm
- [ ] Assembly + wiring
- [ ] Walking test

## License

MIT License — see [LICENSE](LICENSE)

---

## Author

**Shaurya Tamang** .
[GitHub](https://github.com/GoTouchGra55) .
[Website](https://shauryatamang.netlify.app)
