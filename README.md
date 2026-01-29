# Line Follower Robot (LFR)

This project is an autonomous Line Follower Robot built using Arduino Nano, a 5-channel IR sensor array, and the TB6612FNG dual motor driver.  
The robot detects the line in real time and adjusts the motor speeds to follow the path smoothly.

## How it works
- IR sensors detect the line position (left / center / right)
- Arduino processes sensor readings and decides motion
- TB6612FNG controls both DC motors for turning and forward movement
- PID control is used for smoother and stable line following

## Components Used
- Arduino Nano
- TB6612FNG Motor Driver
- 5-Channel IR Sensor Array
- N20 DC Motors
- 2S Li-ion Battery Pack + Switch

## Repository Contents
Code → Arduino `.ino` source code
- **images/** → Robot photos, sensor setup, and output/demo images

Useful for robotics learning, embedded systems practice, and control applications.
