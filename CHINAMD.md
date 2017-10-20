inspeckage

======

工具介绍

--------

[中文](https://github.com/ihbing/Inspeckage/blob/master/CHINAMD.md) 

[english](https://github.com/ihbing/Inspeckage/blob/master/README.md) 


一个基于Xposed 开发的应用动态分析工具 github已开源  内置web页面 体验度很不错  ‘
核心功能 监控Shared Preferences  数据  绕过SSL 可以抓到https 以及使用HOOK  过滤出很多有价值的数据


信息收集

请求权限;
应用权限
共享库
出口和非出口活动，内容提供商，广播接收机和服务;
检查应用程序是否可调试？
版本，UID和GID;
钩子

有了钩子，我们可以看到应用程序在实时中做了什么：

共享首选项（日志和文件）;
序列化;
加密;
哈希;
SQLite的;
HTTP
文件系统;
杂项（Clipboard，URL.Parse（））;
的WebView;
IPC;
钩子（动态添加新钩子）
操作

使用Xposed可以执行诸如启动未注册的活动等等操作：

开始任何活动（已导出和未导出）;
调用任何提供者（导出和未导出）;
禁用FLAG_SECURE;
SSL取消选中（绕过证书固定 - JSSE，Apache和okhttp3）;
启动，停止并重新启动应用程序;
替换参数和返回值（+ Hooks选项卡）。
