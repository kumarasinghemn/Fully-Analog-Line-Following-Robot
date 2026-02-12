# Fully-Analog-Line-Following-Robot
This project was a group project completed under the module EN2091 - Laboratory Practice and Projects - Semester 3, Department of Electronic and Telecommunication Engineering, University of Moratuwa.
# Introduction
Line following is a common task in many robot applications.
But here the special case is our robot do line following using only analog electronic components.
That means no micro controllers as in common case.
<p align="center">
  <img src="https://github.com/user-attachments/assets/6fefdec3-7dbc-4b5b-8b93-a715bf572a0f" width="400"/>
</p>

## 🔧 Working Principle

- Fully autonomous control implemented **without any microcontroller**
- All functions handled using **pure analog circuitry**
- **IR sensor array** detects line position and measures deviation from center
- Sensors generate **continuous analog voltage signals**
- Signals are conditioned and processed through an **op-amp based PID controller**
  - Proportional (P) component for immediate error correction
  - Integral (I) component to eliminate steady-state error
  - Derivative (D) component to improve stability and response time
- P, I, and D outputs are combined to generate a **smooth corrective control signal**
- Analog adders and subtractors create **differential drive signals** for left and right motors
- Control voltage is converted into **PWM using a comparator and triangular wave generator**
- PWM signals drive the motor driver for precise speed and direction control
<p align="center">
  <img src="https://github.com/user-attachments/assets/8c0d613e-52f0-47c5-8377-b19cd23ffdaf" width="400"/>
</p>

# Software Specifications
- Altium Designer
- Solidworks
- LT Spice

# Enclosure Design
<p align="center">
  <img src="https://github.com/user-attachments/assets/931c004f-7da6-4d37-a7f1-5f00fec0c134" width="400"/>
</p>

# PCB Design
<p align="center">
  <img src="https://github.com/user-attachments/assets/c1592424-59ad-46cc-b766-d61c94f8a6c7" width="400"/>
</p>

# Final PCB
<p align="center">
  <img src="https://github.com/user-attachments/assets/e824335f-8a58-4700-8a8c-0ff261a70ca0" width="400"/>
</p>

# Group Members
- Kumarasinghe M.N.
- Wedamestrige A.N.
- Ranathunga R.J.K.O.H.
- Himasara W.V.M.J.





