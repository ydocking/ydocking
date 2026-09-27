# About Me

- I'm a student of the Division of Electrical and Electronic Engineering.
- I focus on **embedded systems and control**: microcontroller firmware, motor and servo control, sensors, and serial / CAN communication.
- My favorites are C/C++.

## Projects

> Most of these repositories are private.

### MarineRobot — Underwater ROV
- Controls four thrusters from a Teensy, with slew-rate limiting on the ESC outputs
- Manual driving with a DJI DT7 transmitter (DBUS decoding) and pre-planned autonomous missions
- Onboard video recording with an ESP32-CAM
- MATLAB simulator with depth and heading hold (PID) and disturbances such as water current, cable drag and thruster failure

### Tanekon — CanSat Rover (Tanegashima Rocket Contest)
- Autonomous rover: waits in the capsule, deploys on a barometric trigger, then navigates to the goal
- GPS navigation, IMU-based tip-over detection and recovery, camera guidance by color detection
- RoboMaster M2006 motors over CAN with timer-interrupt PID control (Teensy / Spresense)

### Coin Counter with H8/3052F — Embedded Systems Course
- A webcam and OpenCV (HSV masking + Hough circle transform) count the coins on the PC
- The result is sent over serial (Win32 API, 9600 bps) to an H8/3052F
- The H8 drives a servo with ITU PWM (20 ms period) and makes it bow

### Raspberry Pi 4 Port
- Porting the microcontroller control code to a Raspberry Pi 4 in C++
- Thruster PWM with pigpio, motor control over Linux SocketCAN instead of an SPI CAN controller

## Programming Languages

<img src="https://skillicons.dev/icons?i=c,cpp,py" /> <img src="https://img.shields.io/badge/VHDL-1f425f?style=for-the-badge" height="48" alt="VHDL" /> <br /><br />

## Tools & Platforms

<img src="https://skillicons.dev/icons?i=arduino,raspberrypi,matlab,opencv,linux,git,github,vscode,visualstudio,docker,anaconda,blender,unity,discord" /> <br /><br />
