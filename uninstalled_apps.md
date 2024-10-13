
# Samsung Apps to Uninstall or Disable

This file contains a list of Samsung-specific apps that can be safely uninstalled or disabled using ADB. Uninstalling or disabling these apps can help declutter the device and free up resources.

## List of Apps and Commands

### 1. **Galaxy Store**:
   - Package Name: `com.sec.android.app.samsungapps`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.sec.android.app.samsungapps
     ```

### 2. **Samsung Health**:
   - Package Name: `com.sec.android.app.shealth`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.sec.android.app.shealth
     ```

### 3. **Samsung Messages**:
   - Package Name: `com.samsung.android.messaging`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.samsung.android.messaging
     ```

### 4. **Samsung Internet**:
   - Package Name: `com.sec.android.app.sbrowser`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.sec.android.app.sbrowser
     ```

... (more apps can be added as needed)

## Notes
- Use the appropriate ADB commands to either **disable** or **uninstall** apps depending on your preference.
