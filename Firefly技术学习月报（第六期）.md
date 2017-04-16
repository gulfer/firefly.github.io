# Firefly技术学习月报（第六期）

## 编者序

前段时间看《你要如何衡量你的人生》，里面提到一个动因理论：真正让我们乐于工作的，是工作本身的挑战性、个人认可、对工作的责任感以及获得的个人成长，而物质激励只是为工作中遇到挫折做出的补偿和安慰。这种说法似乎对工程师尤为贴切，你无法用加班费贿赂工程师去加班，反倒是抛出一个有深度的技术问题能让他们熬夜奋战，因为这具有挑战性；又比如发表技术博客，这本身就是实现个人成长的过程。这些动因是“真正”的工程师的食粮，是工作真正的“报酬”。

不过我仍然要说，请老板们多给些安慰。。。

本期重点内容涉及冷启动速度优化、Swift语法介绍、BeeHive实践、ES6相关介绍及流控工具RateLimiter解析等。另外近期将推出《从零开始学React》系列，敬请期待龙哥大作。

## 客户端

[Android：获取应用基本信息](http://blog.csdn.net/qq309909897/article/details/70186666) @胡稳安
  
  对于应用管理或者应用市场类的平台，一定需要统计应用的各种基本信息，以便对应用进行审核和管理。主要的基本信息包括应用名称、icon图标、版本号、包名、权限、签名文件摘要信息等。本文介绍两种获取应用基本信息的方法，一种基于源代码，另一种基于apk文件。

[Android应用冷启动速度优化](https://github.com/yanbo200303/studynotes/blob/master/Android%E5%BA%94%E7%94%A8%E5%86%B7%E5%90%AF%E5%8A%A8%E9%80%9F%E5%BA%A6%E4%BC%98%E5%8C%96.md) @闫波
  
  有很多Android应用在首次启动时经常会出现现黑屏、白屏或者首帧出现慢的现象，本文就冷启动的速度优化进行探讨。

[Swift可选值(Optional Values)介绍：?和!使用总结](http://www.jianshu.com/p/7a320ebaaecb) @温彦杰
  
  本文重点介绍了swift语言中的一个全新特性可选值类型(Optional Values)，结合实例总结了'？'和'！'等语法的使用场景和注意事项。

[自定义BeeHive Module](http://www.jianshu.com/p/f8316a5a9663) @朱宏飞
  
  Beehive为模块化编程提供了一种优秀的设计思路，在设计iOS 应用框架时有很好的借鉴意义。本文仿照Beehive对webview 进行了模块化封装，应用在webview 的小功能例如 白名单，js bridge 都以单独模块的方式实现，通过宏注册模块，最大化解除了代码耦合程度。

## 前端

[]() @雷双龙
  
  。

[ES2016及ESNext语法前瞻](https://github.com/BinaryDevil/Post2Share/blob/master/Technical/ESNext.md?from=singlemessage&isappinstalled=0) @李庭瑞
  
  本文将通过截取ESNext目前一些具有代表性的新语法，提前预告一下近几年Javascript语言规范、新语言特性的走向。。

[ES6 Generator](https://github.com/ToBeNumerOne/blog/blob/master/generator.md) @程晨
  
  Generator函数,作为es6推出的一种全新的函数,与普通的函数完全不同.它的基本特性使得它可以作为一种异步编程的解决方案.本文主要介绍Generator函数的基本用法以及它在异步编程时的使用方式。

## 后端

[RateLimiter解析](https://github.com/gulfer/gulfer.github.io/blob/master/RateLimiter.md) @杨朝
  
  本文对Guava提供的流控工具RateLimiter进行了代码解析，并分析了令牌桶算法的原理及实现。

[Spring源码解读：IoC容器初始化流程](https://github.com/ZmRepo/ZmRepo.github.io/blob/master/Spring%E6%BA%90%E7%A0%81%E8%A7%A3%E8%AF%BB%EF%BC%9AIoC%E5%AE%B9%E5%99%A8%E5%88%9D%E5%A7%8B%E5%8C%96%E6%B5%81%E7%A8%8B.md) @郑苗
  
  Spring通过IoC模式管理依赖关系，并将这些依赖关系注入到组件中，那么会让这些依赖关系的适配和管理更加灵活。本文从源码角度剖析Spring IoC容器初始化过程。
  
[爬取链家房源信息](https://wangzzzz.github.io/html/6/index.html) @王哲
  
  本文主要讲述了如何爬取链家房源信息，并使用MySql持久化存储信息，同时，分析了链家的登录、处理验证码等过程。


