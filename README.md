# Let-the-obstacles-get-avoid
A robotic car which avoids the obstacles and hurdles on it`s way.

# Obstacle Avoidance Robot
This project is a simple obstacle avoidance robot built using an Arduino Uno and an HC-SR04 ultrasonic sensor. The main objective was to understand how a robot can detect obstacles and make movement decisions without any manual control.
Instead of following a fixed path, the robot continuously checks the distance in front of it. Whenever it detects an obstacle within a certain range, it stops, changes its direction, and continues moving once the path is clear.
This project was built as a learning project to gain practical experience with Arduino programming, sensors, motor drivers, and basic robotics.

## Hardware components Used:
* Arduino Uno
* HC-SR04 Ultrasonic Sensor
* Servo motor
* L298N Motor Driver
* Motors
* Wheels
* Battery Pack
* Jumper Wires

## How It Works
The ultrasonic sensor continuously measures the distance in front of the robot.
* If there is enough space, the robot keeps moving forward.
* When an obstacle is detected, the motors stop.
* The robot checks left and right and changes its direction accordingly.
* After finding a clear path, it resumes moving forward.
This cycle repeats continuously, allowing the robot to navigate around obstacles without any manual involvement.

## Circuit
The wiring is based on the following components:
* Ultrasonic sensor is connected to the Arduino for distance measurement.
* Servo motor is connected to Arduino for the left right movement.
* L298N motor driver used for communication between the output components and microprocessor.
* Battery pack used as the power source.

## Running the Project
1. Open the code file in the Arduino IDE.
2. Select the correct board and COM port.
3. Upload the program to the Arduino Uno.
4. Power the robot using the battery pack.

## What I Learned
Working on this project gave me practical experience with both hardware and software aspects of robotics. Some of the key things I learned includes:
- Interfacing an ultrasonic sensor with Arduino.
- Controlling DC motors using the L298N motor driver.
- Writing Arduino code based on how sensor reacts.
- Understanding how autonomous robots behaves and responds to the surroundings.
- Debugging hardware connections and solving the code errors.

## Future Improvements
Some ideas that can be added later:
* Bluetooth or Wi-Fi control
* OLED display for distance information
* Better obstacle detection algorithm
* Implementing a smarter path-planning algorithm so it could detect the obstacle as well as move on a defined path.


## ~Princy Turkhiya
This project is part of my journey of being a Robotics Engineer. 
