# Smart Distance Alert System using Arduino & Ultrasonic Sensor

This project is based on Arduino UNO and an ultrasonic sensor. It is designed to measure distance and trigger a buzzer if the measured distance is below a certain threshold.

## 🧰 Components Used:
- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- Buzzer
- Breadboard
- Jumper Wires

## ⚙️ How It Works:
The ultrasonic sensor sends out sound waves. When they hit an object, they bounce back and the sensor calculates the time taken to receive the echo. This data is used to determine the distance. If the distance is less than a defined safe limit (e.g., 10 cm), the buzzer activates.

## 📦 Installation:
1. Connect the components as shown in the circuit diagram.
2. Upload the Arduino code provided in the sketch.
3. Open the Serial Monitor to see the distance readings.

## 📄 License:
This project is open-source for educational and personal use.
