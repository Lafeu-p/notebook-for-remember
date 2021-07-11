# svg
svg:scalable vector graphics,可缩放的矢量图
1. 该图片用代码书写而成
2. 缩放不会失真
3. 内容轻量

## 怎么使用
可以嵌入浏览器，也可以使用一个单独的文件
## 书写svg代码
### 矩形
rect
```
<rect width="100" height="100" x="100" y="100" fill="red" stroke-width="10" stroke="#000"/>
```
### 圆形
circle
```
<circle cx="300" cy="300" r="50" fill="green" stroke="yellow"/>
```
### 椭圆
```
 <ellipse rx="20" ry="10" cx="400" cy="300"/>
```
 ### 线
```
<line x1="20" x2="100" y1="100" y2="100" stroke="yellow" stroke-width="5"/>
```
### 折线
```
<polyline points="300,100,300,150,400,200,70,70" fill="none" stroke="black"/>
```
### polyline
```
<polygon points="300,300,150,150,150,450" />
```
### path  路径
M moveto
L:LineTo
