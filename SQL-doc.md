# 先创建本地版本库，然后创建github的远程仓库，然后进行两者的链接，吧文件导入。如果文件不能复制，那么就用vim里 打开地十八行 删除掉 代码为 vim .vimrc
#####  进行创建数据库，其中打开源码```sudo vim /etc/apt/sources.list```
然后粘贴代码
```
deb http://mirrors.aliyun.com/ubuntu/ xenial main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ xenial-security main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ xenial-updates main restricted universe multiverse
deb http://mirrors.aliyun.com/ubuntu/ xenial-backports main restricted universe multiverse
##测试版源
deb http://mirrors.aliyun.com/ubuntu/ xenial-proposed main restricted universe multiverse
#源码
deb-src http://mirrors.aliyun.com/ubuntu/ xenial main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-security main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-updates main restricted universe multiverse
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-backports main restricted universe multiverse
##测试版源
deb-src http://mirrors.aliyun.com/ubuntu/ xenial-proposed main restricted universe multiverse
# Canonical 合作伙伴和附加
deb http://archive.canonical.com/ubuntu/ xenial partner
deb http://extras.ubuntu.com/ubuntu/ xenial main
```
### 接着创建数据库，并设置密码123456
``` sudo apt-get update
sudo apt-get install tasksel
sudo tasksel  ```
#### 然后创建并打开数据库代码为mysql -u root -p        然后回车 敲入密码。进入。
 然后输入show databases  接着输入； ，可以显示数据库
