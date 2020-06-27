# CSS相关
CSS，全称 Cascading Style Sheets，译称：层叠样式表。
#### 基本语法
选择器 { 属性: 值; 属性: 值;}
```css
h1 { color: skyblue; font-size: 16px; }
```

---
## 插入样式表方法
#### 外部样式表
在外部文件中进行 css 代码的编写，以 .css 扩展名保存，再在 html 文件中用 <link> 标签引用。
```html
<head>
  <link rel="stylesheet" type="text/css" hreaf="style_demo.css">
</head>
```
#### 内部样式表
在 html 文件的 <head> 部分，用 <style> 标签中编写 css 代码。
```html
<head>
  <style>
    ...css代码
  </style>
</head>
```
#### 内联样式
在相关标签内的 style 属性中，编写 css 代码。
```html
<h1 style="...css代码">内容</h1>
```
#### 三种方式的样式优先级
内联样式 > 内部样式 > 外部样式
---
···
