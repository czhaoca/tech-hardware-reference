
# ADB Commands for Samsung Devices

This file contains a list of useful ADB commands specifically for managing Samsung devices. You can use these commands to manage apps, system settings, and device configurations.

## Common ADB Commands

### 1. **List All Installed Packages**:
   ```bash
   adb shell pm list packages
   ```

### 2. **List Disabled Packages**:
   ```bash
   adb shell pm list packages -d
   ```

### 3. **Disable a Package**:
   ```bash
   adb shell pm disable-user --user 0 <package_name>
   ```

### 4. **Uninstall a Package**:
   ```bash
   adb shell pm uninstall --user 0 <package_name>
   ```

### 5. **Re-enable a Disabled Package**:
   ```bash
   adb shell pm enable <package_name>
   ```

## Notes
- Replace `<package_name>` with the actual package name of the app.
- Always be cautious when disabling or uninstalling system apps.
