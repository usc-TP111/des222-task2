# Study Buddy (Pomogotchi)

## Purpose
A desk device, designed to assist students with focusing on study and work.

![Screenshot of UltiMaker Cura slicer with the front side of the device.](image.png)

## Function
The core function is a combination of the 'pomodoro' technique and the 'Tamagotchi' concept. It is also equipped with various sensors (temperature, humidity, air quality), inputs (SD card, buttons, web connection), outputs (LED display, speaker), and app integrations (e.g. calendar, Spotify), all aimed at creating a better, studying environment.

## Technology
The whole device is controlled by an ESP32-S3 Dev Board. This controller also hosts a website, which acts as an interface for configuration.
The sensors include DHT22 Module for temperature and humidity, as well as the Air Quality Sensor ENS160.
For sound, it uses an enclosed speaker of 8Ω/5W, paired with an I2S 3W Class D Amplifier breakout board (MAX98357A).
The display is a Waveshare 2.4inch LCD Mini Display Module 65K RGB Colors 240×320 Resolution.
The controls are basic tactile buttons, as well as the aforementioned web interface.
All the data are saved on an SD Card, access through an SD Card Module.
The whole device is then powered by a LiPo battery (3.7V, 1100mAh), and cooled with an active cooler.