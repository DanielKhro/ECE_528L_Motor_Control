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

# Known Issues or Limitations
No limitations or issues were discoved while performing the lab and its tasks. All tasks were met successfully.

# References
MSP432P4xx SimpleLink Microcontrollers Technical Reference Manual

TI DRV8838 Motor Driver Datasheet

HS-485HB Servo-Stock Rotation Datasheet