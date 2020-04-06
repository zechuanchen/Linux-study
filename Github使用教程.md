# Github使用教程


标签（空格分隔）： 

---

一、注册github账号：
https://github.com/
创建公共仓库 配置仓库信息
二、Github安装
[下载git Windows版](https://github.com/git-for-windows/git/releases/download/v2.26.0.windows.1/Git-2.26.0-64-bit.exe)

三、配置Git
本地创建ssh key
```
ssh-keygen -t rsa -C "540096844@qq.com"
```
生成结果：可以选择默认，在~/生成.ssh文件夹
```
Generating public/private rsa key pair.
Enter file in which to save the key (/c/Users/hp/.ssh/id_rsa):
/c/Users/hp/.ssh/id_rsa already exists.
Enter passphrase (empty for no passphrase): #输入github账户的密码
Enter same passphrase again:  #同上
Your identification has been saved in /c/Users/hp/.ssh/id_rsa.
Your public key has been saved in /c/Users/hp/.ssh/id_rsa.pub.  
#public key 保存在/c/Users/hp/.ssh/id_rsa.pub
The key fingerprint is:
SHA256:tm+UfmlP5GQ2Jln2qmXM6DGq5WtrdGJZPaoSD0NPq8s 540096844@qq.com
The key's randomart image is:
```
然后
```
cat /c/Users/hp/.ssh/id_rsa.pub

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQC93oNWMKRtfEmuCE6KTf97JEDUYzqy3vuPOyuE7NGuImBuu797PdrU7rz7jGEVpjhtmuXN1woiKj7GKWNsVU0QRldMD5D5WkhunmFBajZnoYEK97Fkyt/ZHvpSlBJxzcqW1ToifzQU80+wOlATDTNG7/kE/8EnKMGhz7tIVI895r4/U7UuDnYz0EGOYFOPV0kFipUgqHs/U5LpmN/CLVbFjZccGy0CAyEEF534xKJl7aXEoxTTAqdTjwnjBFpUzPWZrUw6DpxRxIRD4Oy48ln44EJAGupliFP6tINdqhQUkwLhY95c22Y6x+BYfdBvgd5/sM7yiG5JVZ3vsHXr+NMV 540096844@qq.com
```





