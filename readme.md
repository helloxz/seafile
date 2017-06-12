# CentOS 7一键安装Seafile
Seafile 是一款开源的企业云盘，和Owncloud类似，个人感觉Seafile更加稳定，搭建也很简单，写了一个一键脚本，方便安装。（一键脚本使用SqLite 3作为数据库）
___

### 环境要求
* CentOS 7 64位
* Python >= 2.7
* SqLite 3

### 开始安装
```bash
#已经安装wget这一步可省略
yum -y install wget
wget https://raw.githubusercontent.com/helloxz/seafile/master/install_seafile.sh
chmod +x install_seafile.sh && ./install_seafile.sh
```

详细说明请访问：[https://www.xiaoz.me/archives/8480](https://www.xiaoz.me/archives/8480)