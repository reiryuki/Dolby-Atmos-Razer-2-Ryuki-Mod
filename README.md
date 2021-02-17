# Dolby Atmos Razer Phone 2 Magisk Module

## Descriptions
- An EQ ported from Razer Phone 2 (bolt)
- Doesn't support dynamic partition
- Spoofing product model/brand/device/manufacturer, may break some system apps.

## Requirements
- Android 9, 10, or 11
- 64 bit
- Magisk installed

## Installation Guide
- Remove another Dolby module
- Reboot
- Install via Magisk Manager only
- Reboot

## Optional
- If you using multiple audio mods (don't use both):
  - AML 4.0 supported
  - ACDB supported (Android 10 and bellow only for now)
- You can rename dax-default extension to use more bass enhancer boost. See /data/adb/modules_update/DolbyAtmos/system/vendor/etc/dolby/. Delete /data/vendor/dolby/dax_sqlite3.db if there before reboot.

## Troubleshootings
- If installation failed with "I/O error", then you need to disable DM-Verity of your ROM first.
- If SE policy patch doesn't work for your device, send logcats to dev, then try using force permissive method.
  Run at Terminal Emulator before flash:
  - `su`
  - `setprop dolby.force.permissive 1`
- If Dolby force close, reboot twice.
- Make sure manifest.xml is patched correctly.

## Report Guide
- [Tap here](https://t.me/audioryukimods/2618)
- If you don't do above, it will be closed immediately

## Telegram
- https://t.me/audioryukimods

## Donate
- https://www.paypal.me/reiryuki




           - Enjoy the Atmos 🎧 -
