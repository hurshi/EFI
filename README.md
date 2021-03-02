# EFI

| Name         | Item                              |
| ------------ | --------------------------------- |
| CPU          | i9-9900K                          |
| Motherboard  | Asus ROG Maximus XI Hero（Wi-Fi） |
| CPU Cooler   | Noctua D15s                       |
| Memory       | USCORSAIR DDR4 3600 32GB          |
| SSD          | SAMSUNG 970 PRO 512GB (M.2)       |
| Power Supply | Corsair HX850i                    |
| WIFI & BT    | BCM943602CDP                      |



### 遇到的问题：

* 显卡始终加载得有问题

  > 看看设备名称，非独显不要用 iMac，而是 MacMini

* Bios 进入 F1 安全模式

  > 修改 RTC: [RTC综述 @xjn](https://blog.xjn819.com/post/rtc-issues-related-to-oc.html)

* 蓝牙始终加载不出来（Bluetooth Core Spec: Unknown）

  > 1. 确认在 config 中注入了蓝牙驱动
  >
  > 2. 关闭主板上的 Wi-Fi / 蓝牙

### 优秀的文章：

1. [使用 OpenCore 引导黑苹果 @xjn](https://blog.xjn819.com/post/opencore-guide.html)
2. [RTC综述 @xjn](https://blog.xjn819.com/post/rtc-issues-related-to-oc.html)
3. [精解OpenCore @黑果小兵](https://blog.daliansky.net/OpenCore-BootLoader.html)