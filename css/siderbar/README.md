## text-align

文本内容水平对齐的方式

## display:table

## letter-spacing

增加或减少字符间的空白 ， 三个值： normal ｜ inherit ｜ 具体的值，可以为负值

## text-transform:

值有： uppercase ：转成大写

## span

内联元素，不会独占一行，高度和宽度由内容自动撑开

## text-decoration

该属性 规定添加到文本的修饰
对应的值有：
none：不设置任何装饰
underline: 定义文本下的一条线
overline:
line-througn:穿过文本的一条线
blink:
inherit:

## position: relative + float:left

## cursor: pointer;

设置鼠标指针在元素上的样式是手型

## box- sizing

盒模型属性 box-sizing 有两个常用的取值：

box-sizing: content-box;（默认值，即为标准盒子模型）：
这个取值表示元素的宽度和高度只包括内容区域（content），不包括内边距、边框和外边距。也就是说，设置元素的宽度和高度时，需要额外考虑内边距、边框和外边距的影响。

box-sizing: border-box;：
这个取值表示元素的宽度和高度包括内容区域（content）、内边距（padding）和边框（border），不包括外边距（margin）。也就是说，设置元素的宽度和高度时，内边距和边框的宽度会被包含在内，不会增加元素的总宽度和高度。

## input[type='checkbox']:checked ~ .sidebarIconToggle > .horizontal

input[type='checkbox']：这种选择器，包含所有类型为 checkbox 的 input
input[type='checkbox']:checked：类型为选中状态的 checkbox
input[type='checkbox']:checked ~ .sidebarIconToggle > .horizontal： 选中状态的 input
