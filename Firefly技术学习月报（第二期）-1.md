# Firefly技术学习月报（第二期）

## 导读

本期内容包括Android应用截屏方法研究、单例模式以及Fluent编程风格在Android开发中的应用、Cordova安卓源码分析系列之插件初始化、可插拔式的iOS客户端log规范、Python脚本实现自动配置iOS工程证书文件方法介绍、以及对iOS深浅拷贝的研究；前端内容包括JavaScript原型解析、React组件数据存储方式介绍以及React中this关键字说明；后端内容包括微服务构建系列之Spring Boot介绍、区块链运行机制介绍及同步工具类AbstractQueuedSynchronizer原理介绍等。

## 客户端开发

[几种Android截屏方法](http://blog.csdn.net/qq309909897/article/details/52845312) @huwenan

目前自动化测试和无码数据采集都用到了一项技术：截屏。通过截屏并在远端进行绘制和播放，这样用户便可以在远端点选测试点和采集点，进而生成相关的测试脚本和采集集信息。本文介绍几个最近了解到的android截屏方法。

[单例模式和Fluent Interface在SDK开发中的应用](https://github.com/yanbo200303/studynotes/blob/master/%E5%8D%95%E4%BE%8B%E6%A8%A1%E5%BC%8F%E5%92%8CFluent%20Interface%E5%9C%A8SDK%E5%BC%80%E5%8F%91%E4%B8%AD%E7%9A%84%E5%BA%94%E7%94%A8.md) @yanbo

在SDK开发中，应用最广泛的开发模式就是单例模式，本文就单例模式的一些应用进行探讨，并讨论下FluentInterface的接口设计风格。

[可插拔式的iOS客户端log规范](http://www.jianshu.com/p/c22bb90a518f) @wenyanjie

本文分享了一篇iOS客户端的log打印规范。基于该规范，可让客户端log根据不同的功能模块，实现可插拔式的输出。

[Cordova—Android源码分析一：Cordova插件的初始化流程](https://wangzzzz.github.io/html/cordova/cordova1.html) @wangzhe

本文研究了Cordova的Android源码，分析了Cordova插件的整个初始化流程。

[Python脚本实现自动配置iOS工程证书文件](http://www.jianshu.com/p/7dc69ff347e6) @yujinyu

在实现iOS项目的自动打包工程中，我们需要配置好工程的证书文件信息，为了能够自动的根据bundle id来设置不同的profile文件，本文提供了一种通过python脚本文件修改工程project.pbxproj文件进行自动设置的方法。

[iOS深浅拷贝的思考](http://www.jianshu.com/p/93a5a85640a1) @zhuhongfei

深浅拷贝是开发当中常遇到的问题，本文针对iOS中深浅拷贝的问题进行了研究和探讨。

## 前端开发

[JavaScript原型解析](https://github.com/rayswim/blog/blob/master/src/JavaScript%E5%8E%9F%E5%9E%8B%E8%A7%A3%E6%9E%90.md) @leishuanglong

本文对JavaScript中的prototype及__proto__做了详细的解读，在JavaScript中一切皆对象，每个对象都有__proto__指向了其原型对象，每个函数又包含一个prototype属性。prototype也是一个对象，其中包含constructor属性和__proto__。JavaScript通过__proto__从null到对象间形成了一条原型链，每个对象都可以使用其上层原型对象的属性和方法。

[React组件数据存储方式](https://github.com/gingermount/gingermount.github.io/blob/master/React%E7%BB%84%E4%BB%B6%E6%95%B0%E6%8D%AE%E5%AD%98%E5%82%A8%E6%96%B9%E5%BC%8F.md) @jiangshan

本文总结了React组件存储数据的几种形式，比较了他们的异同，并给出了适合应用的场景。

[React中this关键字的说明](https://github.com/ToBeNumerOne/blog/blob/master/react%E4%B8%ADthis%E7%9A%84%E7%94%A8%E6%B3%95.md) @chengchen

随着ES6的普及，我们在开发React项目时采用ES6的形式。在项目开发过程中，我们会经常用到this关键字。本文以在项目开发过程中遇到的this指向问题为例，分析this指向原理并陈述遇到this指向问题时的解决办法。

## 后端开发

[微服务构建与部署 - Spring Boot实践](http://blog.csdn.net/baofashibukezudangde/article/details/52829969) @zhengmiao

本文对Spring Boot的基本用法进行了描述。

[区块链运行机制简介](http://blog.csdn.net/gloria_dandan/article/details/52844822) @zhengyidan

区块链是这两年来无论在技术界还是金融界都非常热门的一个概念，但是其本身涉及很多艰深的算法，学习起来也比较费劲。本文力图用比较简明的介绍区块链技术以及区块链的运行机制。

[理解AbstractQueuedSynchronizer](https://github.com/gulfer/gulfer.github.io/blob/master/AbstractQueuedSynchronizer.md) @yangzhao

本文简单介绍了工具类AbstractQueuedSynchronizer实现线程同步控制的基本原理。


