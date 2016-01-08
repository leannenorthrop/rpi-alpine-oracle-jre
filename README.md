# rpi-alpine-oracle-jdk

Docker image creation for Raspberry Pi cluster with Oracle JRE. Based on the work of Gary Wisniewski and so many others which allowed me to [build the glibc apk file for armhf](https://github.com/leannenorthrop/rpi-alpine-glibc) and this image based on it for running Oracle Java 8.

## Creation

`docker build -t test/alpine-java .`

## Interactive Usage

`docker run -ti test/alpine-java` will start a bash shell with Java tools on path.
