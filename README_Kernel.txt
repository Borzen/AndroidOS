HOW TO BUILD KERNEL 3.1 ICS FOR P4-Wifi(P7510)

1. How to Build
	- Get Toolchain (arm-eabi-4.4.3)
	- edit Makefile
			edit "CROSS_COMPILE" to right toolchain path(You downloaded).
			Ex)  CROSS_COMPILE=/opt/toolchains/arm-eabi-4.4.3/bin/arm-eabi-
	$ make ARCH=arm samsung_p4wifi_defconfig
	$ make ARCH=arm
	
2. Output files
	- Kernel : /arch/arm/boot/zImage
	
3. build clean
	- make clean
