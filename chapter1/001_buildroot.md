### 1.1. Buildroot 준비

[2016.11 버전](https://buildroot.org/downloads/buildroot-2016.11.tar.gz)을 사용한다.

````bash
tar xzf buildroot-2016.11.tar.gz
cd buildroot-2016.11
make O=../output-buildroot raspberrypi3_defconfig
make O=../output-buildroot
````

