# Study Clock

A simple study desk clock made using an ESP32 and an OLED display.

The case also includes 2 pen holders to keep the desk organized.

## Features

- OLED time display
- ESP32 based
- Change mode from switch
- Buzzer for timer
- Compact desk design
- 2 built-in pen holders


## Bill Of Materials (BOM)

- ESP32
- OLED Display
- Cherry Switch
- Buzzer
- Jumper wires
- USB cable


## Wiring 

| OLED | ESP32 |
|------|--------|
| VCC  | 3.3V   |
| GND  | GND    |
| SDA  | GPIO 21 |
| SCL  | GPIO 22 |

Buzzer - GPIO 25

CHerry Switch - GPIO 32

## Setup

1. Connect the OLED, Buzzer and Cherry Switch to the ESP32
2. Upload the code using Arduino IDE
3. Power the ESP32

## About

I made this project to create a useful and clean desk accessory while learning more about ESP32 and OLED displays.

## Images

<img width="792" height="563" alt="schematic" src="https://github.com/user-attachments/assets/147ea246-4703-49e8-8c8d-3c3e78edfc46" />

