# 项目简介
本固件适配斐讯 N1 旁路由模式，追求轻量（不具备 PPPoE、WiFi、Docker 相关功能）<br>
每周日0点自动开始打包<br>
如遇问题可参考本项目Wiki<br>
固件包含完整 IPv6 支持，以及下列 luci-app：<br>
[luci-app-amlogic](https://github.com/ophub/luci-app-amlogic)：系统更新、文件传输、CPU 调频等<br>
[luci-app-diskman](https://github.com/lisaac/luci-app-diskman): 磁盘管理<br>
[luci-app-podman](https://github.com/Zerogiven-OpenWRT-Packages/luci-app-podman)：podman 容器管理<br>
[luci-app-hd-idle](https://github.com/adelolmo/hd-idle): 磁盘休眠<br>
[luci-app-nikki](https://github.com/nikkinikki-org/OpenWrt-nikki)：科学上网<br>
luci-app-samba4：存储共享<br>
luci-app-ttyd: 终端<br>
***
# 致谢
本项目基于 [ImmortalWrt-25.12](https://github.com/immortalwrt/immortalwrt/tree/openwrt-25.12) 源码编译，使用 [ophub](https://github.com/ophub/amlogic-s9xxx-openwrt) 的打包工具和[内核](https://github.com/ophub/kernel)打包成完整固件，基于 [N1-OpenWrt](https://github.com/nantayo/N1-OpenWrt) 项目基础上开发，感谢开发者们的无私分享。
