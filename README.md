# 2425_maker_spectre

## Introduction

### Context

This project is made in the context of the second year option called "Maker" at the French graduate school ENSEA ([https://www.ensea.fr](https://www.ensea.fr)). This option encourages learning by doing, using several manufacturing tools as part of a personal project.

### My project

The idea is to build a drone from almost non-existent knowledge in this field (and so to learn how it's done). The drone will be a quadrotor and its theme will be the spectrum of the Destiny video game series (see photo below). The ultimate aim is to turn it into a companion that will follow its ‘master’ wherever he goes.

![Spectrum Drone](https://github.com/user-attachments/assets/2c8c20e0-56f3-4f3e-a992-1068808213e8)

## -Project milestones

### -Creating a flight control PCB

### -Creating a light 3D body which represents the drone from the game

### -Creating a 4 in 1 ESC PCB

### -Learn how to implement/use Betaflight for the software part

### -Design and aesthetics

Build a drone inspired by the Spectrum companion from Destiny, keeping the design functional and yet recognizable.

- Use 3D CAD tools to make the drone's skeleton
- (Use of fabrics to lighten the body, maybe in future versions)
- The design shouldn't disrupt the functioning

### For later work - Implement autonomous navigation

Program the drone to follow a "master".

- Compare and decide which technology to use to implement this function by comparing many factors (need for computing power, ease of implementation, precision)

## Tools and Materials

### Tools

#### Software:

- CAD software:
  - We will learn and use Onshape for designing the frame
  - We will design our PCB on KiCAD
- Flight control software:
  - We will use Betaflight solutions

#### Hardware:

- 3D printer for the frame (PCB, motors, and battery support + design of the drone body)
- Fabrics for the design (flat surfaces)
- Soldering station for assembling components on the PCB

### Materials:

#### Actuator

- Brushless motors and propellers suitable for quadrotor drones

#### Control

- Flight controller
- ESC (Electronic Speed Controllers)
  - Designing one can be an objective, buying one is too easy :)

#### Energy

- Use of Lipo 2S for the drone

#### Sensors

- IMU = Accelerometer + Gyroscope
- Barometer for altitude
- For autonomous part (in further versions):
  - Bluetooth antenna (find target relative position)
  - ToF sensor (obstacle avoidance)

#### Communication

- Radio transmitter
- For autonomous part: Bluetooth

#### Frame

- Lightweight materials for the body:
  - PLA: find balance between solidity and weight
  - (Fabric instead of full printed faces)
  - 3D design of the drone with Onshape

![Frame Design 1](https://github.com/user-attachments/assets/b0779466-b318-4b8b-896d-5f2980331e10)
![Frame Design 2](https://github.com/user-attachments/assets/dd088166-9f5d-4084-9ef7-fe2c30449972)
![Frame Design 3](https://github.com/user-attachments/assets/504cc3e9-6351-450c-9d58-85a2c4e19c57)

- Work done from now on:
  - Flight control PCB with KiCad:

![PCB 1](https://github.com/user-attachments/assets/ef3a1a53-c0b4-4ff5-8ef1-536e2d8c0f1a)
![PCB 2](https://github.com/user-attachments/assets/1228ebd2-2619-4e28-aecd-a9000c0b7683)
![PCB 3](https://github.com/user-attachments/assets/604373c1-4036-4d1f-8d70-7143f6e51cdf)

- Honorable mention for KiCad who only crashed 4 times during the rooting phase :)
