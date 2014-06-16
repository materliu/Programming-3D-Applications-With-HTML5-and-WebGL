# 变换和矩阵

3D网格是通过它们顶点的位置确定的。如果每次你想移到当前网格的另一个视角的时候都需要修改其顶点的位置将会是一件非常痛苦的事情，尤其是当这个网格不停运动的时候。也正因如此，大多数的3D系统都支持变换，通过变换，不需要遍历所有的顶点并修改其位置，仅需要修改几个相对顶点，即可移动一个网格。通过变换，我们无需修改网格顶点的任何值，即可以缩放，旋转，偏移这个网格。

![Figure1-5](http://materliu.github.io/Programming-3D-Applications-With-HTML5-and-WebGL/assets/Chapter1-Introduction/figure1-5.png)