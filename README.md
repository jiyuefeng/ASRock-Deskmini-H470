# ASRock Deskmini H470

Opencore EFI &amp; macOS recovery for ASRock Deskmini H470

## Usage

1. 使用[gibMacOS](https://github.com/corpnewt/gibMacOS) 制作系统恢复镜像，引导方式选择[OpenCore](https://dortania.github.io/OpenCore-Install-Guide/) 这里使用[0.6.3](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.3) 版本
1. clone 此项目代码，拷贝至 以上系统安装盘 EFI文件夹
1. 启动，并使用在线安装方式（记得没免驱网卡的要插网线）

## After install

**IMPORTANT**

- **Update Serial Number to Enable iCloud Services and App Store**

Instructions: https://shuiyunxc.gitee.io/2020/03/16/Three/index/

## Specifications

- OS: macOS 10.15.7 Catalina
- OpenCore: 0.6.3
- CPU: Intel® Core™ i3-10100
- RAM: Kingston Impact DDR4 2666MHz 8GB x 1
- SSD: KingBank KP230 128G
- Wi-Fi Card: Intel® 3168

## BIOS

- Disable **Secure Boot**

## Not Working

- Audio jack, front panel
- Awake from sleep using mouse / keyboard

## 工具
- [OpenCore Configurator](http://www.macoshome.com/hackintosh/htools/2100.html)

## 其他
- 部分网络环境下[AirportItlwm.kext](https://openintelwireless.github.io/itlwm/) 出现网络诊断
- itlwm+[HeliPort](https://github.com/OpenIntelWireless/HeliPort) 不支持 WPA2 Enterprise

## 感谢

[csrutil](https://github.com/csrutil)
[OpenIntelWireless](https://github.com/OpenIntelWireless)
[LewiVir](https://github.com/LewiVir/)
