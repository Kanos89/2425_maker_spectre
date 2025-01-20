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

  
### ( -Implement autonomous navigation: Program the drone to follow a "master" )
  -> Compare and decide which technology use to implement this function by comparing many factors ( need for computing power, ease of implementation, precision )

## Tools and Materials

### Tools

#### Software :
  CAD software :
  -> we will learn and use onshape for designing the frame
  
  -> we will design our PCB on KiCAD
  
  Programming tools :
  -> C++/MATLAB ? to implement the code in the controller
  
  -> ( dev a mobile interface to control the drone ) 
  
#### Hardware :
  3D printer for the frame ( PCB, motors and battery support + design edges )
  Fabrics for the design ( flat surfaces )
  Soldering station for assembling components on the PCB

### Materials :
#### Actuator
Motors and propellers suitable for quadrotor drones 
### Control
Flight controller
ESCs (Electronic Speed Controllers)

  -> Designing one is an objective, buying one if too difficult
  
  ->MOSFET + Driver + microcontroller
  
### Energy
Battery pack and charger

### Sensors
IMU Complete Accelerometer + Gyroscope (+ Magnetometer)
Barometer/Ultrasonic sensor (also used if obstacle avoidance) or lidar for altitude

### Communication
Bluetooth transmitter ( can also use RSSI for proximity with the phone controlling the drone)

### Frame
Lightweight materials for the body
-> PLA

-> Fabrics

-> Thin wood sheets

## Project Documentation

### Progress Logs
Regular updates documenting each phase of the project will be maintained, covering :

1 Research and component selection

2 Design and prototyping

3 Assembly and testing

4 Iterations and improvements

### Challenges and Solutions
A section highlighting key challenges encountered and how they were addressed will be included in the final documentation.

## Retro planning 

| **Week**           | **Period**       | **Main Objectives**                                                                                     | **Deliverables / Milestones**                                                                          |
|---------------------|------------------|---------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|
| **Week 1**         | 20/01 - 26/01    | - Analyze requirements and plan the project<br>- Learn/review drone basics<br>- Research main components | - Preliminary component list<br>- Functional diagram of the drone<br>- Initial requirements document |
| **Week 2**         | 27/01 - 02/02    | - Select motors and ESCs<br>- Study propeller designs and basic calculations (autonomy, weight, thrust)  | - Final motor selection<br>- Preliminary calculations for propeller design                           |
| **Week 3**         | 03/02 - 09/02    | - Research custom ESC design<br>- Study MOSFETs, drivers, and suitable microcontrollers                  | - ESC specifications (initial component schematic)                                                   |
| **Week 4**         | 10/02 - 16/02    | - Finalize the list of required components<br>- Order components                                         | - All components ordered<br>- Procurement plan                                                       |
| **Week 5**         | 17/02 - 23/02    | - Model the frame using Onshape<br>- Start 3D prototyping                                               | - Preliminary 3D design of the frame<br>- First prints for testing                                   |
| **Week 6**         | 24/02 - 01/03    | - Deep dive into ESC design: detailed electronic schematic<br>- Start PCB design on KiCAD               | - KiCAD schematic for ESC<br>- Theoretical validation of the circuit                                 |
| **Week 7**         | 02/03 - 08/03    | - Mechanical assembly of the frame and motor mounting<br>- Finalize PCB for ESC                         | - Assembled frame with motors mounted<br>- PCB files ready for fabrication                           |
| **Week 8**         | 09/03 - 15/03    | - Solder and assemble the ESC<br>- Start unit testing: ESC, motors, batteries                          | - Functional ESC tested with a motor<br>- Documentation of unit tests                                |
| **Week 9**         | 16/03 - 22/03    | - Program basic controls (PWM, ESC)<br>- Begin developing the mobile app for Bluetooth control          | - Drone capable of responding to basic PWM commands<br>- Prototype of the mobile app interface       |
| **Week 10**        | 23/03 - 29/03    | - Integrate Bluetooth communication with the drone<br>- Test and refine the mobile app                 | - Fully operational Bluetooth control via mobile app<br>- App tested with all drone functionalities  |
| **Week 11**        | 30/03 - 04/04    | - Final optimization (stability, autonomy)<br>- Prepare for exhibition<br>- Finalize documentation      | - Fully functional drone ready for exhibition<br>- Final README with complete tutorial               |

