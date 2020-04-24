# wndr3700v2-openwrt-ipks
Some supplementary packages (ipks) for official OpenWrt release

对官方发布OpenWrt固件的一些软件包（ipk）补充

You will find, in this repository, some Netgear WNDR3700v2 OpenWrt packages (ipks) compiled or collected by myself, which are usually not included in its official OpenWrt firmware.

本仓库保存个人编译（和收集）的适用于 Netgear WNDR3700v2 路由器的 OpenWrt 软件包（ipk），这些软件不包含在官方OpenWrt Release版本中。

## mentohust/锐捷认证（802.1x）客户端
源码见Google Project Hosting：https://code.google.com/archive/p/mentohust/

mentohust编译使用了[KyleRicardo/MentoHUST-OpenWrt-ipk](https://github.com/KyleRicardo/MentoHUST-OpenWrt-ipk)修改后的源码，同时提供依赖库libpcap.ipk

luci-app-mentohust使用 [BoringCat/luci-app-mentohust](https://github.com/BoringCat/luci-app-mentohust)，需要opkg安装luci-compat后才能正常使用，似乎有一个bug，会使浏览器访问luci GUI特别缓慢，反正我是卸载了还是用ssh命令了也不麻烦。
