## Adafruit kernel 적용

LCD를 활성화하기 위해서 [Adafruit github](https://github.com/adafruit/adafruit-raspberrypi-linux)를 사용한다.

````bash
cd buildroot-2016.11
make O=../output-buildroot menuconfig
````

![menuconfig](../images/0001_buildroot-menuconfig.png)