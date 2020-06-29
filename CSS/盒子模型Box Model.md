# 盒子模型Box Model

![BoxModel](D:\workspace-web\css\img\BoxModel.gif)

#### CSS盒模型各部分分别是：

- `margin`  外边距，边框外的区域

- `border`  边框，外边距和内边距之间的区域
- `padding`  内边距，盒子内容和边框之间区域
- `content`  盒子内容，如文本和图像

各方向上的样式均可单独设置。



## 边框border属性

`border-style`  设置边框样式，属性值：

- `dotted`  点线
- `dashed`  虚线
- `solid`  实线
- `double`  双重边框
- `groove`  3D沟槽
- `ridge`  3D脊
- ...



`border-width`  设置边框宽度，属性值：`length`或 `thick` / `medium`(默认) / `thin`



`border-color`  设置边框颜色



`border`  简写属性，无顺序要求，可设`width` 、`style` 、`color`



## 外边距margin

属性值可用 `auto` 、`length` 、`n%`



## 内边距padding

属性值可用`length` 、`n%`



## 轮廓outline

轮廓线位于borer外围，属性值：

- `outline-color`  设置轮廓颜色

- `outline-style`  设置轮廓样式
- `ounline-width`  设置轮廓宽度