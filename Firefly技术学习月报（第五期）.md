# Firefly技术学习月报（第五期）

## 编者序

最近在家门口看到一则张贴广告：电脑专修、手机专修，曾几何时这也是热门的手艺，现在基本上无人问津了吧，其实我们现在所从事的很多工作，焉知若干年后同样被淡忘。我们编写的代码，设计的框架，无非是告诉用户（开发人员）两条：什么可以做、什么不能做，当技术上的约束和规范不断被强化、固化，开发的思维和定式被融入到开发所需的基础设施，最终会以傻瓜式工具的形态交付给用户。也许到时候我们在电线杆上看到的广告就是：后端程序员、前端程序员了。

本期重点内容涉及代码扫描、移动应用数据采集、HTTPS相关知识及前端开发基础知识等。

## 客户端

[Android静态代码扫描-自定义规则](http://blog.csdn.net/qq309909897/article/details/62219479) @胡稳安
  
  Android提供了一个代码检查工具Android Lint，能够对项目中潜在正确性、安全性、性能、可用性、可访问性、国际化等问题和隐患进行检查，并生成html和xml两种文件的扫描报告。Android Lint提供了6大类共200多条检查项，并对每个检查项指定了严重等级。如果需要搭建一个企业内部的Android静态代码扫描工具，直接使用Android自带的Android Lint检查是不够的，会有大量的误报和漏报。因此需要根据企业内部的开发规范、技术框架特性和业务特点制定自己的Lint检查规则，本文对Android静态代码扫描的自定义规则进行研究及探讨。

[移动应用数据采集](https://github.com/yanbo200303/studynotes/blob/master/data_collection/%E7%A7%BB%E5%8A%A8%E5%BA%94%E7%94%A8%E6%95%B0%E6%8D%AE%E9%87%87%E9%9B%86.md) @闫波
  
  随着移动互联网的飞速发展，通过数据分析缺点移动应用的迭代已是每个应用必不可少的手段。做数据分析的首要条件就是进行数据采集，本文就对移动应用数据采集的进行探讨。

[iOS中HTTPS证书验证浅析](http://www.jianshu.com/p/b909a9223c3b) @温彦杰
  
  本文深入浅出介绍了HTTPS的基本机制，重点介绍了iOS中实现HTTPS的具体方法和相关实践代码。

[使用JAVA爬取北京豆瓣租房小组租房信息](https://wangzzzz.github.io/html/5/index.html) @王哲
  
  本文主要介绍了如何使用Java根据关键词爬取北京豆瓣租房小组上的租房信息，使用OKhttp作为网络请求的客户端，使用Jsoup解析网页的html，最终的结果使用csv进行存储。

[BeeHive框架实现原理分析](http://www.jianshu.com/p/7546ef8743b8) @朱宏飞
  
  BeeHive是阿里开源的一个iOS平台模块化编程的实现方案，本文对BeeHive的设计思路及实现原理进行分析。

## 前端

[JavaScript关键字this](https://github.com/rayswim/blog/blob/master/src/this_in_javascript.md) @雷双龙
  
  在JavaScript中，this的指向是在函数执行时确定的。正式由于这种特性，this指向问题才成了很多人困扰的问题。只有深刻理解JavaScript中的关键字this，才真正算是入门JavaScript。借住理解this，我们可以深入去了解JavaScript函数的执行环境，而这是理解闭包等其他概念的基础。

[Apollo Mobile Framework With MobX](https://github.com/BinaryDevil/Post2Share/blob/master/Technical/React-Mobx.md) @李庭瑞
  
  这是一个将MobX与FIREFLY平台现有apollo-mobile开发框架结合的Demo。MobX是一个负责状态(state)管理的JS库，并且有针对react的版本mobx-react。 这篇文章将从React的状态管理角度入手，阐述引入MobX的优势和方法。

[浅谈HTTPS的安全](https://github.com/ToBeNumerOne/blog/blob/master/https-cookie-session.md) @程晨
  
  本文是一篇有关HTTPS安全的科普文章.重在介绍HTTPS较于HTTP是如何实现安全通信的,以及讲解涉及到HTTPS安全方面的一些基本概念。

## 后端

[SpringBoot配置加载机制及扩展](https://github.com/ZmRepo/ZmRepo.github.io/blob/master/SpringBoot%E9%85%8D%E7%BD%AE%E5%8A%A0%E8%BD%BD%E6%9C%BA%E5%88%B6%E5%8F%8A%E6%89%A9%E5%B1%95.md) @郑苗
  
  本文主要解析了SpringBoot加载配置文件的逻辑，并实现了自定义对Json语法的配置支持。最后对配置文件的使用做了示例说明。

[SQL性能优化－upper函数](http://www.jianshu.com/p/7b72b0e0d29b) @余进玉
  
  最近对生产上最为耗时的几条sql语句进行分析优化，发现最为耗时的几条sql中都出现了upper函数，通过分析它们的执行计划初步估计是由于upper函数的使用导致的性能低下，所以选其中一条比较简单的sql进行了测试和分析，并给出了优化方案。

[Java动态代理](https://github.com/gulfer/gulfer.github.io/blob/master/DynamicProxy.md) @杨朝
  
  本文简要介绍了Java动态代理的原理和几种实现方式。


