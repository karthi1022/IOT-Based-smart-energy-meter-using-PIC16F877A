#  IoT Smart Energy Meter

An automated electrical parameter monitoring and protection device using PIC microcontroller integrated with cloud data logging.

## Hardware & Components
- Microcontroller: Microchip PIC16F877A
- Communication / IoT: ESP32
- Actuation: Relay module for automated circuit cutoff
- Sensing: Current Transformer (CT) and Voltage Sensor

## Tech Stack
- Firmware: Embedded C 
- Cloud Platform: ThingSpeak IoT platform
- Simulation: Proteus VSM

## Key Features
- Live tracking of voltage, current, and total power consumption.
- ThingSpeak cloud logging with real-time graphs and automated consumption alerts.
- Remote automated relay disconnect upon reaching load limit.
