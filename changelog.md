# 更新日志

### 2019-05-07
- 现在使用`VirtualSMC(1.0.3)`替代`FakeSMC`.
- 默认使用防误触的触摸板驱动 VoodooPS2Controller(1.9.2) + VoodooI2C(2.1.5).
- 更新Lilu系列驱动.
- 添加了博通蓝牙参数`bpr_probedelay=100` `bpr_initialdelay=300` `bpr_postresetdelay=300`.

### 2019-04-03
- 日常更新Lilu系列

### 2019-03-27
- 更新clover到`4898`版本，支持10.14.4

### 2018-11-09
- 日常驱动更新`WhateverGreen.kext`、`AppleALC.kext`和`Lilu.kext`

### 2018-09-26
- 添加`USBPower.kext`替代`SSDT-UIAC.aml`和`USBInjectAll.kext`
- 添加`agdpmod=pikera`启动参数patch HDMI,移除 `NvidiaGraphicsFixup.kext`


### 2018-09-20 (距离正式版本推送还有5天,此版本已经在GM上正常使用了)
- 初始化配置
- 兼容10.13.x，可以从High Sierra无痛升级10.14
