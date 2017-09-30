# VNPY-noVNC-DOCKER

DOCKER 比虚拟机的好处是启动快，占用内存小。
我搞的CN3C3P/noVNC全部在浏览器里工作-----

已编译好:CTP linux API vnpy1.7   镜像大小 total: 5.1G

VNPY镜像主要有：

Debian jessie 8/anaconda2.7

pyqt5 \ qt5

pymongo

websocket-client

msgpack-python

qdarkstyle

汉语拼音输入

xfce-4,gedit ,firefox, gcc-4.9 g++-4.9 cmake

sublime

可以安装运行suit to run：pycharm,WingIDE

端口： EXPOSE 5900 8686

This container runs:

Xvfb -x11vnc -noNVC -Tigervnc

How To With Docker Hub:

下载在  https://hub.docker.com/r/cn3c3p/vnpy-novnc/

docker pull cn3c3p/vnpy-novnc

DOCKER启动：

docker run -d -p 8686:8686 cn3c3p/vnpy-novnc

浏览器firefox

http://localhost:8686

默认密码PASSWORD：88888888


Thanks！ Based on continuumio/anaconda:latest,VNPY

<img src="https://github.com/cn3c3p/VNPY-noVNC-DOCKER/blob/master/34d5393b55dc%200%20%20%20noVNC(4).jpg">

<img src="https://github.com/cn3c3p/VNPY-noVNC-DOCKER/blob/master/34d5393b55dc%200%20%20%20noVNC(3).jpg">
