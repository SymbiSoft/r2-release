# [R2](R2.md) Symbian平台GoogleReader客户端 #



[![](http://r2-release.googlecode.com/svn/trunk/sharesina.png)](http://v.t.sina.com.cn/share/share.php?url=http://code.google.com/p/r2-release/&title=&appkey=2924220432)

[![](http://open.t.qq.com/apps/share/images/s/b32.png)](http://v.t.qq.com/share/share.php?url=http://code.google.com/p/r2-release/&appkey=appkey&site=&pic=&title=R2(googlereader-for-symbian))



## 介绍 ##
[R2](R2.md)是一个Qt Quick开发的symbian平台Google Reader客户端.支持s60 v3,v5以及symbian^3机型，R2致力于打造一个symbian平台的拥有更好的用户体验的googlereader客户端,同时R2是开源和免费的，对用户更加友好。



![http://farm6.static.flickr.com/5049/5312107424_415152fa7e.jpg](http://farm6.static.flickr.com/5049/5312107424_415152fa7e.jpg)

![http://farm5.static.flickr.com/4079/5441386420_390096953a_z.jpg](http://farm5.static.flickr.com/4079/5441386420_390096953a_z.jpg)

更多截图在这里 http://www.flickr.com/photos/8328812/tags/mobile/

以及这里 http://www.flickr.com/photos/8328812/sets/72157626037873922/



## 功能列表 ##

  1. 根据标签浏览订阅列表
  1. 支持已读列表和未读列表的显示
  1. 文章显示支持图片和链接，支持导航键左右滚动快速浏览
  1. 支持数据缓存，离线浏览
  1. 文章分享
  1. 文章加注星标
  1. 文章收藏
  1. 文章邮件转发
  1. 文章加注笔记分享
  1. 笔记记录，离线笔记

## 支持机型 ##

  * s60 v3非触摸机型

NOKIA官方声明支持的机型： E72, E71, E66, E63, E52

不过我在5320上测试也成功了，理论上V3 FP1机型以上都可以支持

  * 触摸机型

包括s60 v5和symbian^3（N8，C6-01，C7）

  * 要确认你的机型是否支持，请参见：http://www.forum.nokia.com/Devices/


## 安装说明 ##

  * s60 v3非触摸机型

确认你的机型在支持范围内

下载安装 Qt Runtime [ftp://ftp.qt.nokia.com/qt/symbian/4.7.1/qt_installer.sis](ftp://ftp.qt.nokia.com/qt/symbian/4.7.1/qt_installer.sis)

（如果你想看看qt的更多演示应用，可以安装ftp://ftp.qt.nokia.com/qt/symbian/4.7.1/ 目录下的demo程序）

下载安装 [R2](R2.md).sis安装文件 http://code.google.com/p/r2-release/downloads/list

  * S60 V5机型

下载安装 Qt Runtime [ftp://ftp.qt.nokia.com/qt/symbian/4.7.1/qt_installer.sis](ftp://ftp.qt.nokia.com/qt/symbian/4.7.1/qt_installer.sis)

下载安装 [R2](R2.md)-Touch.sis安装文件 http://code.google.com/p/r2-release/downloads/list

  * symbian^3机型

[R2](https://code.google.com/p/r2-release/source/detail?r=2)-Touch需要qt4.7.1的支持， 目前symbian<sup>3机型还是内置qt4.6.3,如果想体验R2-Touch，需要安装Qt4.7.1的运行环境，注意，目前在symbian</sup>3上的qt4.7.1版本还属于beta状态，除非你认为自己有能力处理试用beta版本带来的麻烦，否则不要进行实验。
在windows版本的qtsdk1.1中，提供了qt4.7.1的symbian^3安装文件,也可以在本站下载列表下载。


qt程序目前在扩展卡启动有点问题，请安装到内存卡上。

## 已知问题 ##

FontRouter和基于Symbian的Qt之间冲突，http://code.google.com/p/r2-release/issues/detail?id=2
如果你的机器安装了FontRouter，那么不能安装QT，否则会进入重启的恶性循环，如果你真的下定决心要在你的手机上体验QT，那么先卸载FontRouter。

## 隐私声明 ##

当前版本采用google clientLogin登录google reader，[R2](R2.md)在首次运行时需要输入帐号和密码，R2保证不会收集您的个人私密信息，若对此不能认可，请暂停使用[R2](R2.md)，




