# Automated Classroom Environment Management System

An Arduino Mega-based smart classroom automation system developed during a hardware hackathon. The system improves classroom energy efficiency and comfort by automatically controlling lighting and ventilation based on environmental conditions.

---

## Features

- Automatic classroom light control using an LDR sensor
- Real-time temperature and humidity monitoring using DHT11
- Automatic fan activation when temperature exceeds threshold
- Energy-efficient classroom management
- Real-time environmental sensing

---

## Components Used

- Arduino Mega 2560
- DHT11 Temperature & Humidity Sensor
- LDR (Light Dependent Resistor)
- LEDs / Relay-based light simulation
- Fan / DC motor simulation
- Jumper wires
- Breadboard

---

## How It Works

### Smart Lighting System

The LDR sensor continuously measures ambient light intensity in the classroom.

- If natural light is sufficient:
  - Classroom lights remain OFF

- If natural light falls below a predefined threshold:
  - Classroom lights automatically turn ON

This helps reduce unnecessary power consumption while maintaining proper classroom visibility.

---

### Smart Ventilation System

The DHT11 sensor continuously monitors:

- Temperature
- Humidity

When the classroom temperature exceeds a set threshold value:

- Fans are automatically switched ON

Once the temperature returns to normal:

- Fans are switched OFF

This creates a simple automated climate-control system for classrooms.

---

## Applications

- Smart classrooms
- Energy-efficient buildings
- Automated room monitoring
- Basic IoT and embedded system projects

---

## Technologies Used

- Arduino IDE
- Embedded C/C++
- Sensor interfacing
- Automation logic

---

## Project Context

Developed as part of the Byte2Board Hardware Hackathon as a low-cost embedded solution for improving classroom management and energy efficiency.
