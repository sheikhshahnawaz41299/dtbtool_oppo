# dtbtool_oppo

Original code can be found in LineageOS/android_device_oppo_msm8939-common

<b>Note</b>: <br> 
Oppo device's bootloader uses board-id to detect which dtb will be passed to the kernel according to board-id.

# How to compile 

` gcc path/to/dtbtool.c -o dtbtool

# How to generate master dtb 

` ./dtbtool -s 2048 -o dt.img  path/to/dtbs
