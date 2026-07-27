# Ultrasonic Automatic Car Barrier

This project is an automatic car barrier made using an Arduino Uno, an ultrasonic sensor, a servo motor, and an LED.

When the ultrasonic sensor detects a car or object within **10 cm**, the servo motor lifts the barrier and the LED turns on. When the object moves away, the servo returns the barrier to its original position and the LED turns off.

## Components

- Arduino Uno
- HC-SR04 ultrasonic sensor
- Servo motor
- LED
- 220 Ω or 330 Ω resistor
- Breadboard
- Jumper wires

## Connections

| Component | Arduino Pin |
|---|---|
| Ultrasonic sensor TRIG | D6 |
| Ultrasonic sensor ECHO | D9 |
| Servo signal | D3 |
| LED | D2 |
| Ultrasonic sensor VCC | 5V |
| Servo VCC | 5V |
| All GND connections | GND |

## How It Works

1. The ultrasonic sensor measures the distance in front of the barrier.
2. When a car or object is detected within 10 cm, the servo moves from 0° to 90°.
3. The LED turns on while the barrier is open.
4. When the object moves farther than 10 cm, the servo returns to 0°.
5. The LED turns off when the barrier closes.

## Tinkercad Circuit


<img width="1528" height="635" alt="Smashing Snicket-Turing" src="https://github.com/user-attachments/assets/c9491a8e-e335-4947-9401-b68ebcf74a82" />


## Real-Life Project


<img width="1496" height="756" alt="WhatsApp Image 2026-07-27 at 10 25 01 PM" src="https://github.com/user-attachments/assets/95842884-22ef-45a7-ad94-fd3198fbfa5b" />


## Video

Add your project video link here:



https://github.com/user-attachments/assets/c5addc82-ded3-4dd3-b005-d824ce6267a2



## Author

**Faris Bahussain**
