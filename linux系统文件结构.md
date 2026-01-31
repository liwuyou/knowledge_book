## 文件结构
![20260131175059](https://liwuyou66.oss-cn-beijing.aliyuncs.com/img/20260131175059.png)
```
wuyou@ubuntu:/lib$ ls /
bin   cdrom  etc   lib    lib64   lost+found  mnt  proc  run   snap  swapfile  tmp  var
boot  dev    home  lib32  libx32  media       opt  root  sbin  srv   sys       usr
```
**系统启动文件**
/boot,启动的内核文件
/etc,系统全局配置文件"etcetera等等"，网络，权限，apt等配置文件
/lib,基本代码库,类似windows的DDL文件
/sys

**命令集合**
/bin 二进制，常用程序和指令
/sbin，s是super，管理员程序或指令

**设备相关**
/dev Device设备，设备文件。
/medio 自动识别的设备，u盘光驱等
/mnt 用户临时挂载文件系统

**临时文件**
/run /lost+found /tmp

**用户相关**
/root /home /usr