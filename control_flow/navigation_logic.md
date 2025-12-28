# Navigation Logic

The navigation logic of the drone is based on **GPS-guided autonomous control**
implemented through the flight controller firmware.

## Core Navigation Flow

1. GPS lock is obtained before arming
2. Home position is recorded at takeoff
3. Waypoints are executed sequentially
4. Altitude is maintained using GPS + barometer data
5. Orientation and stabilization handled by IMU

## Waypoint Execution

- Waypoints are predefined in Mission Planner
- Each waypoint includes position and altitude
- Drone transitions smoothly between waypoints

The navigation system relies on **preplanned missions**, not real-time path planning.
