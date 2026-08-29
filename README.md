# Pomodoro Speaker

Portable Bluetooth speaker with an integrated Pomodoro timer, built using an ESP 32

The device combines a stereo bluetooth speaker with a dedicated display for focus sessions and music,
Pomodoro settings and device controls will also be accessible using a local web interface

## Planned Features

- Bluetooth stereo audio
- Pomodoro focus + break timer
- 240x320 TFT Display
- Physical control button
- Web-based controls
- Rechargeable LiPo battery (USB-C)
- Stereo sound

## Hardware

- ESP32
- 240x320 SPI TFT display
- PAM8403 stereo amplifier
- 2x 4 Ohm 3 Watt speakers
- 3.7 V 100 mAh liPo battery
- Charging/power module
- Black push button with white led ring
- I2S Stereo DAC
- Perfboards

## Software

### Firmware

- C++
- Arduino Framework
- Platformio

### Web Interface

- HTML
- CSS
- Javascript

## Project road map

- [ ] Initialize TFT Display
- [ ] Build Pomodoro Timer
- [ ] Add Physical button controls
- [ ] Once I2S arrive, integrate alongside stereo amplifiers
- [ ] Add Wi-Fi control API
- [ ] Build control website
- [ ] Connect battery power
- [ ] Design Closure
- [ ] Final Assembly

## Status:

Early Development