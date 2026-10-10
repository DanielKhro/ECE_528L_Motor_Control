# ECE 528/L - Robotics and Embedded Systems with Lab
**CSU Northridge**

**Department of Electrical and Computer Engineering**

## Motor Control Lab

# Overview 
This lab uses the TI MSP432 to control the motors and servos on the TI-RSLK MAX robot. Timer_A generates pulse width modulation (PWM) signals, allowing the ability to adjust motor speed and servo position. The lab also configures the front bumper switches as edge-triggered GPIO interrupts so the robot can respond when it detects a collision. A predefined drive pattern is programmed for that response, then use an oscilloscope to verify the PWM signals and observe switch bounce. This ultimately demonstrates how timer outputs and interrupts support motor control and event-driven behavior.

# Components Used
(1) MSP432 LaunchPad
(1) USB A to microUSB Cable
(1) TI-RSLK MAX Chassis
(2) Bumper Switches
(2) HS-485HB Servo
(1) Oscilloscope
(2) Oscilloscope Probes

# Analysis and Results:
The robot began to properly move forward until a collision was detected by the bumper switches mounted in the front of the robot chassis. It then continued to roatate and operate in another direction. The process would then continue to operate until the next collision.

Servo 0 Degrees:
<img width="640" height="480" alt="ECE528L_Lab1_servo_0_degrees" src="https://github.com/user-attachments/assets/1bd41567-28d3-4e1e-82e6-caf3c7e3e09e" />

Servo 0 Degrees PW:
<img width="640" height="480" alt="ECE528L_Lab1_servo_0_degrees_pulse_width" src="https://github.com/user-attachments/assets/b69a4394-7f22-4adc-bdbb-ad4cd138ea2d" />

Servo 180 Degrees:
<img width="640" height="480" alt="ECE528L_lab1_servo_180_degrees" src="https://github.com/user-attachments/assets/ee3ab128-1435-4cd3-89ae-d580d47d551d" />

Servo 180 Degrees PW:
<img width="640" height="480" alt="ECE528L_Lab1_servo_180_degrees_pulse_width" src="https://github.com/user-attachments/assets/154a4108-49e8-4046-819c-9566d5a9af62" />

Bumper Scope Shot:
<img width="640" height="480" alt="ECE528L_Lab1_bumper_scope_shot" src="https://github.com/user-attachments/assets/09e13492-e610-4374-b42f-87018397ade8" />


# Known Issues or Limitations
No limitations or issues were discoved while performing the lab and its tasks. All tasks were met successfully.

# References
MSP432P4xx SimpleLink Microcontrollers Technical Reference Manual

TI DRV8838 Motor Driver Datasheet

HS-485HB Servo-Stock Rotation Datasheet
