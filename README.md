由 [AirScript][5] 提供的中文 CyanogenMod 社区支持。

![cyanogenmod-logo.jpg][6]

CyanogenMod 是 Android 6.0.x (Marshmallow 棉花糖) 免费自由的二次社区固件。它的目的是为您的设备提供高于普通 Android 的稳定性和可靠性。

> * 你的行为可能造成保修无效。
> * 我对设备的无法正常启动、SD卡的损坏、设备爆炸或者您因闹钟不响而被解雇不负有任何责任。
> * 如果你对包含在ROM里的功能担忧，请在刷入之前请做一些调查
> * 你将要做出一些修改，但如果你若因你的设备出现故障而责备我，我不会承担任何责任我反而会嘲笑你。

CyanogenMod 是一个基于 AOSP（Android 开源项目 Android Open Source Project）与 Android 社区里许多人维护的项目。所有的 CyanogenMod 代码都在 CyanogenMod 的 [Github][7] 上获取。如果你想向我们贡献代码，请访问 [Gerrit Code Review][8]。


----------


注意
---
 - 我们不会对以下用户提供支持或解决问题：
 - 运行第三方内核
 - 以及进入刷机模式
 - 修改系统文件
 - 不严格执行我们的步骤
 - 没有礼貌

WIKI
----

官方 CyanogenMod Wiki: [http://wiki.cyanogenmod.org/w/cancro_Info][9]

步骤
--

**第一次安装或从其他 ROM 刷入 CyanogenMod 13.0 到您的小米3/4：**

 - 阅读[官方 Wiki][10]
 - 如果你没有解锁 bootloader 的话，请先解锁
 - 通过 Fastboot 刷入第三方 recovery
 - 把 [GApps][11] 和 CM 13.0 拷入你的设备
 - 重启进入 Recovery 恢复出厂设置
 - 从你的 SD 卡刷入 CM 13.0
 - 从你的 SD 卡刷入 GApps for Marshmallow
 - 重启 （请耐心等待，“优化 apps”会花费一些时间）
 - 不要使用钛备份来恢复你的系统数据！
 - 恢复 Apps + Data 可能造成一些未知的问题，请尽量避免！

**从较早的 CyanogenMod 版本升级：**
 - 把最新的 CM 13.0 的刷机包拷入 SD 卡
 - 重启进入 Recovery
 - 从 SD 卡刷入 CM 13.0
 - 如果你遇到问题的话，可以考虑从把最近的 GApps for Lollipop 刷入
 - 重启 （请耐心等待，“优化 apps”会花费一些时间）

下载
---

最新 Nightly 版本 : [http://get.cm/get/cancro-latest.zip][12]

最新 Recovery (Nightly 版本) : [http://get.cm/get/cancro-latest-recovery.img][13]

Google Apps (arm): [http://wiki.cyanogenmod.org/w/Gapps][14]

所有版本: [http://download.cyanogenmod.org/?device=cancro][15]

BUGS
----

在 [https://jira.cyanogenmod.org/browse/NIGHTLIES][16] 提交 nightly 版本的 bugs。请记住 bugs 可能仍然在这些版本上。如果你想要稳定版，请选择 Snapshot 分支。

当前状态
-----

版本： nightlies， (12.1 snapshot)

最新的 Snapshot 版本： YOG7D

是否会获得下一个 Snapshot： 会

已知问题： 无

Security (kernel): all CVE (Common Vulnerabilities and Exposures) are fixed

Supported CMHW classes: DisplayColorCalibration.java; KeyDisabler.java; VibratorHW.java; HighTouchSensivity.java

常见问题
----

 - ROOT! ROOT! 给我 root 权限，不然我就快死了！！！ ROOT 在哪里？？？
 - 首先不要刷入任何类似于 supersu/superuser/superman 的压缩文件来获取 root 权限。请打开设置>开发者模式>Root  acces > Apps Only。
 - Gapps 在 CM 13.0 上能运行吗？
 - 请使用建议的版本。
 - 为什么今天我没有收到 nightly 更新？
 - 这个版本或 ROM 有一些问题，我决定知道我修复了这个问题为止停止发布更新。
 - 我什么时候需要清除数据？
 - 当你从其他 rom 刷入或者从 Snapshot 分支刷入 Nightly 分支时必须清除数据，反之亦然。当你从同一个更新渠道更新时并不需要清除数据（但是如果执行大版本更新，例如从 CM12.1 升级到 CM13.0 仍然建议你清除数据）。
 - 为什么不支持 TDB？
 - CyanogenMod 支持加密。如果使用 TDB 我们就不能分隔开加密的用户数据，除此以外还会导致只能运行一个系统。
 - 为什么没有 MIUI 的某个功能？
 - 因为这是 CyanogenMod。
 - 你会添加某个非 CyanogenMod 的功能吗？
 - 我不会。你可以在 gerrit 提交相关请求，在那里你的请求会被审核。

CyanogenMod 团队感谢那些参与测试，编码，修复问题和创建文章的人。祝开心！

**Mi4 LTE 不在支持范围中。**

XDA:DevDB 信息
---------------------

[OFFICIAL] CyanogenMod 13.0 - Mi4 [cancro], ROM for the Xiaomi Mi 4
-------------------------------------------------------------------

**贡献者**
[linuxxxx][17]

ROM 系统版本: 6.0.x Marshmallow

ROM 内核: Linux 3.4.x

**版本信息：**
状态: Nightly

创建于 2015-12-22

最后更新日期 2015-12-22
  [5]: https://www.airscr.com/
  [6]: https://dn-airscr.qbox.me/2015/08/2964752827.png
  [7]: https://github.com/CyanogenMod
  [8]: http://review.cyanogenmod.org/
  [9]: http://wiki.cyanogenmod.org/w/cancro_Info
  [10]: https://wiki.cyanogenmod.org/w/Cancro_Info
  [11]: https://wiki.cyanogenmod.org/w/Google_Apps
  [12]: http://get.cm/get/cancro-latest.zip
  [13]: http://get.cm/get/cancro-latest-recovery.img
  [14]: http://wiki.cyanogenmod.org/w/Gapps
  [15]: http://download.cyanogenmod.org/?device=cancro
  [16]: https://jira.cyanogenmod.org/browse/NIGHTLIES
  [17]: http://forum.xda-developers.com/member.php?u=5451053
  [18]: http://www.airscr.com/
  [19]: http://forum.xda-developers.com/mi-4/orig-development/official-cyanogenmod-13-0-mi4-t3276711
