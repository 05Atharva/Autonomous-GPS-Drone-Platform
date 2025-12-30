# Failsafe Mechanisms

Failsafe behavior is a critical part of autonomous drone operation.

## Implemented Failsafe: Return to Launch (RTL)

- Triggered manually or via predefined safety conditions
- Drone returns to the recorded Home position using GPS
- Performs controlled descent and landing

## Purpose of RTL

- Prevents uncontrolled flight
- Reduces risk during signal loss
- Enables safe mission termination

Failsafe logic is handled by the flight controller firmware and configured through Mission Planner.
