# 2425_maker_spectre

## Introduction

### Context

This project is made in the context of the second year option called "Maker" at the french graduate school ENSEA (https://www.ensea.fr). This option encourages learning by doing, using several manufacturing tools as part of a personal project.

### My project

The idea is to build a drone from almost non-existent knowledge in this field ( and so to learn how it's done ). The drone will be a quadrotor and its theme will be the spectrum of the Destiny video game series (see photo below). The ultimate aim is to turn it into a companion that will follow its ‘master’ wherever he goes.

<img src="https://github.com/user-attachments/assets/2c8c20e0-56f3-4f3e-a992-1068808213e8" width="100" height="200" />

## -Project milestones

### -Documentation and reproducibility: Share the progress, challenges, and solutions so that others can learn from the process
  -> Making of a tutorial like readme with a linear progression

### -Learn/relearn the fundamentals of drone design: Understand basic aerodynamics principles, components ( brushless motors control, propellers design, flight controllers, battery ), and assembly
  -> Choose wisely the motors ( not overkill )
  
  -> Find an effective propeller design ( efficient and not too noisy ) 
  
  -> Try to find balance between weight and autonomy

### -Design and aesthetics: Build a drone inspired by the Spectrum companion from Destiny, keeping the design functional and yet recognizable
  -> Use 3D CAD tools to make the drone's skeleton 
  
  -> Use of fabrics to lighten the body ?
  
  -> The design shouldn't disrupt the functionning

  
### For later work  -Implement autonomous navigation: Program the drone to follow a "master" 
  -> Compare and decide which technology use to implement this function by comparing many factors ( need for computing power, ease of implementation, precision )

## Tools and Materials

### Tools

#### Software :
  CAD software :
  -> we will learn and use onshape for designing the frame
  
  -> we will design our PCB on KiCAD
  
  Flight control software : 
  -> we will use betaflights solutions
  
#### Hardware :
  3D printer for the frame ( PCB, motors and battery support + design edges )
  Fabrics for the design ( flat surfaces )
  Soldering station for assembling components on the PCB

### Materials :
#### Actuator
Brushless motors and propellers suitable for quadrotor drones 
### Control
Flight controller
ESC (Electronic Speed Controllers)

  -> Designing one can be an objective, buying one if too difficult
  
  ->MOSFET + Driver + microcontroller
  
### Energy
Use of Lipo 2S for the drone

### Sensors
IMU = Accelerometer + Gyroscope
Barometer for altitude
(for autonomous part : bluetooth antena [find target relative position] + tof [obstacle avoidance])

### Communication
Radio transmitter
(for autonomous part : bluetooth)

### Frame
Lightweight materials for the body
-> PLA find balance between infill and weight

-> Fabrics

-> Thin wood sheets ?
![image](https://github.com/user-attachments/assets/ef3a1a53-c0b4-4ff5-8ef1-536e2d8c0f1a)
![image](https://github.com/user-attachments/assets/1228ebd2-2619-4e28-aecd-a9000c0b7683)
![image](https://github.com/user-attachments/assets/604373c1-4036-4d1f-8d70-7143f6e51cdf)



