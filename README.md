# x96max-lkc
A linux kernel config for x96max

# HOW TO
```
sudo apt install linux-source

tar -xf /usr/src/linux-source-X.YY.tar.xz
cd linux-source-X.YY
cp ../config .config

make ARCH=arm64 menuconfig
ARCH=arm64 CROSS_COMPILE=aarch64-linux-gnu- nice make -j4 bindeb-pkg
```
