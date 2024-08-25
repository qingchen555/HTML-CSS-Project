## position 概念

指定一个元素在文档中的移动位置
再结合 top ， left， right， bottom 来确定元素最终的位置
主要有三种类型的值：
相对定位：relative
绝对定位：absolute and fixed
粘性定位：sticky

### static

文档流：dom 元素在排列时所占用的位置和空间
元素在正常的文档流的位置， 对于 top,bottom, left, right, z-index 都是无效的

### relative

相对于自己的初始位置进行定位的，脱离文档流，保留原来的位置

### absolute

相对于最近一个已经定位的祖先元素，脱离文档流，原来的空间不会保留
如果没有最近已经定位的祖先元素，会相对于最初的包含块进行移动

### fixed

相对于可视窗口的位置进行定位，元素脱离文档流，不会保留原来的位置
作用：
1-元素的位置在屏幕滚动时，不会改变
2-打印时，元素会出现在每页的固定位置
3-fixed 属性会创建新的层叠上下文
4-

### sticky

必须要结合 top, left, right, bottom 其中之一，才可以使粘性定位生效
sticky 元素会固定在离它最近的一个拥有滚动机制的祖先元素

## position 不同属性值对应的使用场景

## 父元素设置 display： table-cell，子元素必须设置 display： inline-block 才可以使用父元素的 text-align：center？

首先，子元素设置为 inline-block 之后具有的特性
1-元素在同一行内显示，不会独占一行
2-可以设置宽高，内外边距
3-元素之间存在默认的水平间距
4-仍在文档流中
5-会影响父元素的定位属性
6-可以通过 vertical 属性来调整该元素的基线

然后，对于 text-align 属性：是用于设置元素内的文本的水平对齐方式
对于 inline-block，会影响该元素的对齐方式
