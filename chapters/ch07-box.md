# 第 7 章：盒模型

## 阅读参考资料

- [盒模型](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/Building_blocks/The_box_model)

## 块和内联元素的盒模型

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/poegzLY?editors=1100) 代码中进行如下 CSS 样式设置
- 给 p, ul 加 2px 紫色实线边框和 0.5em 内边距
- 给 .block 和 li 加 2px 蓝色实线边框及 0.5em 内边距
- 设置 li 没有项目符号，设置 ul 内部为 flex 弹性盒子布局
- 设置 block 类的样式为块样式

示例参考：
- [块和内联元素的盒模型](https://wangding.github.io/css-demo/03-box/01-box.html)

## 普通盒子和 border-box

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/mdWVboX?editors=1100) 代码中进行如下 CSS 样式设置
- 设置 box 类的样式，5px 紫色实线边框，背景色为浅灰色，内边距为 40px，宽度为 300px，高度为 150px，外边距为 40px
- 设置 alternate 类的盒子模型为 border-box，观察两个盒子在页面上的尺寸差异
- 用 Chrome 开发者工具观察[普通盒子和 border-box 盒子](https://wangding.github.io/css-demo/03-box/02-box.html)的尺寸差异

示例参考：
- [普通盒子和 border-box](https://wangding.github.io/css-demo/03-box/02-box.html)

## 负外边距

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/oNZbMaq?editors=1100) 代码中进行如下 CSS 样式设置
- 设置容器 container 的样式：边框 5px 蓝色实线，外边距 40px
- 设置盒子 box 的样式：边框 5px 紫色实线，浅灰背景色，高 150px，内边距 10px，外边距 40px
- 将 box 上外边距改成 -40px，其他不变，观察 box 和 container 的位置关系

示例参考：
- [负外边距](https://wangding.github.io/css-demo/03-box/03-box.html)

## 外边距折叠

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/PopZBrr?editors=1100) 代码中进行如下 CSS 样式设置
- 设置 container 容器样式：边框 5px 紫色实线
- 设置段落样式：边框 5px 蓝色实线，上下内边距 10px，左右内边距 0px
- 设置第一个段落样式：下外边距 50px
- 设置第二个段落样式：上外边距 30px
- 将第二个段落的上外边距改为 0px，观察外边距折叠现象

示例参考：
- [外边距折叠](https://wangding.github.io/css-demo/03-box/04-box.html)

## 精确控制边框样式

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/qBrbMRJ?editors=1100) 代码中进行如下 CSS 样式设置
- 设置容器 container 的样式：上边框 5px 绿色点状线，右边框 1px 黑色实线，下边框 20px 深蓝色双实线
- 设置 box 的样式：所有边框线为 1px 黑色实线，上边框为点线，右边框的宽度为 20px，下边框的颜色为粉色，内边距为 20px，背景色为浅灰色

示例参考：
- [精确控制边框样式](https://wangding.github.io/css-demo/03-box/05-box.html)

## 内联盒子

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/GRWowEB?editors=1100) 代码中进行如下 CSS 样式设置
- 设置段落样式：边框 2px 紫色实线，宽度 300px，行高 30px
- 设置 span 样式：宽度 80px，高度 50px，边框 2px 蓝色实线，浅蓝背景色，外边距 20px，内边距 20px
- 观察 span 覆盖了部分段落文字，导致排版混乱
- 修改 span 的显示类型为 inline-block，观察修改后的 span 的效果，修改前后 span 盒子尺寸的变化以及边距的效果

示例参考：
- [内联盒子](https://wangding.github.io/css-demo/03-box/06-box.html)
