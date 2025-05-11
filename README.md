# 🚧 Automatic Gate Control System with Ultrasonic Sensor

This Arduino project controls a gate using an ultrasonic sensor, servo motor, LEDs, and a piezo buzzer. The gate opens automatically when an object (like a person or car) is detected nearby and closes after a short delay.

## 🛠 Features

- Ultrasonic distance detection
- Automatic gate control using a servo motor
- Visual feedback using red (closed) and blue (open) LEDs
- Audible buzzer alert while the gate is open
- Auto-close after 5 seconds
- Software-controlled ground for additional flexibility

## 🔌 Hardware Required

- Arduino Uno or compatible board
- Ultrasonic Sensor (HC-SR04)
- Servo Motor (e.g., SG90)
- Red LED
- Blue LED
- 2x 220Ω resistors (for LEDs)
- Piezo Buzzer
- Jumper wires
- Breadboard

## 🖥 Pin Connections

| Component      | Arduino Pin |
|----------------|-------------|
| Ultrasonic Trig | D2          |
| Ultrasonic Echo | D3          |
| Red LED         | D4          |
| Blue LED        | D5          |
| Servo Motor     | D6 (PWM)    |
| Ground Pin 1    | D7 (LOW)    |
| Ground Pin 2    | D8 (LOW)    |
| Piezo Buzzer    | D12         |

## 🚀 Getting Started

1. Upload the code to your Arduino board.
2. Wire up the components as per the pin connections.
3. Power your Arduino and observe the behavior.
4. Place an object within 15 cm to trigger the gate.

## 📄 License

MIT License
