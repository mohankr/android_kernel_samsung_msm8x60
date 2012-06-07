HOW TO BUILD KERNEL 3.0.15 FOR SHV-E110S

1. How to Build
	- get Toolchain
	download and install arm-eabi-4.4.3 toolchain for ARM EABI.

2. Extract kernel source and move into the top directory.

3. Execute 'build_kernel_E110S.sh'


4. Output files
	- Kernel : kernel/arch/arm/boot/zImage
	- module : kernel/drivers/*/*.ko
	
5. How to make .tar binary for downloading into target.
	- change current directory to kernel/arch/arm/boot
	- type following command
	$ tar cvf SHV-E110S_Kernel.tar zImage
