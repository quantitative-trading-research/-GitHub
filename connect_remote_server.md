# 远程连接服务器快速入门

# Windows快速连接至服务器
目前服务器端的ubuntu版本更新为18.04,添加了更加易用的访问方式,且解决了分别率低的问题(目前暂时不支持通过vpn登录内网)。

## step1: 打开远程桌面连接
在windows10中直接搜索: 远程桌面连接

## step2: 键入IP地址
```txt
/* add a connection */
键入: 192.168.1.117
```

## step3: 输入用户名和密码
```txt
/* 私信发给大家 */
```

# 安装通用软件

## 1 安装 anaconda
### step1: 下载Linux版本的Anaconda

```txt
/* offical */
https://www.anaconda.com/products/individual

/* tsinghua */
https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/
```

### step2: 安装Anaconda
打开终端并前往下载目录，找到`Anaconda3-20xx.xx-Linux-x86_64.sh`文件

```bash
# add execution permission to Anaconda3-20xx.xx-Linux-x86_64.sh
$ chmod u+x Anaconda3-20xx.xx-Linux-x86_64.sh
# installation
# if you don`t want to custome insall enter yes instead
$ ./Anaconda3-20xx.xx-Linux-x86_64.sh
```

> 安装Anaconda时已自动将`conda`可执行指令加入了环境变量中，如果在终端中我们无法使用`conda`指令时需要手动添加Anaconda可执行路径至系统环境变量中。

## 2 安装 RAalpha
更多使用介绍请参考[官方文档](https://rqalpha.readthedocs.io/zh_CN/latest/intro/install.html)

```bash
$ pip install -i https://pypi.douban.com/simple rqalpha
```
