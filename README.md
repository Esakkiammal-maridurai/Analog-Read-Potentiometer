# Analog Read – Potentiometer

## Description
This project uses an ESP32 to read the analog value from a potentiometer and display the value on the Serial Monitor every 500 milliseconds.

## Components Used
- ESP32
- Potentiometer
- Wokwi Simulator

## Connections
- Potentiometer GND → ESP32 GND
- Potentiometer SIG → GPIO 34
- Potentiometer VCC → ESP32 3V3

## Working
The ESP32 reads the potentiometer value using `analogRead()`.
The value is printed on the Serial Monitor every 500 ms.

## Wokwi Simulation
https://wokwi.com/projects/476209578809472001
