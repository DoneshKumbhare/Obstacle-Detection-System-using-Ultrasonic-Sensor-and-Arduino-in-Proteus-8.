# Obstacle-Detection-System-using-Ultrasonic-Sensor-and-Arduino-in-Proteus-8.
This project is an Obstacle Detection System designed and simulated using Proteus 8 Software and programmed through the Arduino IDE. The system uses an Ultrasonic Sensor to measure the distance of nearby obstacles
and display the distance dynamically on an LCD screen.When an obstacle comes within a certain distance (set using a potentiometer), the LED and buzzer are activated as visual and sound alerts.If there is no
obstacle detected, both the LED and buzzer remain off.

Components & Technologies Used
1. Arduino UNO – Main controller for the system
2. Ultrasonic Sensor (HC-SR04) – Detects distance to the obstacle
3. 16x2 LCD Display – Shows real-time distance readings
4. Potentiometer – Adjusts contrast and sensitivity
5. LED – Visual alert when an obstacle is detected
6. Buzzer – Sound alert when an obstacle is detected
7. Proteus 8 Professional – Circuit design and simulation software
8. Arduino IDE – Code development and uploading

How It Works

The ultrasonic sensor sends sound waves and measures the time it takes for them to bounce back after hitting an obstacle. The Arduino calculates the distance using the time difference.The LCD display continuously
shows the measured distance. If the measured distance is less than the set threshold, the LED turns on and the buzzer beeps. When no obstacle is detected (distance greater than threshold), both the LED and buzzer
stay off. The potentiometer can be used to adjust the contrast of the LCD and fine-tune the system’s response.
