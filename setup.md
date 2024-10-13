
# General Setup for Samsung Devices

This document provides a general guide for setting up Samsung devices, including enabling developer options, setting up ADB, and managing system apps.

## Steps for Initial Setup

### 1. **Enable Developer Options**:
   - Go to **Settings > About Phone**.
   - Tap **Build Number** seven times to enable Developer Options.

### 2. **Enable USB Debugging**:
   - Open **Settings > Developer Options**.
   - Enable **USB Debugging** to allow ADB access.

### 3. **Install ADB on Your Computer**:
   - Follow the instructions in the main `README.md` to install ADB on your system.

### 4. **Connecting the Device**:
   - Use a USB cable to connect the Samsung device to your computer.

## Useful Configurations

- **Disabling Bloatware**: Use the provided ADB commands in `adb_commands.md` to disable unnecessary apps.
- **Custom ROMs**: If you plan on installing a custom ROM, ensure you unlock the bootloader and back up important data first.

## Backup and Restore
It's always a good idea to back up your device before making significant changes to system apps.

