Realme Narzo 30A / Narzo 20 / 7i EU Device Tree - RMX3171/RMX2193
================================================================


Basic   | Spec Sheet
-------:|:-------------------------
CPU     | OOcta-core (2x2.0 GHz Cortex-A75 & 6x1.8 GHz Cortex-A55)
Chipset | MediaTek Helio G85 (12 nm)
GPU     | Mali-G52 MC2
Memory  | 3/4 GB
Shipped Android Version | Android 10, realme UI 1.0 
Storage | 32/64 GB (eMMC type)
MicroSD | Up to 512 GB 
Battery | Li-Po 6000 mAh, non-removable
Dimensions | 164.5 x 75.9 x 9.8 mm (6.48 x 2.99 x 0.39 in)
Display | 720 x 1600 pixels, 20:9 ratio (~270 ppi density)
Rear Camera  | Dual : 13 MP; 2MP (depth)
Front Camera | Single: 8 MP
Release Month | Announched: Feb 24, 2021; Released: 2021, March 05 

![Realme Narzo 30A](https://fdn2.gsmarena.com/vv/pics/realme/realme-narzo-30a-1.jpg "Realme Narzo 20")


Patches needed:

1. Needed to boot: https://github.com/SamarV-121/android_vendor_extra/blob/lineage-18.1/patches/external/selinux/0001-Revert-libsepol-Make-an-unknown-permission-an-error-.patch
2. Needed for AV fix: https://github.com/phhusson/platform_frameworks_av/commit/624cfc90b8bedb024f289772960f3cd7072fa940.patch

Copyright (C) 2021 Lineage OS
