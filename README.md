# Actions-LEDE / [Actions-OpenWrt](https://github.com/molun/Actions-OpenWrt)

[![LICENSE](https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE)](https://github.com/P3TERX/Actions-OpenWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/P3TERX/Actions-OpenWrt.svg?style=flat-square&label=Forks&logo=github)

Build OpenWrt using GitHub Actions

forked from [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)


## 说明

- 默认采用[Lean's lede](https://github.com/coolsnowwolf/lede)源码编译
- 默认IP地址：192.168.2.1
- 默认用户名：root
- 默认登录密码：password


## 用途

- 在线编译单个设备的OpenWrt固件，例如：Phicomm K2P、HiWiFi HC5962、Redmi AC2100
- 生成config.seed编译配置文件
- 用生成的config.seed文件开启 [多设备自动编译](https://github.com/molun/Auto-Build-OpenWrt) 


## 使用方法

- [Frok 本项目](https://github.com/molun/Actions-LEDE/fork) 或者点击 [使用此模板](https://github.com/molun/Actions-LEDE/generate) 创建你自己的仓库
- 点击 Actions 并授予执行权限
- 点击 Star 触发 Actions 编译流程
- 在 Actions→Build OpenWrt→Build 下查看 SSH connection to Actions 信息
________________________________________________________________________________
To connect to this session copy-n-paste the following into a terminal or browser:

ssh xnAycRt49vGC2EpVVfeAZGTVt@sfo2.tmate.io

https://tmate.io/t/xnAycRt49vGC2EpVVfeAZGTVt

After connecting you can run 'touch /tmp/keepalive' to disable the 30m timeout

________________________________________________________________________________
- 出现以上类似信息时，复制 SSH 连接命令粘贴到终端内执行，或者复制链接在浏览器中打开使用网页终端。（网页终端可能会遇到黑屏的情况，按 Ctrl + C 即可）
- cd openwrt && make menuconfig
- 完成后按快捷键Ctrl+D或执行exit命令退出，后续编译工作将自动进行


## 致谢

- [Microsoft](https://www.microsoft.com)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub](https://github.com)
- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cisco](https://www.cisco.com/)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [Cowtransfer](https://cowtransfer.com)
- [WeTransfer](https://wetransfer.com/)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)


## License

[MIT](https://github.com/molun/Actions-LEDE/blob/master/LICENSE) © molun
