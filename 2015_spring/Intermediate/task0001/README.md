# HTML、CSS基础

**任务编号**：`TASK 0001`

## 任务目的

掌握`HTML`、`CSS`基础知识、能够较为熟练地使用`HTML`、`CSS`编写页面

## Start

## 6. 盒模型及定位

### 6.1 任务描述

在`task0001.html`中，实践以下内容：

- 用两种方法来实现一个背景色为`红色`、宽度为`960px`的`<DIV>`在浏览器中居中：[源代码](https://github.com/nitta-honoka/baiduIFE_practice/tree/master/2015_spring/Intermediate/task0001/%236.%20box-model-position/item1)，[博文总结](http://www.cnblogs.com/honoka/p/5146953.html)
- 有的圆角矩形是复杂图案，无法直接用border-radius，请在不使用border-radius的情况下实现一个可复用的高度和宽度都自适应的圆角矩形：[源代码](https://github.com/nitta-honoka/baiduIFE_practice/tree/master/2015_spring/Intermediate/task0001/%236.%20box-model-position/item2) ![示例](img/task0001_7.png)
- 用两种不同的方法来实现一个两列布局，其中左侧部分宽度固定、右侧部分宽度随浏览器宽度的变化而自适应变化: [源代码](https://github.com/nitta-honoka/baiduIFE_practice/tree/master/2015_spring/Intermediate/task0001/%236.%20box-model-position/item3)，[博文总结《如何通过 CSS 实现一个左边固定宽度、右边自适应的两列布局》](http://www.cnblogs.com/honoka/p/5156133.html) ![示例](img/task0001_3.jpg)
- 用两种不同的方式来实现一个三列布局，其中左侧和右侧的部分宽度固定，中间部分宽度随浏览器宽度的变化而自适应变化：[源代码](https://github.com/nitta-honoka/baiduIFE_practice/tree/master/2015_spring/Intermediate/task0001/%236.%20box-model-position/item4),[《CSS 布局实例系列（三）如何实现一个左右宽度固定，中间自适应的三列布局——也聊聊双飞翼》](http://www.cnblogs.com/honoka/p/5161836.html)
- 实现一个浮动布局，红色容器中每一行的蓝色容器数量随着浏览器宽度的变化而变化：[源代码](https://github.com/nitta-honoka/baiduIFE_practice/tree/master/2015_spring/Intermediate/task0001/%236.%20box-model-position/item5),[《CSS 布局实例系列（四）如何实现容器中每一行的子容器数量随着浏览器宽度的变化而变化？》](http://www.cnblogs.com/honoka/p/5164616.html) ![示例1](img/task0001_4.jpg) ![示例2](img/task0001_5.jpg)
- 实现一个三列等高布局

### 6.2 知识点总结

- 掌握块状元素、内联元素、和内联块状元素的概念与区别：块状、行内与行内块状
- 掌握盒模型的所有概念，学会如何计算各种盒模型相关的数值：margin、padding、border、负边距
- 掌握`position`的相关知识：static、relative、absolute（脱离文档流）、fixed
- 掌握`float`的相关知识：脱离文档流，清除浮动
- 掌握基本的布局方式
- 了解`Grid`、`Flexbox`等布局方式
- BFC 原理

### 6.3 参考资料

- [w3school](http://w3school.com.cn/css/css_boxmodel.asp)
- [MDN](https://developer.mozilla.org/zh-CN/docs/CSS/%E5%BC%80%E5%A7%8B/Boxes)
- [慕课网](http://www.imooc.com/code/2047)
- [w3school](http://w3school.com.cn/css/css_positioning.asp)
- [慕课网](http://www.imooc.com/code/2057)
- [学习CSS布局](http://zh.learnlayout.com/no-layout.html)
- [CSS布局方式](http://teamtreehouse.com/library/css-layout-techniques)
- [双飞翼布局介绍-始于淘宝UED](http://www.imooc.com/wenda/detail/254035)
- [W3C Visual formatting model](http://www.w3.org/TR/CSS21/visuren.html#)
- [MDN Visual formatting model](https://developer.mozilla.org/en-US/docs/Web/Guide/CSS/Visual_formatting_model)
- [CSS 101: Block Formatting Context](http://www.yuiblog.com/blog/2010/05/19/css-101-block-formatting-contexts)
- [Block Formatting Context In CSS](http://outofmemory.cn/wr/?u=http%3A%2F%2Fkkeys.me%2Fpost%2F68547473290)
- [A new micro clearfix hack](http://nicolasgallagher.com/micro-clearfix-hack/)
- [那些年我们一起清除过的浮动 by 一丝冰凉](http://www.iyunlu.com/view/css-xhtml/55.html)
- [BFC和hasLayout](http://www.cnblogs.com/pigtail/archive/2013/01/23/2871627.html)

## 7. 综合练习

### 7.1 任务描述

在您自己的Github中建立一个新的仓库，比如命名为`task0001`，在该目录下创建以下四个html文件：

- `index.html`：对应`task0001_1`及`task0001_1_marked`设计稿
- `blog.html`：对应`task0001_2`及`task0001_2_marked`设计稿
- `gallery.html`：对应`task0001_3`及`task0001_3_marked`设计稿
- `about.html`：对应`task0001_4`及`task0001_4_marked`设计稿
 
再创建一个`css`目录，在`css`目录中创建一个`style.css`用于编写样式。

再创建一个`img`目录，用于存放页面编写中会使用到的图片。

这时，你的文件夹结构应该是这样的：

![文件结构](img/task0001_6.png)

基于[设计稿](design/)中的设计图及标志实现页面，里面的内容、图片、配色均可自定义。

- 编码过程请尽可能遵守[HTML、CSS的代码规范](https://github.com/ecomfe/spec)；
- 暂时不要使用`less`、`sass`等，这是后面的任务；
- 不要使用任何样式框架。
- 不需要写任何JavaScript，只需要关注HTML、CSS
- 页面实际内容宽度为980px，头部背景、大图、底部背景均为100%宽，当浏览器宽度低于980px时，页面宽度不变，允许出现横向滚动条。右上角的Github图标在浏览器低于980px时消失。

**任务关键执行步骤**

- 按照以上要求进行编码，先不需要关注页面中任何具体的图片和文字内容，都随意输入，注意力放在页面架构、布局、样式上；
- 编码的同时，记录遇到的技术问题和疑惑；
- 完成编码后，删掉它们，不留一丝痕迹；
- 开始重(Chong)构(Xie)，让自己的代码要比第一次有提升，尽可能地让第一次遇到问题和疑惑不再存在；
- 在blog.html页面中真的写上2-3篇这次学习上的技术总结收获；
- 初级班同学请在[这里](https://github.com/baidu-ife/ife/issues/764)，按要求回复您的task0001的Github地址。

### 7.2 期望达成

- 学会能够基于设计稿来合理规划HTML结构
- 理解语义化，合理地使用HTML标签来构建页面
- 能够较为熟练地使用HTML、CSS创建一个静态页面
- 大概了解并实践企业中对于HTML及CSS的编码规范
- 编写复用性高、可读性、可维护性好的代码

### 7.3 参考资料

- [HTML、CSS的代码规范](https://github.com/ecomfe/spec)
- [顾轶灵:Web语义化](http://www.zhihu.com/question/20455165)
- [CSS命名规范@W3C Funs](http://www.w3cfuns.com/blog-5445898-5398950.html)
[点击阅读: CSS浏览器兼容性列表](http://en.wikipedia.org/wiki/Comparison_of_layout_engines_%28Cascading_Style_Sheets%29)

## 8. 验证

经过上面的练习，您是否已经能够熟练到能够在一天甚至半天之内完成任务7的编码呢？或者不带任何犹豫地可以知道

- `doctype`是什么，它是干啥用的
- `ul`、`ol`、`dl`都适合用在什么地方
- 能够娓娓道来你是怎么理解HTML语义化的
- CSS选择器都有哪些
- `position`都有什么值，区别是什么
- 经典的清除浮动代码中每一行语句都是干什么用的，为什么少了它不行
- 让一个HTML节点居中的各种实现方式
- 神马圣杯布局、双飞翼布局都是些什么东西
- 强大的负外边距都能干嘛
- 不小心提起文档流的时候还能接着解释到底啥是文档流
- ……

关于HTML、CSS，我们暂时到这里，下一个任务我们将进行JavaScript的一些基础训练。
