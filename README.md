# Mediatek Bootlogo Script
A minimal shell script for generating logo.bin (bootlogo) used by Begonia or other MT67xx based devices.

This script is designed specifically for **Begonia (Redmi Note 8 Pro)** The script produces a working and identical bin to the one present in MIUI China ROM but if you try to use a custom image, the device gets bricked, probably because of verification and signing, though you can always experiment wtih your device and the script.

As the script is taken from Alps, it should work fine with other devices too, refer to the instructions in the repo for that, also, do not sign the bin if you're generating for another device, the certificates are from Xiaomi and are NOT needed for your device, though you can always sign it with the certificates used by your device if that's the case.

The default flashing location for generated flashable zip is **dev/block/platform/by-name/logo**, you can change it in updater-script in META-INF folder.

## Requirements
You need a Linux-based OS to run the script, with **python3** and **zip** installed.

## Issues
If you have any issue or you generated a custom bootlogo for begonia, you can email me anytime or message me on Telegram (@moonkepler)
