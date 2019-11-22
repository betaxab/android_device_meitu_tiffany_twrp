# TWRP Device configuration for Meitu T9

## Device specifications

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Octa-core (4x2.2 GHz Kryo 260 & 4x1.84 GHz Kryo)
CHIPSET | Qualcomm SDM660 Snapdragon 660
GPU     | Adreno 512
Memory  | 4,6GB
Shipped Android Version | 8.1 (Oreo)
Storage | 64,128GB
Battery | 3100 mAh
Dimensions | 75 x 172.1 x 9.5 mm
Display | 1080 x 2160 pixels, 6.01" AMOLED
Rear Camera  | 12 MP + 5 MP, (PDAF, dual pixel)
Front Camera | 12 MP + 5 MP

### Kernel Source
None, Use prebuilt kernel from stock firmware

### How to compile

```sh
. build/envsetup.sh
lunch omni_tiffany-eng
make -j4 recoveryimage
```
### Copyright
 ```
  /*
  *  Copyright (C) 2013-19 The OmniROM Project
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
