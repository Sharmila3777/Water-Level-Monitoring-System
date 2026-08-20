# Water Level Monitoring and Detection System

## Overview

This project is an Arduino-based Water Level Monitoring and Detection System. 
It measures the water level using an analog water level sensor and displays 
the water level percentage on an I2C LCD.

## Features

- Real-time water level monitoring
- Water level displayed as a percentage
- I2C LCD display
- Serial Monitor output
- Sensor value calibration
- Water level detection

## Components Used

- Arduino board
- Water level sensor
- 16x2 I2C LCD
- Buzzer
- Connecting wires
- Breadboard/trainer kit

## Working

1. The water level sensor produces an analog value.
2. Arduino reads the sensor value through analog pin A0.
3. The sensor value is limited between the minimum and maximum calibration values.
4. The value is converted into a percentage from 0% to 100%.
5. The water level percentage is displayed on the LCD.
6. Sensor readings and water level are also displayed on the Serial Monitor.

## Programming

- Language: C/C++ (Arduino)
- IDE: Arduino IDE
- Library: LiquidCrystal_I2C

## Project Output

The system continuously monitors the water level and displays the 
corresponding percentage on the LCD and Serial Monitor.

## Project Images

### Hardware Setup
Add the hardware setup image here.

### Circuit Diagram
Add the circuit diagram here.

### Serial Monitor Output
Add the Serial Monitor screenshot here.
