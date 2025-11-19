# TFT Screen, shutdown button, and a MAX98357A wiring reference

This repo helps as a reference to wire this components into a raspberry pi zero, but may work too in the RPI 2, RPI 3 and maybe the RPI 4.

The project uses the [fbcp-ili9341](https://github.com/juj/fbcp-ili9341) driver for the ILI9341 screen. Consequently, it will not work on a Raspberry Pi 5, which uses a different display driver.

The audio MAX98357A is Mono, if you need stereo 2 boards must be used, you need to check how to wire them.

The main purpose of this setup is get alive 80s small tv devices (for example a Casio TV-6500), where only a raspberry pi zero can fit.

![Main diagram](wiring.png)