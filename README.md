# ESP32-Accel-Control-Motor
POC project where you can control the movement of a motor using data from an accelerometer.

This is a sub-project for me, but I thought I'd publish it to keep track of it. The goal of this project is to control a motor's direction and rotation distance, based upon acceleration data. For example, if I move the accelerometer forward very quickly, I'd like to turn the motor very quickly clockwise to a set end position. If I move it backwards, I'd like to turn the motor very quickly counter-clockwise to a set end position.

In this version, I think I'd like to average input from the accelerometer to smooth motor movements and not shift the motor position erraticly.

Additionally, I'd like to keep track of motor position and change motor position dynamically using mathematic operations.

I don't want to get too far in the weeds with this version, since I'll be working on a separate 4-motor version with multiple accelerometers and inputs. A potential use case for this code could be robotics, such as robotic arms or human assistance devices.
