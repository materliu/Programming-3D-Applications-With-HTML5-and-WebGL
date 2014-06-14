# 3D坐标系统

如果你熟悉2D笛卡尔坐标系统
，比如说HTML文档的窗口坐标系，你就知道x和y值的含义。这些2D坐标系定义了div标签被定位在页面的哪里或者虚拟的笔刷在HTML Canvas元素上哪里绘制。相似的，意料之中，3D的绘制发生在一个3D坐标系中，3D坐标系多了一个z轴维度用来描述深度，比如说一个物体在绘制时在屏幕之内或之外多远距离。在本书中我们用到的坐标系是绘制成图表1-3那样的，x轴从左往右在水平方向延展，y轴纵向延展，z轴的正值从屏幕中穿出。如果你已经熟悉2D坐标系的概念了，过渡到3D坐标系会相当直观容易。

![Figure1-3](http://materliu.github.io/Programming-3D-Applications-With-HTML5-and-WebGL/assets/Chapter1-Introduction/figure1-3.png)

图表1-3. 一个3D坐标系；基于Creative Commons Attribution-Share Alike 3.0 unported许可

【页内标注】

WebGL定义了y轴的正向是从底部到顶部，这一点与2D Canvas API 和 CSS变换定义y轴正向往下不同。这是不幸的一点，但是这反映了两种技术的不同传统：WebGL基于长期的使用y轴正向向上的图形图像标准，Canvas和CSS基于HTML的y轴正向向下的坐标约定，而这个约定本身是久经使用的window系统的坐标体系的后代。如果你最终在一个项目中使用两种技术，你必须时刻保持对这点不同的清醒认识。如果z轴也是相反的，情况就更糟了，庆幸的是，z轴不是。