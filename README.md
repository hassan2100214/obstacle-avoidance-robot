# obstacle-avoidance-robot
Simple Arduino code for a 2-wheel robot with obstacle avoidance. Control robot movement using infrared sensors. Customize pins, speeds, and behavior.
# Obstacle Avoidance Two-Wheel Robot Arduino Code

This repository contains a simple Arduino program designed for a two-wheel robot with obstacle avoidance capabilities. The code is intended to be used with an Arduino microcontroller and motor driver circuitry to control the movement of the robot and avoid obstacles in its path.

## Features

- The code defines constants for pins and speeds, making it easy to configure and adapt to different hardware setups.
- It utilizes infrared sensors to detect obstacles on both the left and right sides of the robot.
- The robot can perform the following movements:
  - Move forward
  - Move backward
  - Turn left
  - Turn right
  - Stop

## Usage

1. Set up your Arduino hardware and connect the motor driver and infrared sensors to the specified pins as defined in the code.
2. Upload the provided code onto your Arduino board using the Arduino IDE or another compatible software.
3. The robot will continuously read sensor values and make decisions based on the detected obstacles.
4. If no obstacles are detected on either side, the robot moves forward.
5. If an obstacle is detected on the right side only, the robot turns left to avoid it.
6. If an obstacle is detected on the left side only, the robot turns right to avoid it.
7. If obstacles are detected on both sides, the robot stops to prevent collisions.

## Customization

The code can be customized to fit your specific robot hardware and requirements:
- Adjust motor pin assignments and sensor pin assignments to match your hardware connections.
- Modify the speed values to control the robot's movement speed.
- Customize the behavior based on sensor readings to implement different obstacle avoidance strategies.



## Credits

This code was developed by Hassan Abdul-Razeq and can be found in its original form on GitHub 
