# ASRock Deskmini H470/H470W

Opencore EFI &amp; macOS recovery for ASRock Deskmini H470/H470W

## Usage

1. 使用[gibMacOS](https://github.com/corpnewt/gibMacOS) 制作系统恢复镜像，引导方式选择[OpenCore](https://dortania.github.io/OpenCore-Install-Guide/) 这里使用[0.6.3](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.3) 版本
1. clone 此项目代码，拷贝EFI到系统安装盘 EFI文件夹
1. 启动，并使用在线安装方式（记得没免驱网卡的要插网线）

## After install

**IMPORTANT**

- **Update Serial Number to Enable iCloud Services and App Store**

Instructions: https://shuiyunxc.gitee.io/2020/03/16/Three/index/

## 配置清单

- OS: macOS 10.15.7 Catalina
- OpenCore: 0.6.3
- CPU: Intel® Core™ i3-10100
- Cooler: [乔思伯（JONSBO）HP400电商版](https://market.m.taobao.com/app/idleFish-F2e/widle-taobao-rax/page-detail?id=635049968042)
- RAM: [Kingston Impact DDR4 2666MHz 16GB](https://item.jd.com/67046879906.html#crumb-wrap) x 1
- SSD: [KingBank KP230 128G](https://item.jd.com/100006331038.html#crumb-wrap)
- Wi-Fi Card: Intel® 3168

## BIOS

- Disable **Secure Boot**

## Not Working

- 部分网络环境下[AirportItlwm.kext](https://openintelwireless.github.io/itlwm/) 出现网络诊断
- itlwm+[HeliPort](https://github.com/OpenIntelWireless/HeliPort) 不支持 WPA2 Enterprise
- Awake from sleep using mouse / keyboard
- 蓝牙

## 工具

- [Caffeine] 系统不休眠
- [OpenCore Configurator](http://www.macoshome.com/hackintosh/htools/2100.html)


## 其他

## 感谢

- [csrutil](https://github.com/csrutil)
- [OpenIntelWireless](https://github.com/OpenIntelWireless)
- [LewiVir](https://github.com/LewiVir/)
