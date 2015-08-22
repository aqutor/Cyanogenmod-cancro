由 ![AirScript][6] 提供的中文 CyanogenMod 社区支持。

![cyanogenmod-logo.jpg][7]

CyanogenMod 是一个自由的社区版本，拥有 Android 5.1.x (Lollipop)的固件分配，它可以提升你的 Android 设备的稳定性和性能。

> * 你的行为可能造成保修无效。
> * 我对设备的无法正常启动、SD卡的损坏、设备爆炸或者您因闹钟不响而被解雇不负有任何责任。
> * 如果你对包含在ROM里的功能担忧，请在刷入之前请做一些调研（或调查，原文research）
> * 你将要做出一些修改，但如果你若因你的设备出现故障而责备我，我不会承担任何责任并且嘲笑你。

CyanogenMod 是一个基于 AOSP（Android开源项目 Android Open Source Project）与 Android 社区里的其他人进行额外维护的项目。所有的 CyanogenMod 代码都在 CyanogenMod的[Github][8] 上获取。如果你想向我们贡献代码，请访问 [Gerrit Code Review][9]。


----------


注意
---
我们不会对以下用户提供支持或解决问题：
运行第三方内核
以及进入刷机模式
修改系统文件
不严格执行我们的步骤
没有礼貌

WIKI
----

官方 CyanogenMod Wiki: [http://wiki.cyanogenmod.org/w/cancro_Info][10]

步骤
--

**第一次安装或从其他 ROM刷入 CyanogenMod 12.1 到您的小米3：**

 - 阅读[官方 Wiki][11]
 - 如果你没有解锁 bootloader 的话，请先解锁
 - 通过 Fastboot 刷入第三方 recovery
 - 把 [GApps (arm)][12] 和 CM 12.1 放入你的设备
 - 重启进入 Recovery 恢复出厂设置
 - 从你的 [SD 卡][13]刷入 CM 12.1
 - 从你的 SD 卡刷入 GApps for Lollipop
 - 重启 （请耐心等待，“优化 apps”会花费一些时间）
 - 不要使用钛备份来恢复你的系统数据！
 - 恢复 Apps + Data 可能造成一些没有提到的问题，请尽量避免！

**从较早的 CyanogenMod 12.1 版本升级：**
 - 把 CM 12.1 的压缩文件放到 SD 卡
 - 重启进入 Recovery
 - 从 SD 卡刷入 CM 12.1
 - 如果你遇到问题的话，可以考虑从把最近的 GApps for Lollipop 刷入
 - 重启 （请耐心等待，“优化 apps”会花费一些时间）

下载
---

官方 CM 12.1 版本: [http://download.cyanogenmod.org/?device=cancro][14]
百度云：[http://pan.baidu.com/s/1sjDUTGx][15] （包含 Cyanogen Recovery）
Google Apps (arm): [http://wiki.cyanogenmod.org/w/gapps][16]
百度云：[http://pan.baidu.com/s/1mg3pDXm][17]

BUGS
----

在 [https://jira.cyanogenmod.org/browse/NIGHTLIES][18] 提交 nightly 版本的 bugs。请记住 bugs 可能仍然在这些版本上。如果你想要稳定版，请选择 Snapshot 分支。

常见问题
----

 - ROOT! ROOT! 给我 root 权限，不然我就快死了！！！ ROOT 在哪里？？？
 - 首先不要刷入任何类似于 supersu/superuser/superman 的压缩文件来获取 root 权限。请打开设置>开发者模式>Root  acces > Apps Only。
 - Gapps 在 CM 12.1 上能运行吗？
 - 请使用建议的版本。
 - 为什么今天我没有收到 nightly 更新？
 - 这个版本或 ROM 有一些问题，我决定知道我修复了这个问题为止停止发布更新。
 - 为什么不支持 TDB？
 - CyanogenMod 支持加密。如果使用 TDB 我们就不能分隔开加密的用户数据，除此以外还会导致只能运行一个系统。
 - 为什么没有 MIUI 的某个功能？
 - 因为这是 CyanogenMod。
 - 你会添加某个非 CyanogenMod 的功能吗？
 - 我不会。你可以向 gerrit 提交建议，在那里你的请求会被审核。

CyanogenMod 团队感谢那些参与测试，编码，修复问题和创建文章的人。祝开心！

XDA:DevDB 信息
---------------------

[OFFICIAL] Cyanogenmod 12.1 - Mi4 [cancro], ROM for the Xiaomi Mi 4
-------------------------------------------------------------------

**贡献者**
[linuxxxx][19]
ROM 系统版本: 5.0.x Lollipop
ROM 内核: Linux 3.4.x
ROM 固件要求: 至少是 MIUI 多语言 5.7.26 版

**版本信息：**
状态: Nightly

创建于 2015-07-26
最后更新日期 2015-07-26



  [6]: https://www.airscr.com/
  [7]: https://dn-airscr.qbox.me/2015/08/2964752827.png
  [8]: https://github.com/CyanogenMod
  [9]: http://review.cyanogenmod.org/
  [10]: http://wiki.cyanogenmod.org/w/cancro_Info
  [11]: https://wiki.cyanogenmod.org/w/Cancro_Info
  [12]: https://wiki.cyanogenmod.org/w/Google_Apps
  [13]: http://viglink.pgpartner.com/rd.php?r=814&m=1099149112&q=n&rdgt=1439828024&it=1440260024&et=1440432824&priceret=8.01&pg=~~3&k=241a7c323155ea01274b0f73b4ea903e&source=feed&url=http%3A%2F%2Fc%2Eaffil%2Ewalmart%2Ecom%2Ft%2Fcsepg01%3Fl%3Dhttp%253A%252F%252Fwww%2Ewalmart%2Ecom%252Fip%252FUnirex-MicroSD-High-Capacity-Card-4GB-Class-4-with-SD-Adapter%252F43743321%253Fwmlspartner%253Dpricegrabber%2Ecom%2526affcmpid%253D2919630514%2526tmode%253D0000%2526bcfg%253D00a4367205b76052a26ec27645e379fa%2526veh%253Dcse&st=feed&mt=~~~~~~~~n~~~
  [14]: http://download.cyanogenmod.org/?device=cancro
  [15]: http://pan.baidu.com/s/1sjDUTGx
  [16]: http://wiki.cyanogenmod.org/w/gapps
  [17]: http://pan.baidu.com/s/1mg3pDXm
  [18]: https://jira.cyanogenmod.org/browse/NIGHTLIES
  [19]: http://forum.xda-developers.com/member.php?u=5451053
  [20]: http://www.airscr.com/
  [21]: http://forum.xda-developers.com/mi-4/orig-development/official-cyanogenmod-12-1-mi4-t3165625