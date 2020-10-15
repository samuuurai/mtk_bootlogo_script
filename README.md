# Mediatek Bootlogo Script
A minimal shell script for generating logo.bin (bootlogo) used by Begonia or other MT67xx based devices.

This script is designed specifically for **Begonia (Redmi Note 8 Pro)** The script produces a working and identical bin to the one present in MIUI China ROM but if you try to use a custom image, the device gets bricked, though you can always experiment wtih your device and the script.

The default flashing location for generated flashable zip is **dev/block/platform/by-name/logo**, you can change it in updater-script.

## Requirements
You need Linux or Darwin to run the script, with **python3** and **zip** installed.

If you somehow generate a custom bootlogo for begonia, you can email me or message me on Telegram (@sudokepler)
Read instructions.txt for more information and generating for your device.

**I understand this script is useless and a total kang, but this is my first repo on github, I put this on there to look back at my retardedness someday**

Credits: Alps and @agentfabulous for signing script.

