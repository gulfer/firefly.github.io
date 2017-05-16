# Firefly技术学习月报（第七期）

## 编者序

"Do not go gentle into that good night"

----不要温顺的走入那良夜

《星际穿越》让很多人对这句诗印象深刻，电影中弥留之际的老教授念叨这句诗时，颇有些悲壮、凄惨的味道，不禁感叹人类之于宇宙的渺小。不过很少有人看过第二句：

"Old age should burn and rave at close of day"

----日暮之时，年老之人应燃烧、呐喊

还挺愤青。当我们这样的“Old age”面对这样一个新陈代谢如此之快的世界，会不会像驶入宇宙一样产生恐惧，还是会在其中迸发余热？选择放弃很容易，温顺的关闭你的IDE，忘掉那些代码、模式，选择反抗黑夜太难，无数的新鲜名词、算法、理念多如繁星。其实选择往往不取决于个人意志，而是现实，现实会根据人们是否反抗，决定再允许你“burn”多久，所以其实我们并没有选择。

本期重点内容涉及Android Support Annotation简介、Swift Optional嵌套介绍、Brotli压缩算法及Paxos介绍等。

## 客户端

[Android Support Annotations简介](https://github.com/yanbo200303/studynotes/blob/master/Android%20Support%20Annotations%E7%AE%80%E4%BB%8B.md) @闫波
  
  Android Support Library是Android官方推出的支持扩展库，包含了丰富的组件和工具类。从Android Support Library 19.1版本开始，Android引入了一个新的注解库，它包含很多有用的元注解，可以很好的帮忙开发者管理代码，减少bug，本文就简要介绍一下Android Support Annotations。

[Swift Optional嵌套介绍](http://www.jianshu.com/p/5186f8a5ccba) @温彦杰
  
  本文结合swift部分源码，介绍了Optional嵌套的一些有趣用法。目的是深入了解Optional的设计思路，实际开发应避免使用。

[Android AIDL学习及使用](https://wangzzzz.github.io/html/7/index.html) @王哲
  
  本文主要讲解了使用AIDL进行Android的跨进程通信过程,并分析了AIDL的实现原理以及与Messenger的区别。

[Xcode链接中遇到的坑](http://www.jianshu.com/p/fdd07b7d068b) @朱宏飞
  
  本文主要讲述了项目组中在使用第三方库的过程当中遇到的一个问题。不同的链接参数在链接过程使用的符号查找重定向的策略是不一样的，使用-ObjC参数可能会带来一些隐藏的问题，本文主要叙述了整个查错的过程。
  
[Android签名的那些事](http://blog.csdn.net/qq309909897/article/details/72234968) @胡稳安
  
  Android App签名的目的是确保App安装包来自于原创作者，且App没有被篡改。Android手机在App安装的时候会对签名信息进行校验，只有校验通过的App才能成功安装。Android手机是如何识别App来自于原创作者且没有被篡改呢？请看App签名和验签原理。

## 前端

[外文干货译制节选之 - 使用Brotli压缩加快网站响应速度](https://github.com/BinaryDevil/Post2Share/blob/master/Technical/Brotli-Compression.md) @李庭瑞
  
  本文对一种新型的开源压缩算法Brotli进行了介绍（外文翻译）。

[css那些事儿](https://github.com/ToBeNumerOne/blog/blob/master/css.md) @程晨
  
  前端工作中，合理的使用一些css技巧可以极大程度的提高开发和维护效率。所以本文主要讲述前端开发工作中的一些css技巧，包括选择器的使用、css的命名规范、常见的布局介绍以及使用css的一些注意事项。

## 后端

[Spring源码解读：IoC容器依赖注入](https://github.com/ZmRepo/ZmRepo.github.io/blob/master/Spring%E6%BA%90%E7%A0%81%E8%A7%A3%E8%AF%BB%EF%BC%9AIoC%E5%AE%B9%E5%99%A8%E6%8E%A7%E5%88%B6%E5%8F%8D%E8%BD%AC%E5%8E%9F%E7%90%86.md) @郑苗
  
  本文从实际应用出发，解析IoC另一种高级形态的容器ApplicationContext，并分析Spring依赖反转的原理。

[Paxos与分布式](https://github.com/gulfer/gulfer.github.io/blob/master/Paxos.md) @杨朝
  
  本文对解决分布式系统中的数据一致性问题的Paxos协议及其在Zookeeper中的应用进行了介绍。


