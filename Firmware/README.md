# Firmware for F450 Quadcopter
This folder contains all files and instructions related to the flight controller firmware for the F450 quadcopter using the FlySky FS-i6 radio.

## Contents
setup.md – Step-by-step instructions to flash the Pixhawk 2.4.8 with ArduCopter firmware.
- **parameters/**– Folder containing pre-configured parameter files for the quadcopter.
  - `quad_f450.param` – Recommended configuration settings for flight stability, PID tuning, and radio calibration.

## Firmware Used

- **ArduPilot / ArduCopter** (open-source)
- Official GitHub repository: [https://github.com/ArduPilot/ardupilot](https://github.com/ArduPilot/ardupilot)
- Compatible with Pixhawk 2.4.8 flight controller.

## Notes

- Follow `setup.md` carefully before attempting first flight.
- Parameter files are a **starting point**; actual tuning may be required based on props, battery, and payload.
- This folder is designed to make firmware setup **easy, organized, and teacher-friendly**.
