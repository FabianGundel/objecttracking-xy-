# Dual ToF Object Tracking

A simple object tracking system using two Time-of-Flight distance sensors and a servo motor. The sensors are mounted side-by-side on a rotating platform. By comparing both distance measurements, the system determines whether an object is left or right of center and rotates toward it.

A PD control loop adjusts the servo’s angular velocity, enabling smooth and stable tracking of moving objects in real time.

## Hardware
- Arduino
- 2× ToF sensors (e.g. VL53L0X)
- Servo motor
- Rotating sensor mount

## Concepts
- sensor fusion  
- feedback control  
- real-time embedded systems