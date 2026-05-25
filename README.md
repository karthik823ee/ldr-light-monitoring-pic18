# Automatic Street Light System using PIC18F452 and LDR

## Overview
An automatic lighting control system built around the PIC18F452 microcontroller and an 
LDR sensor. The system continuously monitors ambient light intensity and controls an LED 
(representing a streetlight) without any manual intervention — turning it ON in darkness 
and OFF in daylight. Demonstrates energy-efficient automatic control using embedded systems.

## Objectives
- Read analog light intensity via ADC input on the PIC18F452
- Implement threshold-based automatic ON/OFF control logic
- Simulate a real-world streetlight automation system

## Tools & Technologies
- **Microcontroller:** PIC18F452
- **Sensor:** LDR (Light Dependent Resistor)
- **Concepts:** ADC, Sensor Interfacing, Threshold Logic, Embedded C
- **Application Domain:** Energy-efficient automatic lighting

## How It Works
The LDR changes resistance based on ambient light. This produces a varying voltage 
fed into the ADC pin of the PIC18F452. The microcontroller digitises this value and 
compares it to a programmed threshold:
- **Below threshold (dark):** LED turns ON automatically
- **Above threshold (bright):** LED turns OFF automatically

This mimics how real streetlights operate — no human input required.

## Results
- LED responded correctly and consistently to light/dark transitions
- ADC readings varied proportionally with ambient light changes
- System demonstrated reliable automatic switching behaviour

## What I Learned
- ADC configuration and sensor interfacing on PIC18F452
- Threshold-based decision logic in embedded C
- Practical understanding of how automation replaces manual switching

>[MPMC-course project.pdf](https://github.com/user-attachments/files/28211423/MPMC-course.project.pdf)
 📁 Source code, circuit diagram, and hardware photos available in the project report.
