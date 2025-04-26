# Vim
## 课后练习
#### 1.完成 vimtutor 
![示例图片](img/2.png)

学习Vim
![示例图片](img/1.png)
...


#### 2.安装和配置一个插件： ctrlp.vim
创建插件文件夹
![示例图片](img/3.png)

下载这个插件
![示例图片](img/4.png)

## 遇到的问题
#### 1. 权限不够
![示例图片](img/5.png)

以 root 用户登录
`su - root`


#### 2.cannot find a valid baseurl for repo:base/7/x86_64
检查网络连接
`ping -c 4 google.com`

检查DNS设置
`编辑 /etc/resolv.conf文件;
添加 nameserver 8.8.8.8
nameserver 114.114.114.114`

检查YUM仓库配置
`sudo cp -r /etc/yum.repos.d /etc/yum.repos.d.backup`
