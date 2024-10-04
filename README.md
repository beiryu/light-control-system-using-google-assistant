# Light Control System Using Google Assistant

## Introduction

This project implements a home automation system for controlling lights using Google Assistant. It's part of a larger smart home concept that can involve the control and automation of lighting, heating, ventilation, air conditioning, security, and home appliances.

## System Architecture

The system consists of the following components:

- Arduino UNO
- ESP8266 WiFi Module
- Relay Board
- Google Assistant
- Arduino IDE

The controlling device connects to the ESP8266 WiFi module through a hotspot. The ESP8266 communicates with the Arduino microcontroller, which sends commands to the relay board. The relay board acts as a switch in the circuit, controlling the connected appliances.

## Features

- Remote control of lights via Google Assistant
- WiFi connectivity for IoT functionality
- Expandable to control multiple appliances

## Hardware Requirements

- Arduino UNO board
- ESP8266 WiFi Module
- Relay Board
- Breadboard
- Connecting wires

## Software Requirements

- Arduino IDE
- Google Assistant

## Setup and Installation

1. Connect the ESP8266 to the Arduino UNO (wiring diagram to be added)
2. Set up the relay board connections
3. Install the Arduino IDE
4. Upload the provided code to the Arduino
5. Configure Google Assistant to work with your setup

## Usage

Once set up, you can control your lights using voice commands through Google Assistant. For example:

- "Hey Google, turn on the living room lights"
- "OK Google, dim the bedroom lights"

## State Machine

The project implements a state machine for the local server. (Add more details or a diagram of the state machine)

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your changes.

## License

(Add appropriate license information)

## Contact

(Add your contact information or where to direct questions)
