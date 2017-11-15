# VNPY-noVNC-DOCKER

DOCKER 比虚拟机的好处是:启动快，占用内存小。

CN3C3P/noVNC全部在浏览器里工作-----

A docker that runs VNPY stock trading API (and more 还可以运行很多其他用途---)

已编译好:CTP linux API vnpy1.7.1,vnpy1.5   镜像大小 total: 4 G

cn3c3p/vnpy-novnc镜像里已经安装好的内容包含有：

Debian jessie 8/anaconda2.7

pyqt4 \ qt4

pymongo    可以链接：docker pull mongo

websocket-client

msgpack-python

qdarkstyle

汉语拼音输入fcitx-config-gtk

xfce-4,gedit ,firefox, gcc-4.9 g++-4.9 cmake

sublime,
Spyder Updating 需要更新: pip install -U spyder

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

默认密码(VNC PASSWORD)：88888888
可以通过 vncpasswd  更改vnc密码

运行VNPY1.7.1：

1）cd ./vnpy-1.7.1/examples/VnTrader

2) python run.py


Thanks！ Based on continuumio/anaconda:latest,VNPY

<img src="https://github.com/cn3c3p/VNPY-noVNC-DOCKER/blob/master/34d5393b55dc%200%20%20%20noVNC(4).jpg">

<img src="https://github.com/cn3c3p/VNPY-noVNC-DOCKER/blob/master/34d5393b55dc%200%20%20%20noVNC(3).jpg">

<img src="https://github.com/cn3c3p/VNPY-noVNC-DOCKER/blob/master/6ef80dd86a51%200%20%20%20noVNC(1).jpg">

<img src="https://github.com/cn3c3p/VNPY-noVNC-DOCKER/blob/master/cn3c3p-novnc.jpg">
