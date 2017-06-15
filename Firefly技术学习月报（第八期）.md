# Firefly技术学习月报（第八期）

## 编者序

《人类简史》告诉我们一个道理，人类社会所有大规模分工协作所依赖的秩序都是来源于虚构的想像，比如宗教、国家、人权、法律等等都是人们虚构出来的，这些虚构的事物却能够比武力等手段更加有效的促进协作。

本期重点内容涉及Android最新官方语言Kotlin简介、Swift编程经验介绍、测量和优化单页应用程序（SPA）渲染页面效率方案翻译及分布式事务介绍等。

## 客户端

[Kotlin学习笔记-环境搭建](https://github.com/yanbo200303/studynotes/blob/master/Kotlin_study/Kotlin%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0-%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA.md) @闫波
  
  在2017年5月的Google IO大会上，Google宣布Kotlin成为Android的官方语言，随后的2017年6月的TIOBE排行榜中，Kotlin就首次挤进了编程语言TOP50，可见Kotlin的爆发之迅速。作为一个Android开发者需要立刻学习这门新的语言，本文是Kotlin学习笔记的第一篇。

[swift开发：map和flatMap使用](http://www.jianshu.com/p/3415844efdd9) @温彦杰
  
  本文基于源码实现和代码示例，深入介绍了Swift语言中map和flatmap的实现机制和使用注意事项，并进一步对Functor和Monad的设计概念作了基本介绍。

[RecyclerView使用详解](https://wangzzzz.github.io/html/8/index.html) @王哲
  
  本文详细讲解了RecyclerView的使用说明，包括RecyclerView的基本使用，添加头部、尾部布局，加载更多，添加、删除Item的动画，item的点击和长按事件的实现、分割线的实现等。

[iOS 视图的核心—图层](http://www.jianshu.com/p/e3bbf45907b2) @朱宏飞
  
  在iOS开发当中，我们所接触到的所有视图都继承来自UIView类。UIView在底层实现中将视图的绘制工作与触摸事件的响应进行了分离。UIView并不直接完成视图的绘制工作，它将视图的绘制交给了图层来完成。直接操作图层能够实现某些特殊的显示效果，本文将对图层的使用进行介绍。
  
[Android App加固原理分析](http://blog.csdn.net/qq309909897/article/details/73273964) @胡稳安
  
  对App进行加固，可以有效防止移动应用被破解、盗版、二次打包、注入、反编译等，保障程序的安全性、稳定性。对于金融类app，尤其重要。本文主要以dex加固为例介绍App加固的原理。

## 前端

[外文干货译制节选之 - 使用RUM度量和优化单页应用程序的性能](https://github.com/BinaryDevil/Post2Share/blob/master/Technical/RUM-SPA-Optimization.md) @李庭瑞
  
  本文主要介绍LinkedIn测量和优化单页应用程序（SPA）渲染页面效率的方案。

[javascript异步机制](https://github.com/ToBeNumerOne/blog/blob/master/js-async.md) @程晨
  
  一道setTimeout面试题引发的对javascript异步机制、setTimeout运行机制的思考与说明。

## 后端

[Spring源码解读：Spring及其设计模式](https://github.com/ZmRepo/ZmRepo.github.io/blob/master/Spring%E6%BA%90%E7%A0%81%E8%A7%A3%E8%AF%BB%EF%BC%9ASpring%E5%8F%8A%E5%85%B6%E8%AE%BE%E8%AE%A1%E6%A8%A1%E5%BC%8F.md) @郑苗
  
  本文从设计的角度去剖析Spring源码，从中学习Spring的代码架构及设计原则。

[分布式事务](https://github.com/gulfer/gulfer.github.io/blob/master/DistributedTransaction.md) @杨朝
  
  本文结合支付宝相关材料讨论了分布式事务的几种实现思路。


