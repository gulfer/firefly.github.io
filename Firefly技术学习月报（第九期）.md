# Firefly技术学习月报（第九期）

## 编者序

万维钢老师最近介绍了一本新书《端粒效应》，说的是人的寿命与端粒的长度有关系。端粒是染色体末端的DNA序列，每次细胞分裂端粒就会缩短，短到一定程度细胞也就不能分裂了，进而细胞、组织、器官也就步入衰退阶段。很有意思的是，端粒的长短跟一种叫“端粒酶”的酶的数量成正比，而压力会抑制机体制造这种酶，也就是说，总是持续一种高压力状态，是会折寿的。所以广大码农同胞，如果还想多活两年，想办法给自己减减压吧。

本期重点内容包括Kotlin学习笔记系列文章、iOS客户端数据存储使用总结、iOS网络请求缓存机制分析，以及前端技术ES8新特性一览等。

## 客户端

[Kotlin学习笔记-基本语法](https://github.com/yanbo200303/studynotes/blob/master/Kotlin_study/Kotline%E5%9F%BA%E6%9C%AC%E8%AF%AD%E6%B3%95.md) @闫波
  
  在2017年5月的Google IO大会上，Google宣布Kotlin成为Android的官方语言，随后的2017年6月的TIOBE排行榜中，Kotlin就首次挤进了编程语言TOP50，可见Kotlin的爆发之迅速。作为一个Android开发者需要立刻学习这门新的语言，本文是Kotlin学习笔记的第二篇，本篇讲讲Kotlin的基本语法。

[iOS客户端开发数据存储使用总结](http://www.jianshu.com/p/d8b980b41de4) @温彦杰
  
  本文介绍了iOS客户端常用的数据存储技术，重点以Firefly_iOS为例，总结了这些数据存储技术的使用场景和相关使用经验。

[Android——一次选取本地相册多张图片](https://wangzzzz.github.io/html/4/index.html) @王哲
  
  本文详解了Android如何从本地相册选取图片，介绍了mvp模式，以及GridView使用过程中遇到的问题。

[iOS 网络请求缓存机制分析](http://www.jianshu.com/p/1972754dc325) @朱宏飞
  
  网络请求使用缓存技术可以有效地减少网络数据的交互量，缩短页面的加载时间。iOS提供了多种缓存策略来配置网络请求，使用正确的策略可以有效地减少服务器压力，提升用户体验。当然，如果我们明白缓存技术的原理后，我们完全可以根据需求自定义缓存策略。

## 前端

[[译]JavaScript Async/Await 秒杀 Promise 的6个理由（教学向）](http://www.jianshu.com/p/c5baedf1c66c?utm_campaign=hugo&utm_medium=reader_share&utm_content=note&utm_source=weixin-friends) @李庭瑞
  
  处理异步请求一直是Javascript编程中重要的一环，但是随着技术的进步，处理的方法一直也在变化。本文将比较Async Await与Promise的优劣，阐述前者的优势。

[ES8 新特性一览](https://github.com/ToBeNumerOne/blog/blob/master/es8.md) @程晨
  
  本文主要介绍最新的Javascript版本（ES2017）的一些新特性。

## 后端

[DevOps学习心得](http://blog.csdn.net/qq309909897/article/details/75213780) @胡稳安
  
  DevOps狭义的概念是开发运维一体化，强调软件开发和运维团队之间更好的沟通协作，以便更快更高质量的软件交付。广义的讲，DevOps是一种文化，流程和实践，覆盖整个软件开发的全生命周期和所有干系人。强调项目经理、研发、测试和运维人员思维转变，更好的协作和更紧密的整合。通过自动化的流程，使得构建、测试、发布软件更加地快捷、频繁和可靠。最终的目的是提高软件质量、缩短交付周期，甚至于像工厂的流水线一样，扣动按钮，即可实现自动化的、持续的软件交付。

[JDK动态代理原理](https://github.com/ZmRepo/ZmRepo.github.io/blob/master/JDK%E5%8A%A8%E6%80%81%E4%BB%A3%E7%90%86%E5%8E%9F%E7%90%86.md) @郑苗
  
  对于Spring的核心AOP来说，核心原理就是java的动态代理机制，而动态代理模式也是较常用的设计模式之一，了解它的实现原理有助于我们提高自身代码架构水平。本文以Java中的动态代理运行机制出发，推演其内部实现原理。

[分库分表实践](https://github.com/gulfer/gulfer.github.io/blob/master/Zdal.md) @杨朝
  
  本文介绍了分库分表的常见思路及分库分表框架Zdal的使用示例。


