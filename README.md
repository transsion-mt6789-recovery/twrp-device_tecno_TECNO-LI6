## TECNO CAMON 40 4G (_CM5_)
## TWRP / OrangeFox device tree

## Device specifications

Device                  | TECNO CAMON 40 4G
-----------------------:|:-----------------------------------------
SoC                     | Mediatek Helio G100 Ultimate (6 nm)
CPU                     | Octa-core (2x2.2 GHz Cortex-A76 & 6x2.0 GHz Cortex-A55)
GPU                     | Mali-G57 MC2
Memory                  | 8/12 GB RAM
Storage                 | 128/256 GB (UFS 2.2)
MicroSD                 | microSDXC (hybrid slot)
Shipped Android Version | 15.0
Battery                 | Non-removable 5200 mAh
Display                 | 1080 x 2436 pixels (~393 ppi density), 6.78 inches
Camera                  | 50 MP (wide), 8 MP (ultrawide); 32 MP (front, wide)

## Device picture

![ TECNO CAMON 40 4G ](https://fdn2.gsmarena.com/vv/pics/tecno/tecno-camon-40-4g-2.jpg "TECNO CAMON 40 4G")

## Features

Works:

- [X] ADB
- [X] Decryption
- [X] Display
- [X] Fasbootd
- [X] Flashing
- [X] MTP
- [X] Sideload
- [ ] USB OTG
- [ ] Vibrator

## Building

_Lunch_ command :

```
lunch twrp_CM5-eng && mka adbd vendorbootimage
```

### Copyright
 ```
  /*
  *  Copyright (C) 2025 Transsion mt6789 Custom Recovery Project
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
