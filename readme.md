# tuya_gw_link_sdk

## overview

feature :

* Register to Tuya Cloud platform.
* Realtime preview via Tuya Smart APP

## how to use

### run a quick demo

1) edit Makefile, and set COMPILE_PREX ?= to absolute path of your toolchain gcc.

2) compile one application.


```bash
sh build_app.sh <app name> <version>
```

## SDK manual 

[TUYA DOCS center](https://docs.tuya.com/zh/iot/device-development/access-mode-link/linux-general-sdk/gerneral-link-module-sdk)

## supported platforms

### ubuntu x64

* linux-ubuntu-6.2.0_64Bi


### andriod 64bit Linux

* aarch64-linux-android

### andriod 32bit Linux

*arm-linux-androideabi


### REALTEK rtl819x

* msdk-4.4.7-mips-EL-3.10-u0.9.33-m32t-140827 

* mips-linux-uclibc-gcc-4.4.7


### bcm6755

* crosstools-arm-gcc-5.5-linux-4.1-glibc-2.26-binutils-2.28.1

