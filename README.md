Mansi Kernel for Xiaomi Redmi 3 ![Build Status](https://travis-ci.org/Lenovo-K3/android_kernel_lenovo_msm8916.svg?branch=master)
==================================================
Basic   | Spec Sheet
-------:|:----------
CPU     | Quad-core 1.5 GHz Cortex™ A53 & Quad-core 1.2 GHz Cortex™ A53 64Bit ARM® 
Chipset | Qualcomm Snapdragon 616, MSM8939v2
GPU     | Adreno 405
ROM     | 16GB 
RAM     | 2GB LPDDR3
Android | 5.1.1
Battery | 4100 mAh
Display | 720x1280 pixels, 5.0 (~294 ppi pixel density)
Rear Camera  | 13 MP, f/2.0, phase detection autofocus, LED flash
Front Camera | 5 MP, f/2.2, 1080p@30fps
Wi-Fi     | Wi-Fi 802.11 b/g/n, Wi-Fi Direct, hotspot
Bluetooth | v4.1, A2DP
Gps      | With A-GPS, GLONASS, BDS

IMPORTANT HARDWARE INFORMATION
==================================================
|Hardware | Information |
--------:|:--------------
Flash    | null
LCD      | hx8394F_HD720p_video_BOE
TouchPanel | Focaltech, FT5336, 0x4
Camera_Main | s5k3l8, O-film
Camera_Sub | ov5670_q5v41b, O-film
Accelerometer | bma2x2
Alsps    | liteon
Gyroscope| yas537
Magnetometer| yas537


BUILD KERNEL INFORMATION
==================================================
1. Configure build.sh script
    
		export CROSS_COMPILE=~/toolchains/aarch64-linux-android-4.9/bin/aarch64-linux-android-

2. Use build script
    
		./build.sh

3. Flash kernel use custom recovery
    
		~/kernel_dir/Mansi/Mansi_(release)_(date(time)).zip

4. Rebot phone and use new kernel

VIEW DEVICE
==================================================
![Redmi 3](http://www.microsoft-dynamics.net/wp-content/uploads/2016/01/Xiaomi-Redmi-3-3.jpg)
