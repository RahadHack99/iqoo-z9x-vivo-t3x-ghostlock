# GhostLock Z9x/T3x Root - v0.0.1

## Supported Devices

### iQOO Z9x
- Model: I2219
- Kernel: 5.10.246-android12-9-00010-g8ca7539b1d84-ab14517425
- SoC: Qualcomm SM6450 (Snapdragon 6 Gen 1)

### Vivo T3x
- Model: V2407
- Kernel: 5.10.246-android12-9-00010-g8ca7539b1d84-ab14517425
- SoC: Qualcomm SM6450 (Snapdragon 6 Gen 1)

### iQOO Z9 5G (Legacy)
- Model: I2302
- SoC: MediaTek MT6886

### Vivo T3 5G (Legacy)
- Model: V2334
- SoC: MediaTek MT6886

## Features

- **Multi-Device Support**: Automatically detects Z9x (I2219) and T3x (V2407)
- **Device Selection Fallback**: Manual device selection if auto-detection fails
- **CVE-2026-43499 Exploit**: Futex PI UAF for root access
- **KernelSU Integration**: Full root management with KernelSU
- **Shizuku Mode**: Optional Shizuku-based privilege escalation
- **Install History**: Track all installation attempts

## Installation

1. Download `ghostlock-z9x-t3x-v0.0.1.apk`
2. Install on your device
3. Launch the app
4. Follow on-screen instructions
5. Device will be automatically detected
6. Tap "Install" to begin root process

## Requirements

- Android 12+ (API 31+)
- ARM64-v8a architecture
- Unlocked bootloader (recommended)
- Matching kernel version for best compatibility

## Changes in v0.0.1

- Added iQOO Z9x (I2219) support
- Added Vivo T3x (V2407) support
- Expanded device detection to include both Snapdragon and MediaTek variants
- Updated GitHub release source to RahadHack99/iqoo-z9x-vivo-t3x-ghostlock
- Improved error messages for unsupported devices
- Maintained backward compatibility with Z9 5G and T3 5G

## Technical Details

**Exploit**: CVE-2026-43499 futex PI UAF  
**Attack Vector**: UMH (User Mode Helper) - Path A  
**Privilege Escalation**: Kernel memory manipulation via pipe physrw  
**Root Method**: KernelSU module injection  
**Persistence**: KernelSU manager integration

## Repository

GitHub: https://github.com/RahadHack99/iqoo-z9x-vivo-t3x-ghostlock

## Credits

- Original GhostLock framework
- CVE-2026-43499 exploit research
- KernelSU project
- Shizuku framework

## Disclaimer

This tool is for educational and research purposes. Rooting your device voids warranty and may brick your device. Use at your own risk.
