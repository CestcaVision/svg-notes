# SVG

## 图形

rect
> * 左上角坐标 x,y
> * 宽高 width height
> * 圆角半径
圆形

circle
> * 圆心位置 cx, cy
> * 半径 r

ellipse
> * 椭圆心 cx, cy
> * 半径 rx, ry

line
> * x1,y1 x2,y2

polyline 折线
>* （x1,y1）+ (x2,y2)

polygon
> * points = 'x1 y1 x2 y2 x3 y3'

## 填充 描边和变换

* fill 填充颜色
* stroke 描边颜色
* stroke-width 边框宽度
* transform 变形

## JS操作API

* 创建图形
```
document.createElementNS(ns,circle)
```
* 添加图形（添加到DOM上）
```
element.append(childElement)
```
* 设置/获取属性：
```
element.setAttribute(name,value)
element.getAttribute(name)
```
## 坐标系统

？？？？

## SVG中的图形分组

* <g>创建分组 属性子元素继承
* <g>标签可以嵌套使用

##HSL

颜色；饱和度；亮度

www.paletton.column

##path

* 命令区分大小写 大写表示绝对位置 小写表示相对位置
* M画笔移动到的坐标 L画笔画到的坐标 H水平画 V垂直画

##弧线命令（A）

* rx ry xr 经过两点位置的椭圆参数
* laf=0，1 是否大弧线
* sf = 0,1 是否顺时针
* 终点位置（x,y）

##贝塞尔曲线命令

* P1(x,y)
* C1(x1,y1)控制点
* 二次贝塞尔曲线 Q x1 y1 x y 控制点坐标 结束位置坐标
* 三次贝塞尔曲线 C x1 y1 x2 y2 x y 
