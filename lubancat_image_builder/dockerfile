FROM ubuntu:18.04 
MAINTAINER embedfire
RUN  sed -i s@/archive.ubuntu.com/@/mirrors.aliyun.com/@g /etc/apt/sources.list
RUN apt-get update -y && \
        apt-get install make -y && \
        apt-get install gcc-arm-linux-gnueabihf -y && \
        apt-get install gcc-aarch64-linux-gnu -y && \
        apt-get install gcc -y && \
        apt-get install bison flex -y && \
        apt-get install libssl-dev -y && \
        apt-get install dpkg-dev -y && \
        apt-get install lzop -y && \
        apt-get install git -y && \
        apt-get install ncurses-dev -y && \
        apt-get install bc -y && \
        apt-get install kmod -y && \
        apt-get install cpio -y && \
        apt-get install sudo -y && \
        apt-get clean