# Spotify Car-Thing Capable

This repo contains the binaries extracted from my Z-Fold 3 for the last version of the Spotify binary still supporting the Car-Thing bluetooth drivers.

## Installation

To install, enable developer mode and USB debugging on your phone, then connect it to a PC and use adb to install the app bundle:

```bash
adb install-multiple --bypass-low-target-sdk-block .\base.apk .\split_config.arm64_v8a.apk .\split_config.en.apk .\split_config.xxhdpi.apk
```

You should get the message `Success`, indicating a successful install.

After the install, you should be able to launch spotify and pair your Car-Thing via bluetooth with the custom firmware.

To download the firmware, check out this [Google Drive link](https://drive.google.com/file/d/1Y2GRp97eFWM22mxyjIMaaqCns4Xvgy_s/view?usp=sharing) with the original firmware dump from [Dinosaur Talks Tech](https://www.youtube.com/watch?v=KbcO8K9Huz0).
