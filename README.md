# LEDE-K2P-Build

## K2P的LEDE编译配置及预编译镜像

镜像源：[coolsnowwolf/lede](https://github.com/coolsnowwolf/lede/)

workflow来自：[P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

默认IP改为192.168.50.1，密码password

插件列表：

```
CONFIG_PACKAGE_luci-app-arpbind
CONFIG_PACKAGE_luci-app-autoreboot
CONFIG_PACKAGE_luci-app-ddns
CONFIG_PACKAGE_luci-app-firewall
CONFIG_PACKAGE_luci-app-flowoffload
CONFIG_PACKAGE_luci-app-mtwifi
CONFIG_PACKAGE_luci-app-ramfree
CONFIG_PACKAGE_luci-app-rclone_INCLUDE_rclone-webui
CONFIG_PACKAGE_luci-app-rclone_INCLUDE_rclone-ng
CONFIG_PACKAGE_luci-app-rclone_INCLUDE_fuse-utils
CONFIG_PACKAGE_luci-app-ssr-plus
CONFIG_PACKAGE_luci-app-unblockmusic
CONFIG_UnblockNeteaseMusic_Go
CONFIG_PACKAGE_luci-app-upnp
CONFIG_PACKAGE_luci-app-vlmcsd
CONFIG_PACKAGE_luci-app-vsftpd
CONFIG_PACKAGE_luci-app-wol
ipv6helper
```
