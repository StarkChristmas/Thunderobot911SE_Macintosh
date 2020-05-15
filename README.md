# 雷神911se黑苹果EFI文件
## 结构
```
EFI
├── APPLE
│   ├── EXTENSIONS
│   └── FIRMWARE
├── BOOT
│   └── BOOTX64.efi
├── CLOVER
│   ├── ACPI
│   ├── CLOVERX64.efi
│   ├── config.plist
│   ├── drivers
│   ├── kexts
│   ├── themes
│   └── tools
└── grub
    └── grubx64.efi

11 directories, 4 files
```
## 各驱动完善情况
驱动名称|完善程度
-|-
集显(uhd630)|成功驱动
声卡(ALC269)|成功驱动
无线(BCM94352z)|成功驱动
蓝牙(BCM94352z)|成功驱动
电源|成功驱动
键盘|成功驱动
触摸板|成功驱动
睿频|成功睿频
HIDPI|成功
独显|未成功
睡眠|未成功
HDMI|未成功

> 说明一下，键盘成功驱动但键位不对，懒得折腾了直接用Karabiner-Elements软件来填补缺点，大家可以试一下。没有办法睡眠，电源电量显示是没有问题的，AirDrop和HandOff都是没有问题的，还有用AppleWatch解锁也是没有问题的。
## 关于EFI
本EFI是双系统的EFI，Macintosh+Archlinux。EFI大小是512MB。
本EFI是基于macos.10.14.6的Clover的，亲测macos10.15版本开机关机缓慢，总是出现机械硬盘关在不上的问题，所以一直停留在macos10.14.6。
