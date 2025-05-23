# AutomaticGateDemoKit

AutomaticGateDemoKit is an Arduino-based project that simulates an automatic gate system using an ultrasonic sensor, servo motor, LEDs, and a buzzer. This project demonstrates basic automation and safety concepts found in modern security or smart access systems.

🔩 Features
🚪 Automatic Gate Opening when an object (e.g., person or car) is detected within 50 cm

🔒 Auto-Close Delay: Gate closes after 5 seconds if no object is detected

🔴 Red LED: Indicates gate is closed

🔵 Blue LED: Indicates gate is open

🔊 Buzzer: Sounds when the gate is open (object detected)

🧰 Hardware Requirements
Arduino Uno (or compatible board)

HC-SR04 Ultrasonic Distance Sensor

Servo motor

2 LEDs (Red and Blue) with resistors

Buzzer

Jumper wires, breadboard

External power supply (if needed for servo)

🧠 How It Works
The ultrasonic sensor measures the distance to an object.

If an object is detected within 50 cm:

The servo motor opens the gate.

Blue LED and buzzer are activated.

If no object is detected for 5 seconds:

The servo closes the gate.

Red LED turns on.

Buzzer and blue LED turn off.