# 栗子派 leez P710 开发板 debian10 系统镜像

---

### 1. 完整 SD 启动盘，完整系统
#### 镜像文件: leezp710_debian10_20190723_update.img

- 此镜像文件，包含整个启动盘所有文件系统
- 此镜像文件直接烧录到 SD 卡即可开机启动正常使用，烧录方法：
> [linux系统]：sudo dd if=update.img of=/dev/sda bs=10M (假如 sd 卡设备文件是 /dev/sda)
> [window系统]： 直接使用 win32diskimager 烧录到 SD 卡，和烧录树莓派镜像方法一样
- 烧录后开机约需要1-2分钟时间，系统自动初始化扩展分区到整个 SD 卡的大小，初始化完成会自动重启，然后就可以正常使用。仅在烧录后第一次开机会初始化重启一次，并且整个过程持续不超过2分钟，自动完成不需要额外任何操作，坐等重启完成正常使用。
- 系统是 debian10 纯净最小系统，没有图形桌面，只能使用黑屏幕的控制台，开机需要什么软件自己连接网络自己安装，插网线会自动链接网络，软件源已配置好国内中科大源，开机即用
- 普通用户名 leez，密码是 leez
- 管理员用户 root，密码是 root

### 下载链接： [百度网盘](https://pan.baidu.com/s/1owG0KD4MkS8R6a50Kmtilw) 提取码: xxd8
---

### 2. 完整 SD 启动盘，完整系统，带有图形桌面
#### 镜像文件: leezp710_debian10_desktop-xfce4_20190724_update.img

- 此镜像文件，在 1 的基础上增加了图形桌面，xfce4，其他都一样
  
### 下载链接： [百度网盘](https://pan.baidu.com/s/1owG0KD4MkS8R6a50Kmtilw) 提取码: xxd8
---

### 3. 根分区镜像文件，仅 rootfs
#### 镜像文件： leezp710_debian10_20190723_rootfs.img

- 此镜像文件是栗子派 leez P710 开发板根分区镜像，仅仅是根分区 (rootfs分区) 镜像，不含其他分区，不是整个启动盘所有系统，所以只能烧录到 rootfs 分区，不要烧录到整个 SD 卡。
- 烧录后开机需要手动扩展分区大小，需要什么软件自己安装
- 系统是 debian10 纯净最小系统，没有图形桌面，只能使用黑屏幕的控制台。所以镜像文件也很小，350MB。
- 板子插上网线会自动连接网络，确认路由打开 DHCP 即可，或者重启一下板子
- 软件源配置好了，是国内中科大源
- 用户名 leez ，密码 leez
- 管理员 root，密码 root

### 下载链接： [百度网盘](https://pan.baidu.com/s/1owG0KD4MkS8R6a50Kmtilw) 提取码: xxd8

---

### 下载链接： [百度网盘](https://pan.baidu.com/s/1owG0KD4MkS8R6a50Kmtilw) 提取码: xxd8


