# 文本Text

`color`  设置文本颜色

`direction`  设置文本方向，属性值有：`ltr`(默认)、`rtl`

`letter-spacing`  设置字符间距，属性值：`normal`(默认)、`length`

`line-hight`  设置行高，属性值：
- `normal`  默认
- `number`  设置数字，按该数与当前字符尺寸相乘，来设置行高
- `length`  设置固定的行间距
- `n%`  基于当前字符尺寸的百分比设置

`text-align`  设置水平对齐方式，属性值：
- `left` / `center` / `right`
- `justify`  两端对齐

`text-indent`  设置首行文本缩进，属性值：`length`(默认0)、`n%`

`text-shadow`  设置阴影，语法为 `h-shadow v-shadow blur color;`，属性值：
- `h-shadow`  必需，水平阴影的位置，允许负值
- `v-shadow`  必需，垂直阴影的位置，允许负值
- `blur`  可选，模糊的距离
- `color` 可选，阴影的颜色

`text-transform`  设置文本的大小写，属性值：
- `none`  默认
- `capitalize`  每个单词以大写字母开头
- `uppercase`  全为大写
- `lowercase`  全为小写

`unicode-bidi`

`vertical-align`  设置垂直对齐方式，属性值：
- `baseline`  默认，放置在父元素的基线上
- `sub`  对齐文本的下标
- `super`  对齐文本的上标
- `top` / `middle` / `bottom`  对齐行中最高元素的顶端 / 父元素的中部 / 行中最低元素的顶端
- `text-top` / `text-bottom`  把元素的顶端与父元素字体的顶端 / 底端对齐
- `length`
- `n%`  使用 `"line-height"` 属性的百分比排列，允许使用负值

`white-space`  设置元素内空白的处理方式，属性值：
- `normal`  默认，空白会被浏览器忽略
- `pre`  空白会被浏览器保留
- `nowrap`  文本不会换行，直到遇到 `<br>`
- `pre-wrap`  保留空白符序列，但是正常地进行换行
- `pre-line`  保留空白符序列，同时保留换行符

`word-spacing`  设置单词间距，属性值：
- `normal`  默认
- `length`