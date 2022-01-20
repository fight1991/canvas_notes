# canvas_notes
canvas学习笔记

## 初始化实例
+ 1. 获取canvas对象
+ 2. 设置画布大小
+ 3. 获取上下文对象
+ 4. 设置画笔的起点、终点, 描边等

## api
```js
1. var ctx = canvas.getContext('2d') // 画笔
2. ctx.moveTo(100,100) // 画笔的起点
3. ctx.lineTo(500, 100) // 画直线的落脚点
4. ctx.stroke() // 设置描边的颜色等