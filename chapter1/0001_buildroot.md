## Buildroot 준비

[2016.11 버전](https://buildroot.org/downloads/buildroot-2016.11.tar.gz)을 사용한다.

아래 절차대로 수행해서 우선 이미지를 만들 수 있다.

````bash
tar xzf buildroot-2016.11.tar.gz
cd buildroot-2016.11
make raspberrypi3_defconfig
make
````
