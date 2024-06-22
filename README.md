# Bluetooth Controlled Car with Arduino

![image](https://github.com/Deepcoder2905/Bluetooth-Controlled-Car/assets/148648766/e5b4c671-8be0-4423-9823-8f3061f31b6c)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Components](#components)
- [Circuit Diagram](#circuit-diagram)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
This project demonstrates a simple Bluetooth-controlled car using an Arduino. The car can be controlled remotely via a smartphone app, allowing for forward, backward, left, and right movements. The code for this project is written in C++ and developed using the Arduino IDE.

## Features
- Bluetooth remote control using a smartphone
- Simple and intuitive control interface
- Easily customizable and extendable

## Components
- Arduino Uno 
- L298N Motor Driver
- HC-05 Bluetooth Module
- DC Motors X 4
- Chassis for the car
- Wheels
- Power supply 
- Connecting wires
- Breadboard 

## Circuit Diagram
![image](https://github.com/Deepcoder2905/Bluetooth-Controlled-Car/assets/148648766/5ffe9f80-376c-41ae-9238-1d913906f026)


## Installation
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/bluetooth-controlled-car.git
   cd bluetooth-controlled-car# Bluetooth-Controlled-Car

2.**Upload the Arduino Code**
* Open the `bluetooth_car.ino` file in the Arduino IDE.
* Connect your Arduino to your computer.
* Select the correct board and port from the Tools menu.
* Upload the code to the Arduino.

3. **Assemble the Hardware**
* Follow the circuit diagram to connect the components.
*  Ensure all connections are secure.


4. **Install the Bluetooth Control App**
* Download and install a Bluetooth terminal app on your smartphone (e.g., Serial Bluetooth Terminal).

## Usage

### Pair the Bluetooth Module
1. Turn on the car and pair your smartphone with the HC-05 Bluetooth module (default password is 1234 or 0000).

### Control the Car
1. Open the Bluetooth terminal app and connect to the HC-05 module.
2. Use the following commands to control the car:
   - `F` - Move forward
   - `B` - Move backward
   - `L` - Turn left
   - `R` - Turn right
   - `S` - Stop



## Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository.**
   
2. **Create a new branch (`git checkout -b feature-branch`).**
   
3. **Commit your changes (`git commit -am 'Add new feature'`).**
   
4. **Push to the branch (`git push origin feature-branch`).**
   
5. **Create a new Pull Request.**
   
