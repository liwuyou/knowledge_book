## ubuntu的基础操作
```
更新库
sudo apt update

库安装
sudo apt install yourku

```

## ubuntu的ssh连接
### 前期配置
```
查看本机IP
ipcongig

安装ssh
sudo apt install openssh-server

启动ssh
sudo systemctl status ssh
sudo systemctl start ssh
sudo systemctl enable ssh

编辑配置文件
sudo cp /etc/ssh/sshd_config /etc/ssh/sshd_config_copy
sudo vim /etc/ssh/sshd_config
```

### ssh连接
```
ssh wuyou@192.168.203.128
```

## ubuntu C与C++的编译与运行
```
安装编译器
sudo apt update
sudo apt install gcc g++   # 两个都安装

验证安装
gcc --version
g++ --version

编译与运行
gcc hello.c -o hello
./hello
```