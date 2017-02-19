# svg

## 简介

### 1. 元素

|形状|元素|属性|
|:--|:--|:--|
||svg||
||g||
||def||
||use||
||text||
||image||
|矩形| rect | x,y,width,height,rx,ry |
|圆形| circle | r,cx,cy |
|椭圆| ellipse | rx,ry,cx,cy |
|直线| line | x1,y1,x2,y2 | 
|折线| polyline | points |
|多边形| polygon | points |
|路径| path | |

### 2. 属性
#### stroke
0. stroke-width 轮廓的宽度
1. stroke-linecap 设置轮廓结尾处的渲染方式，value有butt(直接一刀切断)、square(保留一点切断)、round(圆弧切断) 3个设置值；
2. stroke-linejoin  用于设置两条线之间的连接方式，value有miter(尖角连接)、round(圆弧连接)、bevel(切断连接) 3个设置值；
1. stroke-miterlimit 表示描边相交（锐角）的表现方式。默认大小是4. 
2. stroke-dasharray 表示虚线描边。可选值为：none, <dasharray>, inherit. 其中，none表示不是虚线；<dasharray>为一个逗号或空格分隔的数值列表。表示各个虚线端的长度。可以是固定的长度值，也可以是百分比值；inherit表继承。
3. stroke-dashoffset 表示虚线的起始偏移。可选值为：<percentage>, <length>, inherit. 百分比值，长度值，继承。
4. stroke-opacity 表示描边透明度。默认是1.

#### fill
1. fill-opacity
2. fill-rule
3. nonzero
4. evenodd

#### transform
0. translate
1. rotate
2. scale
3. skew
4. matrix

#### animation
1. set
2. animate
3. animateTransform
4. animateMotion

## 主要内容
1. [进度条](loading.html)


## 参考 
1. [那些有趣的svg](http://www.hongkiat.com/blog/svg-animations/)
2. [图片转换为svg](http://image.online-convert.com/convert-to-svg)
