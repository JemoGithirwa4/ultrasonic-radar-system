# Arduino Servo and Ultrasonic Sensor Project

## Description
This project demonstrates the use of a servo motor and an ultrasonic sensor with an Arduino. The servo motor rotates from 15 to 165 degrees and back, while the ultrasonic sensor measures the distance at each position.

## Video Demo  
Watch the project in action: [Demo Video on Google Drive](https://drive.google.com/file/d/1AbJ07L5LqTsaWs8NobULOagLe_9K4Cm3/view?usp=sharing)


## Components Used
- Arduino Board (e.g., Arduino Uno)
- Servo Motor
- Ultrasonic Sensor (e.g., HC-SR04)
- Jumper Wires
- Breadboard (optional)

## How to Use
1. Connect the servo motor and ultrasonic sensor to the Arduino according to the pin definitions in the code.
2. Upload the `sketch_mar15a.ino` file to your Arduino board using the Arduino IDE.
3. Open the Serial Monitor to view the angle and distance measurements.

## Code Explanation
- The code includes the Servo library to control the servo motor.
- The `setup()` function initializes the pins and starts serial communication.
- The `loop()` function rotates the servo motor and measures the distance using the ultrasonic sensor.
- The `calculateDistance()` function calculates the distance based on the time taken for the ultrasonic pulse to return.

## License
This project is open-source and can be modified and distributed freely.
