# Dts files to accompany si4703 and fram

Linux repository for these drivers : https://github.com/furhadjidda/linux/tree/development/tuner-si4703

NOTE : All examples are done based on Raspberry Pi-3 

#### Decompiling a device tree blob(dtb) to dts file:
###### root@raspberrypi:~# dtc -I dtb -O dts -o /root/bcm2835-zero.dts /boot/bcm2835-rpi-zero.dtb 

#### Compiling a dts file to dtb:
###### sudo dtc -O dtb -o /home/pi/bcm2709-rpi-2-b.dtb /home/pi/bcm2709-rpi-2-b.dts
