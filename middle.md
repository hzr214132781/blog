#垂直居中的幾種方法
[http://sofish.de/1909](http://sofish.de/1909)
[http://www.qianduan.net/css-to-achieve-the-vertical-center-of-the-five-kinds-of-methods.html](http://www.qianduan.net/css-to-achieve-the-vertical-center-of-the-five-kinds-of-methods.html)
- 1.单行
只考虑单行是最简单的，无论是否给容器固定高度，只要给容器设置 line-height 和 height，并使两值相等，再加上 over-flow: hidden 就可以了
优点：
1. 同时支持块级和内联极元素
2. 支持所有浏览器
缺点：
1. 只能显示一行
2. IE中不支持<img>等的居中
要注意的是：
1. 使用相对高度定义你的 height 和 line-height
2. 不想毁了你的布局的话，overflow: hidden 一定要
3. 