## position 概念

指定一个元素在文档中的移动位置
再结合 top ， left， right， bottom 来确定元素最终的位置
主要有三种类型的值：
相对定位：relative
绝对定位：absolute and fixed
粘性定位：sticky

### static

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
