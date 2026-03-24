# 🚧 Under Active Development 🚧

# J.O.L.T ⚡

### Joint Operated Legged Terrain-walker

## Overview

JOLT is a fully custom quadruped robot inspired by the [MIT Cheetah](https://news.mit.edu/2019/mit-mini-cheetah-first-four-legged-robot-to-backflip-0304), designed and built from scratch. Every component — from the PCB to the frame to the firmware — was designed, sourced, and assembled independently.

## Hardware ⚡

### Actuators

| Joint     | Servo  | Count |
| --------- | ------ | ----- |
| Hip yaw   | MG996R | 4     |
| Hip pitch | MG996R | 4     |
| Knee      | MG996R | 4     |

### Custom Devboard

| Component    | Part                                  |
| ------------ | ------------------------------------- |
| MCU          | STM32-F405RGTx                            |
| IMU          | ICM42688-P (SPI)                      |
| Servo driver | PCA9685 (I2C, 16ch)                   |
| Power        | Buck converter + LDO 3.3V             |
| Debug        | Onboard ST-Link                       |
| Input        | XT-30 connector (2S/3S LiPo)          |

### Frame

- Material: PLA
- Design: MIT Cheetah inspired, triangular cutouts
- Leg links: 130mm shaft-to-shaft (femur + tibia)
- Internal tibia pivot slot in femur

---

## Build Progress 🛠️

- [x] Inverse kinematics 
- [x] Tibia CAD
- [x] Femur CAD
- [x] Hip bracket CAD
- [ ] Body plate CAD
- [ ] Devboard schematic
- [ ] Devboard PCB layout
- [ ] Firmware — IK implementation
- [ ] Firmware — gait algorithm
- [ ] Assembly + wiring
- [ ] Walking test

## License 🪪

MIT License — see [LICENSE](LICENSE)

---

## Author 👨

**Shaurya Tamang** .
[GitHub](https://github.com/GoTouchGra55) .
[Website](https://shauryatamang.netlify.app)
