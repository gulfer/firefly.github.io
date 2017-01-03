# Firefly技术学习月报（第四期）

## 导读

本期内容包括Android自定义相机拍照功能的实现方法、Android应用安装包size优化方法总结、Android自定义view之本地图形验证码实现方法，iOS客户端方面包括iOS旋屏开发实践分享、iOS指令集总结以及iOS逆向工程步骤总结，前端部分包括前端异步编程介绍、前端频繁出发事件的性能优化方法以及如何绘制1px边框的方法介绍，后端内容包括static关键字的执行逻辑、Hadoop学习笔记三之决策树算法实现用户风险等级分类，最后谈了谈对架构的理解。

## 客户端开发

[Android App自定义拍照](http://blog.csdn.net/qq309909897/article/details/53991430) @huwenan
  
  随着Android软硬件的不断升级，目前主流的Android手机拍照功能非常强大，尤其是分辨率不断提高，一张照片下来得3-6M。但是在有些场景下，其实不需要那么高清的图片，需要600*480甚至更小。目前笔者所在的项目就有这样的需求，需要上传一些BUG图片到服务器，本文介绍了自定义相机拍照的实现方法。

[Android应用安装包size优化](https://github.com/yanbo200303/studynotes/blob/master/Android%E5%BA%94%E7%94%A8%E5%AE%89%E8%A3%85%E5%8C%85size%E4%BC%98%E5%8C%96.md) @yanbo
  
  随着移动互联网的飞速发展，Android应用安装包的size也随之极速膨胀，目前Android应用的大小普遍为几十M甚至上百M，很影响用户体验。本文对常用的Android应用安装包的size优化的方法做一个小结。

[iOS旋屏开发实践](http://www.jianshu.com/p/6ffdc0d6928b) @wenyanjie
  
  文章总结了iOS7以后，旋屏开发的相关技巧。重点就实际开发中可能遇到的问题，导致这些问题的原因和解决思路，进行了一些开发实践的经验分享。

[自定义View——验证码](https://wangzzzz.github.io/html/3/randomview.html) @wangzhe
  
  本文主要实现了Android自定义view之本地图形验证码，从自定义View中处理wrap_conten、验证码大小的测算、验证码位置的计算、验证码、干扰线及干扰点的绘制、点击事件以及验证等方面说明了验证码View——RandomCodeView。

[iOS指令集总结](http://www.jianshu.com/p/0ea8b6c566e1) @yujinyu
  
  本文介绍了iOS开发中的各种指令集的用途和用法，并总结了与指令集相关的问题和解决方法。

[iOS 逆向工程步骤总结](http://www.jianshu.com/p/b765dd97a337) @zhuhongfei
  
  iOS逆向工程对研究iOS应用内部机制、应用安全有着非常重要的意义，逆向工程需要结合iOS端与Mac端的多种工具配合使用，本文对iOS应用逆向的过程作了一个总结。

## 前端开发

[前端异步编程](https://github.com/rayswim/blog/blob/master/src/javascript_asynchronous_programming.md) @leishuanglong
  
  本文介绍了javascript中的同步和异步模式，对javascript异步编程做了相关介绍，并通过具体事例代码比较了callback和Promise两种异步编程方案的优缺点。

[js中频繁触发事件的缓冲优化](https://github.com/gingermount/gingermount.github.io/blob/master/js%E4%B8%AD%E9%A2%91%E7%B9%81%E8%A7%A6%E5%8F%91%E4%BA%8B%E4%BB%B6%E7%9A%84%E7%BC%93%E5%86%B2%E4%BC%98%E5%8C%96.md) @jiangshan
  
  在前端的用户交互中，我们设定的触发事件会由于动作的连续触发或者短时间内大量触发而随之不断调用，造成大量的系统资源浪费，这就需要我们加以限制来优化性能，本文介绍两种常用的方法——去抖和节流。

[如何做出真正的1px边框](https://github.com/ToBeNumerOne/blog/blob/master/border.md) @chengchen
  
  由于retina屏的出现以及移动技术的发展，导致css中定义的1px边框会在retina设备上显示变粗。本文针对此问题，介绍如何在retina屏或者devicePixelRatio不等于1的屏幕上展示1px的边框。

## 后端开发

[static引发的类加载](https://github.com/ZmRepo/ZmRepo.github.io/blob/master/Static%E5%BC%95%E5%8F%91%E7%9A%84%E7%B1%BB%E5%8A%A0%E8%BD%BD.md) @zhengmiao
  
  本文从关键词static入手，延伸出对类加载机制及类初始化的剖析。

[Hadoop学习笔记三 — 决策树算法实现用户风险等级分类](http://blog.csdn.net/gloria_dandan/article/details/53983811) @zhangyidan
  
  刚刚过去的2016年被称为人工智能的元年，在AlphaGo大战李世石取得里程碑式的胜利后，神经网络和深度学习的概念瞬间进入了人们的视野，各大商业巨头也纷纷将自己的目标转移到这个还没有任何明确方向但所有人都知道它一旦出手将改变世界的人工智能方向中。在这个过程中，人们也突然发现在过去几年大数据存储技术和硬件处理能力不断发展，而产出却有限，主要是面对如此纷繁复杂的数据，人们却不知道如何利用。答案就在那里，却不知道如何寻找答案。所以数据挖掘、机器学习的算法的学习和研究又成了高度热门的话题。本文继上一篇博客中研究的KNN算法，对机器学习中另一个比较简单的算法 – 决策树算法进行学习和研究。KNN算法是基于节点之间的欧式距离进行分类，算法简单易懂，比较大的缺陷是计算量比较大而且无法给出数据的内在含义，而决策树算法相对而言在数据内在含义方面有比较大的优势，得到的结果也容易在业务上被理解。

[聊聊架构](https://github.com/gulfer/gulfer.github.io/blob/master/Architecture.md) @yangzhao
  
  本文从软件开发和团队管理两方面，探讨架构的意义和对架构的理解。


