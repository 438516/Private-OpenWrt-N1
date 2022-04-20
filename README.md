# Private-OpenWrt-N1
* **固件信息：**
默认IP: `192.168.2.254`
默认用户名: `root`
默认密码: `password`
* **使用方法：**
1. 安装固件：写入U盘直接使用；U盘启动后可输入命令 `openwrt-install-amlogic` 按照英文提示写入到emmc
2. 更新固件：将固件放在 `/mnt/mmcblk2p4/` 目录下，输入命令 `openwrt-update-amlogic` 可直接更新
3. 登录Luci界面后，可直接使用`晶晨宝盒`插件进行写入emmc或者更新操作（使用前先按需求填写好插件设置），免去手动输入命令！