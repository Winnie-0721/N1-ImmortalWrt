# 项目简介
本固件适配斐讯 N1 旁路由模式，追求轻量（不具备 PPPoE、WiFi 相关功能）<br>
每周一0点自动开始打包<br>
如遇问题可参考本项目Wiki<br>
固件包含完整 IPv6 支持，以及下列 luci-app：<br>
[luci-app-amlogic](https://github.com/ophub/luci-app-amlogic)：系统更新、文件传输、CPU 调频等<br>
[luci-app-diskman](https://github.com/lisaac/luci-app-diskman): 磁盘管理<br>
[luci-app-dockerman](https://github.com/lisaac/luci-app-dockerman)：docker 管理<br>
[luci-app-hd-idle](https://github.com/adelolmo/hd-idle): 磁盘休眠<br>
[luci-app-nikki](https://github.com/nikkinikki-org/OpenWrt-nikki)：科学上网<br>
luci-app-samba4：存储共享<br>
luci-app-ttyd: 终端<br>
***
# 致谢
本项目基于 [ImmortalWrt-25.12](https://github.com/immortalwrt/immortalwrt/tree/openwrt-25.12) 源码编译，使用 flippy 的[脚本](https://github.com/unifreq/openwrt_packit)和 breakingbadboy 维护的[内核](https://github.com/breakingbadboy/OpenWrt/releases/tag/kernel_stable)打包成完整固件，基于nantayo的[N1-OpenWrt](https://github.com/nantayo/N1-OpenWrt)项目基础上开发的，感谢开发者们的无私分享。<br>
flippy 固件的更多细节参考[恩山论坛帖子](https://www.right.com.cn/forum/thread-4076037-1-1.html)。
