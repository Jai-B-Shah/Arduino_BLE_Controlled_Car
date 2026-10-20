# Arduino BLE Controlled Obstacle Avoiding Car

This project is an autonomous, obstacle-avoiding car built around an Arduino ATMega328P. It uses IR, ultrasonic, and LDR sensors to sense its surroundings in real time and automatically steer around obstacles, while also supporting wireless Bluetooth master-slave control so a user can drive it remotely. A TFT LCD on the car gives a second, local mode of control and status display, alongside headlight and horn indicators for a more complete vehicle-like experience.

## Skills & Tools Demonstrated

- Embedded C programming on the Arduino IDE / ATMega328P platform
- Multi-sensor integration (ultrasonic, IR, LDR) for real-time distance sensing and decision-making
- Bluetooth wireless communication using a master-slave (HC-05/HC-06 style) architecture
- Motor driver interfacing and movement control (forward, reverse, turning) based on sensor input
- TFT LCD (SPFD5408) interfacing for local display and touchscreen-based control
- Circuit prototyping with breadboards, jumper wires, and a chassis/motor assembly
- Technical documentation and literature review of prior art in obstacle-avoidance robotics

## What Was Built

- An obstacle-avoiding car that continuously scans its path with ultrasonic, IR, and LDR sensors and reacts (stop, turn, reverse) when an obstacle crosses a set threshold distance
- Dual control modes: a Bluetooth link between a transmitter module (with the user) and a receiver module (on the car) for remote driving, and a TFT LCD on the car for local, direct control
- Supporting features: an LED headlight and a buzzer horn, driven through the same Arduino logic
- A project paper documenting the system design, a literature review of related patented obstacle-avoidance vehicles, component breakdown, working operation, and known limitations

## Repository Structure

- `Documentation/` - Project paper (abstract, literature review, components, working principle, limitations)
- `Images/` - Circuit connections, mobile Bluetooth control interface, TFT display, and TFT control screenshots

## Author

Jai B Shah, B.Tech VLSI Design and Technology, VIT Vellore
