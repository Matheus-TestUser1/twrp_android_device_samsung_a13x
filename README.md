# Android Device Tree for Samsung Galaxy A13 5G (A136m)

```
#
# Copyright (C) 2024 The LineageOS Project
#
# SPDX-License-Identifier: Apache-2.0
#
```

![banner](https://i.blogs.es/37c09e/product-image_galaxy-a14-5g/1366_521.jpg)

## Overview

The Samsung Galaxy A13 5G is an entry level device released by Samsung in early 2023 featuring MediaTek's Dimensity 700 chipset

## Specifications

### Hardware

- **Processor**: MediaTek Dimensity 700 (7 nm)
- **RAM**: 4GB LPDDRX4 
- **Storage**: Internal storage options range from 64GB to 128GB, expandable storage. (UFS 2.2)
- **Display**: 6.6-inch PLS LCD with a resolution of 700 x 1600 pixels and a 90Hz refresh rate.
- **Battery**: 5000mAh
- **Camera**:
  - Triple rear camera setup: 50MP wide, 2MP macro, and 2MP depth sensor.
  - 32MP front-facing camera.
- **Connectivity**:
  - Network: GSM / HSPA / LTE / 5G
  - Wi-Fi: Wi-Fi 802.11 a/b/g/n/ac, dual-band, Wi-Fi Direct
  - Bluetooth: 5.2, A2DP, LE
  - NFC: Yes
  - USB: USB Type-C 2.0
- **Sensors**: Fingerprint (side-mounted), accelerometer, gyro, proximity, compass

**### Build**

Make sure you have the necessary build environment set up

1. **Preparation:**
   ```bash
   source build/envsetup.sh  # Source the build environment setup script
   export ALLOW_MISSING_DEPENDENCIES=true  # Necessary step, allows building with missing dependencies and minimal manifest
   lunch twrp_a14xm-eng  # Choose the appropriate device/variant for your A14XM
   ```

2. **Build Recovery Image:**
   ```bash
   mka recoveryimage
   ```




