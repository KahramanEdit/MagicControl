# MagicControl

A Magisk module for advanced device control.

## Features
- **Charge separation** — stops charging at a threshold, with optional delay
- **Charge boost** — removes current restriction when charge separation is off
- **Vibration boost** — gain / duration / vmax tuning
- **Touch optimization** — global or per-app high report rate
- **Brightness unlock** — allows panel to reach its real hardware ceiling
- **Force fan max** — watchdog pushes fan to max level
- **Force liquid cooling max** — watchdog pushes pump to max
- **Thermal removal** — bind-mounts a threshold-stripped thermal-engine.conf (with boot-loop guard)
- **Cloud control block** — cleans and locks `/data/system/cube` folders

## WebUI
Interactive control panel accessible from Magisk / KernelSU / APatch manager.

## Install
1. Download the latest `MagicControl-vX.Y.Z.zip`
2. Flash via Magisk / KernelSU / APatch
3. Reboot

## Notes
- Thermal removal requires a reboot to take effect.
- Tested on Snapdragon devices with `/sys/class/qcom-battery` and `/proc/driver/micropump`.

## Author
Clenix
