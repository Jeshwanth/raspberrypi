obj-m += HelloWorld.o

export CCPREFIX=/home/jeshwanth/raspberry/tools/tools-master/arm-bcm2708/gcc-linaro-arm-linux-gnueabihf-raspbian/bin/arm-linux-gnueabihf-
all:
	make ARCH=arm CROSS_COMPILE=${CCPREFIX} -C /home/jeshwanth/raspberry/linux-rpi-3.2.27 M=$(PWD) modules

clean:
	make -C /home/jeshwanth/raspberry/linux-rpi-3.2.27 M=$(PWD) clean
