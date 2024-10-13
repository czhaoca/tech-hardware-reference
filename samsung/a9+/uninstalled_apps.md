
# Samsung Apps to Uninstall or Disable

This file contains a list of Samsung-specific apps that can be safely uninstalled or disabled using ADB. Uninstalling or disabling these apps can help declutter the device and free up resources.

## List of Uninstalled Apps and Commands

### 1. **Samsung Health**:
   - Package Name: `com.sec.android.app.shealth`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.sec.android.app.shealth
     ```

### 2. **Galaxy Store**:
   - Package Name: `com.sec.android.app.samsungapps`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.sec.android.app.samsungapps
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

### 5. **Samsung Gallery**:
   - Package Name: `com.sec.android.gallery3d`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.sec.android.gallery3d
     ```

### 6. **Samsung Keyboard (Honeyboard)**:
   - Package Name: `com.samsung.android.honeyboard`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.samsung.android.honeyboard
     ```

### 7. **Samsung Clock**:
   - Package Name: `com.sec.android.app.clockpackage`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.sec.android.app.clockpackage
     ```

### 8. **Samsung Contacts**:
   - Package Name: `com.samsung.android.app.contacts`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.samsung.android.app.contacts
     ```

### 9. **OneDrive**:
   - Package Name: `com.microsoft.skydrive`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.microsoft.skydrive
     ```

### 10. **My Rogers (Tablet)**:
   - Package Name: `com.myrogers.tablet`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.myrogers.tablet
     ```

### 11. **Samsung Cloud**:
   - Package Name: `com.samsung.android.scloud`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.samsung.android.scloud
     ```

### 12. **Samsung Phone/Dialer**:
   - Package Name: `com.samsung.android.dialer`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.samsung.android.dialer
     ```

### 13. **Samsung My Files**:
   - Package Name: `com.sec.android.app.myfiles`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.sec.android.app.myfiles
     ```

### 14. **Samsung Calculator**:
   - Package Name: `com.sec.android.app.popupcalculator`
   - Uninstall Command:
     ```bash
     adb shell pm uninstall --user 0 com.sec.android.app.popupcalculator
     ```

## Notes
- Use the appropriate ADB commands to either **disable** or **uninstall** apps depending on your preference.
- Uninstalling these apps removes them only for the current user, and they may be restored after a factory reset.
