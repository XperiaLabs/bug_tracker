XperiaLabs - Bug Tracker
=
Copyright (C) XperiaLabs Project 2023-2024
-

This is the Bug Tracker for XperiaLabs Development Project.

### Build Instructions

Please head to the following repository for the next steps:
https://github.com/XperiaLabs/local_manifests

### F&Q

## What does AOSP stand for?
AOSP stands for Android Open Source Project. It is the open-source foundation of the Android operating system. Faster updates compared to CLO ROMs.

## What does CLO stand for?
CLO (formerly known as CAF) ROMs are built using source code released by CodeLinaro (formerly the Code Aurora Forum) which is a fork of AOSP that runs better on Qualcomm devices as opposed to AOSP. CLO ROMs usually take longer to update due to Qualcomm releasing source a tad bit slower than the ASB (Android Security Bulletin).

### Supported Devices

| Device(s) | Codename(s) |
|:-|:-:|
|| _yodo board_ (**SM8550 Platform**, Snapdragon 8 Gen 2) |
| Xperia 1 V (CLO) <sup>Hiatus</sup> | [pdx234-clo](https://github.com/XperiaLabs/device_sony_pdx234-clo) |
| Xperia 1 V (AOSP) <sup>Hiatus</sup> | [pdx234](https://github.com/XperiaLabs/device_sony_pdx234)
|||
|| _murray board_ (**SM6375 Platform**, Snapdragon 695) |
| Xperia 10 IV <sup>Hiatus</sup> | [pdx225](https://github.com/XperiaLabs/device_sony_pdx225) |
|||
|| _sagami board_ (**SM8350 Platform**, Snapdragon 888) |
| Xperia 1 III (CLO) <sup>WIP</sup> | [pdx215-clo](https://github.com/XperiaLabs/device_sony_pdx215-clo) |
| Xperia 1 III (AOSP) <sup>Dropped</sup> | [pdx215](https://github.com/XperiaLabs/device_sony_pdx215-V2) |
|||
|| _lena board_ (**SM6350 Platform**, Snapdragon 690) |
| Xperia 10 III <sup>Dropped</sup> | [lena](https://github.com/XperiaLabs/device_sony_lena) |
|||
|| _[edo](https://github.com/XperiaLabs/device_sony_edo) board_ (**SM8250 Platform**, Snapdragon 865) |
| Xperia 1 II | [pdx203](https://github.com/XperiaLabs/device_sony_pdx203) |
| Xperia 5 II | [pdx206](https://github.com/XperiaLabs/device_sony_pdx206) |

### How to report a bug

- Press "Issues" button
- Press the "[New Issue](https://github.com/XperiaLabs/bug_tracker/issues/new/choose)" button
- Fill in the issue template mentioning the following items:
  - Device
  - Full Kernel Version (Including the patchlevel | E.g. Kernel Version: 5.4.242)
  - Android Version
  - The issue and steps to reproduce the issue
  - Logs if available
- Press "Submit new issue" button
