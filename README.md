# Obstacle-Avoiding-Car
An Arduino UNO-based autonomous robot car that uses an HC-SR04 ultrasonic sensor to detect obstacles and an L298N motor driver to control DC motors and avoid collisions automatically.
* Obstacle Avoidance Robot Car

- Project Overview

-The Obstacle Avoidance Robot Car is an autonomous robotic vehicle that detects obstacles in its path and automatically changes direction to avoid collisions.

-This project uses Arduino UNO, an HC-SR04 Ultrasonic Sensor, and an L298N Motor Driver to achieve automatic navigation.

- Project Objectives

* To detect obstacles automatically.
* To avoid collisions with objects.
* To control DC motors using Arduino.
* To develop a basic autonomous robot.
* To understand sensor-based robotic systems.

-Components Used

1	Arduino UNO	
2	HC-SR04 Ultrasonic Sensor	
3	L298N Motor Driver	
4	DC Gear Motors	
5	Robot Car Chassis	
6	Wheels	
7	Battery	
8	Jumper Wires
9	Switch	

-Working Principle

1. The HC-SR04 ultrasonic sensor detects obstacles in front of the car.
2. The sensor sends ultrasonic waves.
3. The reflected waves are received by the sensor.
4. Arduino calculates the distance of the obstacle.
5. If the distance is greater than 20 cm, the car moves forward.
6. If an obstacle is detected within 20 cm, the car stops.
7. The car moves backward and turns right.
8. The process repeats automatically.

-Pin Connections

HC-SR04 Ultrasonic Sensor

Sensor Pin	Arduino UNO
VCC	5V
GND	GND
TRIG	D12
ECHO	D13

L298N Motor Driver

L298N Pin	Arduino UNO
ENA	D5
IN1	D8
IN2	D9
IN3	D10
IN4	D11
ENB	D6
GND	GND

-Software Used

* Arduino IDE
* Embedded C/C++
* Arduino UNO

- Working Algorithm

1. Start the robot.
2. Initialize the ultrasonic sensor and motor driver.
3. Measure the distance.
4. Check whether an obstacle is detected.
5. If the path is clear, move forward.
6. Otherwise, stop and move backward.
7. Turn right to avoid the obstacle.
8. Repeat the process.

-Features

* Automatic obstacle detection.
* Autonomous movement.
* Collision avoidance.
* Low-cost robotic system.
* Simple hardware implementation.

-Project Images

Add your actual project photographs here.

* Front View
* Side View
* Top View
* Working Demonstration

-Future Scope

* ESP32 Wi-Fi connectivity.
* Mobile application control.
* Camera-based object detection.
* AI-based navigation.
* 360-degree obstacle detection.

-Applications

* Autonomous robotics.
* Educational robotics projects.
* Industrial automation research.
* Smart robotic vehicles.
* Robotics learning and experimentation.

-Author

Aniket Shelake

Robotics and Artificial Intelligence Student

-Conclusion

This project demonstrates the basic concept of autonomous robotics using ultrasonic sensing and motor control. It provides practical knowledge of Arduino programming, sensors, motor drivers, and robotic navigation.