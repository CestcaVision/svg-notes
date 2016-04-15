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
