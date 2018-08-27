### CSS

以正五边形雷达图为例（其他任意正多边形也一样），如下图所示。Canvas画图的原点在左上角，以r为半径，(r, r)为圆心作圆，作为正五边形的外接圆，则正五边形每条边所对应的圆心角均为 rad = 2*Math.PI/5。再根据正余弦可以求得每个定点所对应的坐标，这样一个正五边形就可以画出来了。

![image](http://github.com/Jackson13145/canvas-radar/raw/master/原理图.png)

