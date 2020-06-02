# Hackintosh-LENOVO-XIAOXIN700
联想小新700（Ideapad 700-15ISK）黑苹果 CLOVER EFI

目前完美支持macOS 10.15.x

## 支持概览

- [x] 集显，完美，建议开启HiDPI获得更好的效果
- [ ] 独显，不可能实现，笔记本通病
- [ ] HDMI，待测试
- [x] USB3.0，完美
- [x] 触控板，完美，支持三指手势
- [x] 内置摄像头，完美
- [x] 内置扬声器和话筒，完美
- [ ] 耳麦插孔，只有单声道
- [x] 睡眠和唤醒，完美
- [x] Wifi、蓝牙、隔空投送、接力、随航等，需要更换BCM94360CS2网卡
- [x] 功能键，包括音量调节、亮度调节、触控板开关、屏幕开关、截屏
- [x] Facetime、iMessage、Apple Store等，完美

## 安装说明
1. 从黑果小冰的博客（<https://blog.daliansky.net>）下载最新系统镜像（Clover版）
2. 使用balenaEtcher（<https://www.balena.io/etcher/>）制作U盘镜像
3. 在BIOS中开启UEFI启动模式并关闭安全启动模式
4. 从U盘启动系统，按照提示进行安装
5. 安装完成后把efi分区下的 `/EFI/CLOVER` 替换即可
