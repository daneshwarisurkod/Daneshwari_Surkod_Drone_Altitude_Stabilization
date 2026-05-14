# Daneshwari_Surkod_Drone_Altitude_Stabilization
# Drone Altitude Stabilization using PID Control 

## Project Overview
This project focuses on designing a Drone Altitude Stabilization System using MATLAB Simulink and a PID Controller. The system maintains stable drone altitude even under external disturbances such as wind.

The drone dynamics are modeled using a transfer function and controlled using a closed-loop feedback system.

---

## Objectives
- Maintain stable altitude
- Reduce overshoot
- Achieve faster settling time
- Minimize steady-state error
- Handle wind disturbances effectively
- Improve system stability

---

## System Transfer Function

G(s) = 1 / (s² + 2s + 5)

---

## Working Principle

The system uses a closed-loop feedback mechanism:

1. Desired altitude is provided as reference input
2. Error is calculated between desired and actual altitude
3. PID controller generates corrective control action
4. Drone plant responds to the control signal
5. Feedback continuously stabilizes the system

---

## Wind Disturbance Handling

A wind disturbance input is introduced to simulate external environmental effects on the drone.

The PID controller compensates for this disturbance and restores the altitude to the desired level.

---

## Aerospace Dashboard Features

The project includes a real-time aerospace-style dashboard containing:

- Altimeter
- Artificial Horizon
- Climb Rate Indicator
- Real-time response graph
- Digital altitude display

These features improve visualization and monitoring of drone behavior.

---

## Results Achieved

- Stable closed-loop response
- Disturbance rejection achieved
- Reduced oscillations
- Improved settling performance
- Real-time monitoring implemented

---

## Tools Used

- MATLAB
- Simulink
- Simulink Dashboard
- Aerospace Blockset

---

## Additional Creative Features

Beyond the required implementation, additional aerospace visualization instruments were added to improve interaction and simulation presentation quality.

---

## Conclusion

The project successfully demonstrates a PID-based drone altitude stabilization system capable of maintaining stable altitude under disturbances while providing real-time aerospace dashboard visualization.
