# Netch

## 更新日志

https://github.com/NetchX/Netch/blob/master/docs/CHANGELOG.zh-CN.md

## 下载与安装

当前发布版本为免安装版本，解压后点击 Netch.exe 即可使用，目前仅支持 Windows

**注意**

- Windows 64 位系统使用 x64 版本
- Windows 32 位系统使用 x86 版本
- 否则你会遇到驱动问题

[最新版下载地址](https://github.com/netchx/Netch/releases)

## 简介

Netch 是一款 Windows 平台的开源游戏加速工具，Netch 可以实现类似 [SocksCap64](https://www.sockscap64.com/homepage/) 那样的进程代理，也可以实现 [SSTap](https://github.com/mayunbaba2/SSTap-beta-setup) 那样的全局 TUN/TAP 代理，和 [shadowsocks-windows](https://github.com/shadowsocks/shadowsocks-windows) 那样的本地 Socks5，HTTP 和系统代理。至于连接至远程服务器的代理协议，目前 Netch 支持以下代理协议：Shadowsocks，Vmess，Socks5，ShadowsocksR

与此同时 Netch 避免了 SSTap 的 NAT 问题 <escape><a name = "ref_1_s"><a href="#ref_1_d"><sup>[1]</sup></a></a></escape>，检查 NAT 类型 <escape><a name = "ref_2_s"><a href="#ref_2_d"><sup>[2]</sup></a></a></escape> 即可知道是否有 NAT 问题。使用 SSTap 加速部分 P2P 联机，对 NAT 类型有要求的游戏时，可能会因为 NAT 类型严格遇到无法加入联机，或者其他影响游戏体验的情况
