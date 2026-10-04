# Software 26-27

This folder contains the 2026-27 software team's work for the LHNT prosthetic arm project, separate from previous years' code elsewhere in this repo.

## Project Scope
Software for an EEG/EMG-controlled prosthetic arm — motor control, sensor data reading, EMG signal integration, and (eventually) 3D visualization of the hand.

## Structure
- `firmware/` - Motor control + UDP command listener (ESP32)
- `signal-processing/` - EMG signal integration & classification (coming soon)
- `visualization/` - 3D visualization of hand/arm position (coming soon)

## Hardware Reference
- **Microcontroller:** ESP32 (ESP32C6)
- **Motors:** N20 DC motors w/ encoders, 600 RPM
- **Power:** LiPo batteries

## Links
- Notion: [https://app.notion.com/p/LHNT-PROSTHETICS-2026-2027-3db688da0d5e807dbfbff9137537d9d8]
- Linear: [https://linear.app/lhnt-prosthetics/project/software-e02d549749c7/overview]
