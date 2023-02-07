# Voron2.4-FYSETCSpider
FYSETC Voron 2.4 R1 Kit with Spider v2.2 Board - Sensorless Homing, Bed Mesh Calibration, Tuned Stepper Drivers, and more!

https://print3d.world is proud to announce a sponsorship with FYSETC 3D Printing! We are working with FYSETC to review and develop high quality, and high speed firmware for the Voron kits offered by their shop.

NOTE: We were unable to flash the firmware to our Spider v2.2 board with traditional method. I had to first upload the 64kib bootloader, and then upload the firmware without overwriting the bootloader. This allowed us to get the board working simply and efficiently after fighting with it for several hours. The files for the bootloader and firmware are here also, look on our blog for directions on how to upload the firmware if yours is not working either!

Sensorless Homing may require further tuning for your specific printer!

Options that are enabled here, not enabled in stock FYSETC configuration firmware:
[list]
[li]Sensorless Homing[/li]
[li]64 Microsteps[/li]
[li]Bed Mesh Calibration with Probe instead of Z-Endstop[/li]
[li]Higher Current Stepper Settings[/li]
[li]PID Calibration for 120v Silicone Heated Bed[/li]
[li]Sensorless Homing Macros, Start G-Codes and more adapted from RatRig[/li]
[/list]
