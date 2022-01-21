# canvas_notes
canvas学习笔记

## 初始化实例
+ 1. 获取canvas对象
+ 2. 设置画布大小
+ 3. 获取上下文对象
+ 4. 设置画笔的起点、终点, 描边等

## api-画笔
```js
// 1.画笔
var ctx = canvas.getContext('2d')
// 2.画笔的起点
ctx.moveTo(100,100)
// 3.画直线的落脚点
ctx.lineTo(500, 100)
// 4.设置描边的颜色等
ctx.stroke()
// 5.下笔和提笔(用来绘制一个图形结束,接着再画另一种图形)
ctx.beginPath();ctx.closePath()
```
## api-线的样式
1. ctx.lineWidth;
2. ctx.lineCap; 线两端的样式 'butt'缺省,'round'圆头,'square'方头
3. ctx.strokeStyle; 描边的颜色 = 'rab(0,0,0)'; '#000'
## api-填充
1. ctx.fill();填充
2. ctx.fillStyle; 填充的颜色,默认黑色