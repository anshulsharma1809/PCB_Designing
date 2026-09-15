# PCB Design Assignment – ESP32 + LoRa

## About the Project

This repository contains my PCB design work sample prepared for the Embedded Systems / PCB Design internship at Illumix LED Lighting Pvt. Ltd.

The concept is based on an ESP32 + LoRa sensor interface board, with supporting interfaces for a DHT11 sensor and I2C OLED display.

## Objective

The objective of this work sample is to demonstrate my basic understanding of:

- PCB schematic planning
- Component selection and footprints
- Component placement
- PCB routing
- Power and ground considerations
- SPI and I2C interfaces
- Design Rule Checking (DRC)
- Basic KiCad workflow

## Hardware Concept

- ESP32 microcontroller
- SX1278 LoRa module
- DHT11 temperature/humidity sensor
- I2C OLED display
- Status LED
- Resistor
- 5V input with 3.3V logic considerations

## Interfaces

| Interface | Purpose |
|---|---|
| SPI | ESP32 ↔ LoRa |
| I2C | ESP32 ↔ OLED |
| GPIO | DHT11 sensor |
| GPIO | Status LED |

## My Current Skill Level

I have basic knowledge of PCB designing using KiCad and have academic exposure to ESP32, LoRa and Arduino through my B.Tech projects.

This is a learning-level PCB design work sample and has not been represented as a production-tested or physically fabricated PCB.

## Learning Goal

Through this internship, I want to strengthen both my practical PCB-design skills and my embedded systems skills, developing an end-to-end understanding from circuit design and PCB layout to microcontroller interfacing, firmware and hardware debugging.

I am eager to learn professional PCB design practices and gain hands-on experience under industry guidance.

## Files

- `Illumix_PCB_Design_Assignment_Anshul.pdf` – Complete assignment
- `01_conceptual_schematic.png` – Schematic concept
- `02_pcb_layout_concept.png` – PCB layout concept
