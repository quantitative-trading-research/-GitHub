# how to connect remote server easily

目前服务器端的ubuntu版本更新为18.04，,添加了更加易用的访问方式,且解决了分别率低的问题, 前置条件是要通过vpn登录内网

## step0: 通过EasyConnect vpn登录内网（且访问10.202.33.83的用户权限已通过）

## step1: 打开远程桌面连接
在windows10中直接搜索： 远程桌面连接

## step2: 键入IP地址
~~~
#add a connection
键入： 10.202.33.83
~~~

## step3: input username and password
~~~
#私信发给大家
~~~

# install common softwares

## install anaconda
step1: download anaconda linux version
~~~
https://www.anaconda.com/products/individual
~~~

step2: install
open a terminal, find the download path, then install
~~~
bash Anaconda3-2020.02-Linux-x86_64.sh
~~~
> to use anaconda command in terminal, you need to add it to environment variable

## install RAalpha
see reference, [documents](https://rqalpha.readthedocs.io/zh_CN/latest/intro/install.html)
~~~
pip install -i https://pypi.douban.com/simple rqalpha
~~~

