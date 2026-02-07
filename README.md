# PX4 SITL Maze Simulation (Gazebo Harmonic)

## Objective
To run PX4 SITL with an X500 drone inside a maze world and connect it to QGroundControl.

## System Setup
- OS: Ubuntu 22.04
- Simulator: Gazebo Harmonic
- Autopilot: PX4 SITL
- Vehicle: X500 (Depth camera model)

## Procedure Followed
1. PX4 firmware was built successfully.
2. Gazebo maze world was launched.
3. Drone spawned inside the environment.
4. QGroundControl was started for monitoring and control.

## Result
- Gazebo environment opened successfully.
- Drone model spawned correctly.
- MAVLink communication started.

## Issue Faced
QGroundControl connected, but sensor initialization failed.

Preflight errors observed:
- Accelerometer missing  
- Gyro missing  
- Barometer missing  
- Compass not detected  

Because of this, the vehicle could not arm or start a mission.

## Repository Contents
- Flight logs (.ulg)
- Terminal output screenshots
- Gazebo screenshots
- Screen recording of the run

## Notes
The issue may be related to missing simulation plugins or rendering limitations in the system.
