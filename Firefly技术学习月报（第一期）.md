# Firefly技术学习月报（第一期）

***

## 导读
Firefly团队技术学习月报第一期，今后将每月定时更新。本期内容包括Android开发中图片加载的内存优化及WebView资源拦截解析研究；iOS内容包括iOS设备表示演进过程、iOS工程添加cordova并实现自定义JS插件研究，以及iOS自动打包相关问题总结；前端内容包括React组件通信相关研究及Cordova源码解读；后端内容包括Java编码相关问题总结、MapReduce工作原理研究及Lambda与匿名类比较等。

***

## Android开发

[图片加载库的内存注意事项](https://github.com/yanbo200303/studynotes/blob/master/%E5%9B%BE%E7%89%87%E5%8A%A0%E8%BD%BD%E5%BA%93%E7%9A%84%E5%86%85%E5%AD%98%E6%B3%A8%E6%84%8F%E4%BA%8B%E9%A1%B9.md) @yanbo

本文讨论了一些Android开发过程中碰到的图片加载的内存优化点。

[WebView资源拦截解析](https://wangzzzz.github.io/html/1/webview.html) @wangzhe

本文主要研究了使用Android WebView组件时，不同的请求所经过的不同方法，同时，讲解了对WebView资源、请求的拦截以及资源本地化缓存。

***

## iOS开发

[iOS设备标识演进](http://kmplayer.iteye.com/blog/2323188) @wenyanjie

本文详尽地总结了iOS设备标识在各iOS版本的演进和iOS各种设备标识的特性。基于对设备标识的准确认识，iOS开发人员应该基于设备标识的实际用途，正确选用iOS设备标识。

[添加cordova到现有iOS工程并实现自定义JS插件](http://www.jianshu.com/p/a137cf01d125) @yujinyu

本文介绍了如何将cordova工程作为现有ios工程的一个组件来使用，并在此基础实现了cordova自定义插件的开发，并附上源代码在github上的下载地址。

[iOS自动打包的若干坑](http://www.360doc.com/showWeb/0/0/590188308.aspx) @zhuhongfei

由于苹果公司的封闭性，iOS自动打包在使用中遇到各种奇怪的错误，本文主要对经历过的各种各样的坑进行了总结。

***

## 前端开发

[React Components之间如何进行通信](https://github.com/rayswim/blog/blob/master/src/React%20Components%E4%B9%8B%E9%97%B4%E5%A6%82%E4%BD%95%E8%BF%9B%E8%A1%8C%E9%80%9A%E4%BF%A1.md) @leishuanglong

基于React的应用本质上是一堆Component的复合，那么在程序中不可避免的会遇到组件间的通信。我们根据组件的在组件树中所在的level可以把组件间通信分为如下四中形式:父组件与子组件通信、子组件与父组件通信、兄弟组件间通信、任意组件间通信。本文针对这四种场景分别介绍了常用的组件间通信的方法。

[Cordova简介](https://github.com/ToBeNumerOne/cordova/blob/master/cordova.md) @chengchen

本文主要讲述了对cordova的初步认识以及针对cordova.js的源码解读。其中主要包括了cordova.js中的模块化机制、事件机制以及js和native交互的实现。

[React组件之间的通信](https://gingermount.github.io/blog/blog_1.html) @jiangshan

***

## 后端开发

[Hadoop学习笔记-MapReduce工作原理](http://blog.csdn.net/gloria_dandan/article/details/52511060) @zhangyidan

本文从一个初学者的角度出发，用通俗易懂的语言介绍Hadoop中MapReduce的工作原理，在介绍MapReduce工作原理前，本文先介绍HDFS的工作原理及架构，再介绍MapReduce的工作原理以及Shuffle的过程。

[那些年挖过的Java坑](http://blog.csdn.net/baofashibukezudangde/article/details/52511117) @zhengmiao

近两年接触Java开发，负责移动开发框架的服务端设计和实现，其中免不了挖些大大小小的坑。当项目落地实施或者做性能分析才发现，我们在编写Java代码时候多了解我们使用到的数据结构或工具的原理，就能大大提高代码的质量，一定程度上就能避免这些坑的产生。以下从代码优化的角度细说产生的原理以及个人的一些优化建议。

[Lambda与匿名类](https://github.com/gulfer/gulfer.github.io/blob/master/Lambda%20And%20Anonymous%20Class.md) @yangzhao

本文对Java8中的Lambda表达式与匿名类从功能、性能等方面进行了简单比较。