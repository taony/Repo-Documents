
#  1、Java相关概念

### ****1.1 Java的技术体系****
Sun官方所定义的Java技术体系包括以下几个组成部分：
- Java程序设计语言
- 各种硬件平台上的Java虚拟机
- Class文件格式
- Java API类库
- 来自商业机构和开源社区的第三方Java类库

Java程序设计语言、Java虚拟机、Java API类库这三部分统称为JDK（Java Development Kit），JDK是用于Java程序开发的最小环境

![image](http://imgsrc.baidu.com/forum/pic/item/ce959422720e0cf38eab06360b46f21fbc09aae2.jpg)

### 1.2 Java技术体系
1. **Java Card**：支持一些Java小程序（Applets）运行在小内存设备（如智能卡）上的平台。
2. **Java ME（Micro Edition）**：这个版本以前称为 J2ME。Java ME 为在移动设备和嵌入式设备
（比如手机、PDA、电视机顶盒和打印机）上运行的应用程序提供一个健壮且灵活的环境。
Java ME 包括灵活的用户界面、健壮的安全模型、许多内置的网络协议以及对可以动态下载的连网和离线应用程序的丰富支持。
基于 Java ME 规范的应用程序只需编写一次，就可以用于许多设备，而且可以利用每个设备的本机功能。
3. **Java SE（Standard Edition）**：Java SE 以前称为 J2SE。它允许开发和部署在桌面、
服务器、嵌入式环境和实时环境中使用的 Java 应用程序。Java SE 包含了支持 Java Web 服务开发的类，
为 Java Platform，Enterprise Edition（Java EE）提供基础。
4. **Java EE（Enterprise Edition）**：这个版本以前称为 J2EE。企业版本帮助开发和
部署可移植、健壮、可伸缩且安全的服务器端 Java 应用程序。Java EE 是在 Java SE 的基础上构建的，
它提供 Web 服务、组件模型、管理和通信 API，可以用来实现企业级的面向服务体系结构（service-oriented architecture，SOA）和 Web 2.0 应用程序。
### 1.3 Java发展史
![image](http://www.kuqin.com/upimg/allimg/120922/1T4294I5-9.png)
- 1991年4月：Java前身Oak
- 1995年5月23：更名Java，发布Java1.0
- 1996年1月23日：JDK1.0发布，提供Sun Class VM
- 1996年4月：首届Java One大会
- 1997年2月19日：Sun发布JDK1.1
- 199912月4日：JDK1.2，拆分3个方向，J2M3、J2SE、J2EE
- 1999年4月27日：HotSpot虚拟机发布
- 2000年5月8日：JDK1.3发布
- 2002年2月13日：JDK1.4发布，2002年微软.Net Framework发布
- 2004年9月30日：JDK1.5发布
- 2006年12月11日：JDK1.6发布，启用Java SE6、Java EE 6、Java ME6
- 2006年11月13日：JavaOne大会上，SUN公司宣布Java开源，建立OpenJDK组织管理开源代码
- 2009年2月19日：JDK1.7完成第一个里程碑版本
- 2009年4月20日，Oracle公司74亿美元收购Sun公司，Java商标归Oracle所有。
- 2011年7月：JDK1.7发布
- 2014年3月19日：JDK1.8发布
- 2017年：将发布JDK1.9

### 1.4 Java虚拟机发展史
1. Sun Classic/ Exact VM
2. Sun HotSpot VM
3. Sun Mobile-Embedded VM / Meta-Circular VM
4. BEA JRockit / IBM J9 VM
5. Azul VM / BEA Liquid VM
6. Apache Harmony / Google Android Dalvik VM
7. 1.4.7　Microsoft JVM及其他
