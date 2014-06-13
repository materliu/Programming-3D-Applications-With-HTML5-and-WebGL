# 浏览器平台

虽然HTML5为Web带来了富图形图像，但是如果没有必要的浏览器发展的支持便会毫无意义。实际上，是一系列的提升，为HTML5开发富互联网应用铺平了道路：

JavaScript虚拟机性能
    
    WebGL和Canvas2D都是JavaScript API；背后的JavaScript代码能跑多快，意味着动画和交互可以多快。几年前，虚拟机的性能问题让3D开发不能在实践应用中得以推广。谢天谢地，如今的虚拟机很给力。
	
混合加速

    浏览器要负责在页面上把各种元素迅速混合，并且不能有视觉痕迹。随着内容动态效果越来越强，浏览器在混合上也取得了巨大进步，包括对2D和3D等所有视觉元素使用3D硬件渲染。

动画支持

    在驱动动画上，通过引入了requestAnimationFrame()函数取代setInterval()和setTimeout()来进行提升。这个新方法可以大大提升性能，并通过允许开发者使用浏览器重绘内置页面元素的同一通道来重绘canvas元素的内容来消除视觉痕迹。

HTML5浏览器同时也包含了一些其他的特性，比如说多线程编程(Web Workers)，全双工TCP/IP网络(WebSockets)，本地数据存储，以及更多的开发者可以用来创造世界级应用的功能。这些特性和WebGL, CSS3 3D,以及Canvas元素一起提供了一个革命性的新平台，借助这个平台我们可以在任何计算机和设备上构建相关的视觉程序。

图表1-2展示了一个运行在Firefox开发版下的Epic公司的游戏Epic Citadel的演示版本。 Epic Citadel使用WebGL来渲染图形，但是真正让其与众不同的是在游戏引擎性能上的重要技术成就。这款游戏使用了Epic的Unreal引擎的一个版本，Unreal引擎最初是依赖于操作系统代码的C++程序，通过使用Emscripten 编译器和asm.js，被移植到了浏览器上，asm.js是一个新的被优化的底层JavaScript子级。只需简单的输入一个URL，浏览器用户就能获得一个美丽渲染的全屏的以每秒60帧率运行的操作游戏体验，而这只需很少的下载时间同时还不需要安装。

![Figure1-2](http://materliu.github.io/Programming-3D-Applications-With-HTML5-and-WebGL/assets/Chapter1-Introduction/figure1-2.jpg)
	