# Voron 2.4 R1 FYSETC Spider v2.2 Kit
# Klipper Firmware & Configuration

FYSETC Voron 2.4 R1 Kit with Spider v2.2 Board - Sensorless Homing, Bed Mesh Calibration, Tuned Stepper Drivers, and more!

#### https://print3d.world is proud to announce a sponsorship with FYSETC 3D Printing! We are working with FYSETC to review and develop high quality, and high speed firmware for the Voron kits offered by their shop.

NOTE: We were unable to flash the firmware to our Spider v2.2 board with traditional method. I had to first upload the 64kib bootloader, and then upload the firmware without overwriting the bootloader. This allowed us to get the board working simply and efficiently after fighting with it for several hours. The files for the bootloader and firmware are here also, look on our blog for directions on how to upload the firmware if yours is not working either!

Sensorless Homing may require further tuning for your specific printer!

<<<<<<< HEAD

# Updates 3/24/2023
+ Purge bucket disabled in this revision
+ Klicky Probe installed and working for Z Endstop, Probe, instead of the endstop
switch and/or the inductive probe.
+ Other minor fixes, left all configuration change dates so you can still use the
old  purge settings if you don't wish to upgrade to Klicky
+ We will make it easier to enable/disable options as we have free time!


# Feature Set 2/7/2023
=======
# Feature Set 2/12/2023
>>>>>>> refs/remotes/origin/main

+ Sensorless Homing
+ 64 Microsteps
+ Bed Mesh Calibration with Probe instead of Z-Endstop
+ Higher Current Stepper Settings
+ PID Calibration for 120v Silicone Heated Bed
+ Sensorless Homing Macros, Start G-Codes and more adapted from RatRig
+ Purge Bucket Mod now Installed
+ Fully tuned TMC Stepper Drivers for the FYSETC TMC 2209 V3.1 with TMC Performance spreadsheet. Currently working on X driver to see if it helps with my undervolt alarms (they haven't come back once yet!)
+ Updated Crowsnest and other items, setup a webcam on it.


### To-Do List
- [ ] Implement Klicky Probe
- [ ] Ensure compatibility with R2 kit
- [ ] Clean Up macros and remove RatRig config
- [ ] Step-by-Step Firmware & Bootloader Install Guide
