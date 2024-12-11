# OrangeFox device tree for alioth (Xiaomi Mi 11X / Redmi K40 / POCO F3)
This tree is for building OrangeFox Recovery for the _alioth_ devices

The Xiaomi Mi 11X (codenamed _"aliothin"_), Redmi K40 / POCO F3 (codenamed _"alioth"_) is a mid range smartphone from Xiaomi.

# Device specifications

| Device       | Xiaomi Mi 11X / Redmi K40 / POCO F3                        |
| -----------: | :----------------------------------------------------------|
| SoC          | Qualcomm SM8250 Snapdragon 870 5G                          |
| CPU          | 8x Qualcomm® Kryo™ 585 up to 2.84GHz                       |
| GPU          | Adreno 650                                                 |
| Memory       | 8GB / 6GB  (LPDDR 5)                                       |
| Shipped Android version | 11                    			    |
| Storage      | 128GB  (UFS 3.1)                                           |
| Battery      | Li-Po 4520 mAh, non-removable                              |
| Dimensions   | 163.7 x 76.4 x 7.8 mm                                      |
| Display      | 1080 x 2400 (20:9), 6.67 inches                            |

## Features

**Works**

- Booting
- **Decryption** (Android 12+)
- ADB
- MTP
- OTG
- vA/B partition functions
- Vibration

The Mi 11X / Redmi K40 / POCO F3 devices use a Virtual A/B Partition Scheme!

## Building

You can find a full compile guide for OrangeFox [Here](https://wiki.orangefox.tech/en/dev/building)

_Lunch_ command :
```
lunch twrp_alioth-eng && mka adbd bootimage
```

## Credits
- [Original alioth tree by Nebrassy](https://github.com/TeamWin/android_device_xiaomi_alioth)
- [Kernel](https://github.com/AOSPA/android_kernel_xiaomi_sm8250.git)

### Copyright
 ```
  /*
  *  Copyright (C) 2022-2024 The OrangeFox Recovery Project
  *
  * This program is free software: you can redistribute it and/or modify
  * it under the terms of the GNU General Public License as published by
  * the Free Software Foundation, either version 3 of the License, or
  * (at your option) any later version.
  *
  * This program is distributed in the hope that it will be useful,
  * but WITHOUT ANY WARRANTY; without even the implied warranty of
  * MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  * GNU General Public License for more details.
  *
  * You should have received a copy of the GNU General Public License
  * along with this program.  If not, see <http://www.gnu.org/licenses/>.
  *
  */
  ```
