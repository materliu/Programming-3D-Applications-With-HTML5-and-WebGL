# 网格，多边形和顶点

目前有很多种方式可以用来绘制3D图像，最通用的是使用网格。一个网格是通过3D空间内由(x,y,z)即顶点定义的坐标点组成的一个或多个多边形组合而成的。这些用于网格的多边形多是三边形或者四边形。3D网格又常被成为模型。

图表1-4展示了一个3D网格。四边形的黑色边线组成的网格，勾勒出了脸的形状。(在最终渲染出来的图像上你是看不到这些线的，这些线放在这里是为了方便我们说明问题。)网格上顶点的x, y, z只是定义了形状，网格表面的特性比如说颜色，阴影是通过我们很快将提到的附加属性来指定的。

![Figure1-4](http://materliu.github.io/Programming-3D-Applications-With-HTML5-and-WebGL/assets/Chapter1-Introduction/figure1-4.png)

图表1-4. 一个3D网格；基于Creative Commons Attribution-Share Alike 3.0 unported许可