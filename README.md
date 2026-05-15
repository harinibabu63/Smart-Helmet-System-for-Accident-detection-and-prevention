# Smart-Helmet-System-for-Accident-detection-and-prevention


This project is an embedded safety system designed to reduce two-wheeler accidents by checking helmet usage, alcohol detection, overload condition, rash driving, and accident impact before or during vehicle operation.

The system uses multiple sensors connected to a PIC microcontroller. If the rider is not wearing a helmet or alcohol is detected, the bike ignition is prevented. If an accident occurs, the system detects the impact and sends the accident location through GPS for emergency response.

## Key Features

- Helmet detection using IR sensor
- Alcohol detection using gas sensor
- Accident detection using vibration sensor
- Rash driving detection using MEMS sensor
- Load monitoring using load sensor
- GPS-based accident location tracking
- ZigBee-based wireless communication
- PIC microcontroller-based system control

## Hardware Used

- PIC16F84A Microcontroller
- [IR Sensor](https://github.com/harinibabu63/Smart-Helmet-System-for-Accident-detection-and-prevention/blob/main/IR%20SENSOR.jpg)
- [Gas Sensor](https://github.com/harinibabu63/Smart-Helmet-System-for-Accident-detection-and-prevention/blob/main/Gas%20sensor_%20smart%20helmet%20Hardware%20setup.jpg)
- [Vibration Sensor](https://github.com/harinibabu63/Smart-Helmet-System-for-Accident-detection-and-prevention/blob/main/vibration%20sensor.jpg)
- [MEMS Sensor](https://github.com/harinibabu63/Smart-Helmet-System-for-Accident-detection-and-prevention/blob/main/MEMS%20sensor.jpg)
- [Load Sensor](https://github.com/harinibabu63/Smart-Helmet-System-for-Accident-detection-and-prevention/blob/main/load%20sensor.jpg)
- GPS Module
- [ZigBee Module](https://github.com/harinibabu63/Smart-Helmet-System-for-Accident-detection-and-prevention/blob/main/Zigbee.jpg)
- LCD Display
- Power Supply Circuit

## How It Works

1. The IR sensor checks whether the rider is wearing the helmet.
2. The gas sensor detects alcohol content in the rider’s breath.
3. If helmet usage and alcohol conditions are safe, the bike can start.
4. The vibration sensor detects accident impact.
5. The MEMS sensor monitors rash driving or abnormal handle movement.
6. The GPS module sends the accident location during an emergency.

## Project Images

- [Block Diagram](https://github.com/harinibabu63/Smart-Helmet-System-for-Accident-detection-and-prevention/blob/main/proposed%20Block%20Diagram%20of%20smart%20Helmet%20System.png)
- [Proposed Block Diagram](https://github.com/harinibabu63/Smart-Helmet-System-for-Accident-detection-and-prevention/blob/main/Proposed%20Block%20Diagram.png)
- [Output Display](https://github.com/harinibabu63/Smart-Helmet-System-for-Accident-detection-and-prevention/blob/main/Output%20display_%20Smart%20Helmet%20system%20for%20Accident%20Detection.jpg)

## What I Learned

- Sensor integration with microcontrollers
- Embedded system design for safety applications
- Accident detection and alert logic
- GPS-based location tracking
- Wireless communication using ZigBee
- Real-world hardware system planning
