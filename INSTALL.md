# Installation Guide

## Prerequisites

- iQOO Z9x (I2219) or Vivo T3x (V2407)
- Android 12 or higher
- At least 4GB free storage
- USB debugging enabled (optional, for troubleshooting)

## Step-by-Step Installation

### 1. Download the APK

Download `ghostlock-z9x-t3x-v0.0.1.apk` from the [Releases](https://github.com/RahadHack99/iqoo-z9x-vivo-t3x-ghostlock/releases/tag/0.0.1) page.

### 2. Enable Unknown Sources

1. Go to **Settings** → **Security** → **Install unknown apps**
2. Select your file manager or browser
3. Enable "Allow from this source"

### 3. Install the APK

1. Open the downloaded APK file
2. Tap "Install"
3. Wait for installation to complete
4. Tap "Open" or find "GhostLock" in your app drawer

### 4. Root Your Device

1. Launch GhostLock app
2. Review device information displayed
3. Tap the "Install" button
4. Wait for the rooting process (2-5 minutes)
5. Device will automatically verify root access

### 5. Install KernelSU Manager

After rooting succeeds:

1. Tap "Download KernelSU Manager" when prompted
2. Install the KernelSU Manager APK
3. Open KernelSU Manager
4. Verify root status shows "Active"

## Troubleshooting

### App shows "Unsupported device"

- Verify your model number in Settings → About Phone
- Ensure kernel version matches: `5.10.246-android12-9`
- Try enabling "Force Compatibility Mode" if available

### Root fails during installation

1. Restart your device
2. Clear GhostLock app data
3. Try again
4. Check install history for error details

### KernelSU not working after root

1. Reinstall KernelSU Manager (exact version shown in app)
2. Grant all requested permissions
3. Reboot device

### Banking apps detect root

1. Use KernelSU's "Hide" feature
2. Enable "Unmount modules" for specific apps
3. Some apps may still detect - use at your own discretion

## Verification

To verify successful root:

```bash
# Using ADB
adb shell su -c id
# Should show: uid=0(root) gid=0(root)
```

Or use a root checker app from Play Store.

## Uninstalling Root

Currently, unrooting requires:
1. Flashing stock firmware
2. Factory reset

⚠️ **Backup your data before rooting!**
