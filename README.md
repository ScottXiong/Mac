# Mac
- 【check】[serial number](https://checkcoverage.apple.com/cn/zh/) for macbook
# npm 包安装在哪里
```
cd ~/
ls -al
```
Meteor 1.6.0.1 has been installed in your home directory (~/.meteor).
Writing a launcher script to /usr/local/bin/meteor for your convenience.
This may prompt for your password.

### 查看本机ip
```
ifconfig | grep "inet " | grep -v 127.0.0.1
```
### 操作技巧
- 光标移到句首`control+a`，句尾`control+e`
### com+shift+.
- mac下控制文件的显隐
### mac修改主机名
`sudo scutil --set HostName MacBookPro`
### mac修改共享名
`sudo scutil --set ComputerName MacBookPro`
### 设置系统变量
[默认语法](https://www.cnblogs.com/shineqiujuan/p/4693404.html):`eg:export PATH=$PATH:/usr/local/mysql/bin`,查看系统变量`echo $PATH`
* cat /etc/profile
* cat /etc/paths
* cat ~/.bash_profile
```
vi ~/.bash_profile
#user root
export PATH=${PATH}:/usr/local/mysql/bin
export NODE_PATH=/usr/local/lib/node_modules

```
