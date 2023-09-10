# 第 11 章：布局

## 阅读参考资料

- [布局](https://developer.mozilla.org/zh-CN/docs/Learn/CSS/CSS_layout)
- [学习 CSS 布局](https://zh.learnlayout.com)
- [Flex 布局教程：语法篇](https://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)
- [Flex 布局教程：实例篇](https://www.ruanyifeng.com/blog/2015/07/flex-examples.html)
- [CSS Grid 网格布局教程](https://www.ruanyifeng.com/blog/2019/03/grid-layout-tutorial.html)

## 弹性盒子

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/eYvgmrN?editors=1100) 代码中进行如下 CSS 样式设置
- 设置页面内外边距为 0px，高度 100%
- 设置 box1 背景色为浅绿色，box2 背景色为浅蓝色，box3 背景色为浅粉色，三个 box 的高度为浏览器窗口高度的 100%
- 观察三个 box 的布局，应该为三行一列
- 使用弹性盒子方式，修改三个 box 的布局，为一行三列布局

示例参考：
- [弹性盒子](https://wangding.github.io/css-demo/07-layout/01-flex.html)

## 网格 1

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/rNyjJQG?editors=1100) 代码中进行如下 CSS 样式设置
- 设置页面内外边距为 0px，高度 100%
- 设置 box1 ~ box6 背景色为浅绿色
- 观察六个 box 的布局，应该为六行一列
- 使用网格布局，修改六个 box 的布局，为二行三列布局，其中 box 之间的距离为 10px

示例参考：
- [网格 1](https://wangding.github.io/css-demo/07-layout/02-grid.html)

## 网格 2

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/RwpKMJr?editors=1100) 代码中进行如下 CSS 样式设置
- 设置页面内外边距为 0px，高度 100%
- 设置 box1 ~ box3 背景色为浅绿色
- 观察三个 box 的布局，应该为三行一列
- 使用网格布局，修改三个 box 的布局，为二行三列布局
- 其中 box2 跨两行，占第一列
- 其中 box1 跨两列，占第一行
- 其中 box3 占第二行，第三列

示例参考：
- [网格 2](https://wangding.github.io/css-demo/07-layout/03-grid.html)

## 浮动 1

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/poeebWW?editors=1100) 代码中进行如下 CSS 样式设置
- 设置段落 p 的宽度为 600px
- 设置 box 的样式为：宽度 150px，高度 150px，左边距 30px，背景色浅绿色，边框 2px 绿色实线，边框圆角半径 5px，内边距 10px
- 观察 box 和段落 p 的布局
- 修改 box 样式，让段落 p 环绕在 box 的右侧

示例参考：
- [浮动 1](https://wangding.github.io/css-demo/07-layout/04-float.html)

## 浮动 2

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/wvJJWpo?editors=1100) 代码中进行如下 CSS 样式设置
- 设置 body，html 和 div 初始样式为，内外边距 0px，高度 100%
- 设置 box1 ~ box3 三个 div 的宽度为 33%
- 设置 box1 背景色为浅绿，box2 背景色为浅蓝，box3 背景色为浅粉
- 观察 box1 ~ box3 的布局，应该是三行一列
- 设置浮动，让 box1 ~ box3 的布局为一行三列

示例参考：
- [浮动 2](https://wangding.github.io/css-demo/07-layout/05-float.html)

## 静态定位

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/qBrrNxv?editors=1100) 代码中进行如下 CSS 样式设置
- 设置 body 盒子样式，宽度 500px，水平居中
- 设置标题一水平居中
- 设置段落样式，背景色浅绿色，边框 2px 绿色实线，外边距 10px，内边距 10px，边框圆角半径 5px

示例参考：
- [静态定位](https://wangding.github.io/css-demo/07-layout/06-static-pos.html)

## 相对定位

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/BaWWzVQ?editors=1100) 代码中进行如下 CSS 样式设置
- 设置 body 盒子样式，宽度 500px，水平居中
- 设置标题一水平居中
- 设置段落样式，背景色浅绿色，边框 2px 绿色实线，外边距 10px，内边距 10px，边框圆角半径 5px
- 设置 positioned 段落样式：背景色浅粉色，边框 2px 红色实线
- 观察 positioned 段落和其他段落之间的位置关系
- 修改 positioned 段落样式，相对其原来位置向下移动 30px，向右移动 30px

示例参考：
- [相对定位](https://wangding.github.io/css-demo/07-layout/07-relative-pos.html)

## 绝对定位

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/oNZZLMK?editors=1100) 代码中进行如下 CSS 样式设置
- 设置 body 盒子样式，宽度 500px，水平居中
- 设置标题一水平居中
- 设置段落样式，背景色浅绿色，边框 2px 绿色实线，外边距 10px，内边距 10px，边框圆角半径 5px
- 设置 positioned 段落样式：背景色浅粉色，边框 2px 红色实线
- 观察 positioned 段落和其他段落之间的位置关系
- 修改 positioned 段落样式，使其位置在浏览器窗口的左上角，水平 150px 垂直 30px（使用绝对定位）
- 设置最后一个段落的高度为 800px，上下滚动页面，观察 positioned 段落是否跟随滚动

示例参考：
- [绝对定位](https://wangding.github.io/css-demo/07-layout/08-absolute-pos.html)

## 固定定位

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/XWMMMyJ?editors=1100) 代码中进行如下 CSS 样式设置
- 设置 body 盒子样式，宽度 500px，水平居中
- 设置标题一水平居中
- 设置段落样式，背景色浅绿色，边框 2px 绿色实线，外边距 10px，内边距 10px，边框圆角半径 5px
- 设置 positioned 段落样式：背景色浅粉色，边框 2px 红色实线
- 观察 positioned 段落和其他段落之间的位置关系
- 修改 positioned 段落样式，使其位置在浏览器窗口的左上角，水平 30px 垂直 30px（使用固定定位）
- 设置最后一个段落的高度为 800px，上下滚动页面，观察 positioned 段落是否跟随滚动

示例参考：
- [固定定位](https://wangding.github.io/css-demo/07-layout/09-fixed-pos.html)

## 粘连定位

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/dyvvvaW?editors=1100) 代码中进行如下 CSS 样式设置
- 设置 body 盒子样式，宽度 500px，水平居中
- 设置标题一水平居中
- 设置段落样式，背景色浅绿色，边框 2px 绿色实线，外边距 10px，内边距 10px，边框圆角半径 5px
- 设置 positioned 段落样式：背景色浅粉色，边框 2px 红色实线
- 观察 positioned 段落和其他段落之间的位置关系
- 修改 positioned 段落样式，使其位置在容器的左上角，水平 30px 垂直 30px（使用粘连定位）
- 设置第一个段落的高度为 800px，最后一个段落的高度为 1800px，上下滚动页面，观察 positioned 段落是否跟随滚动

示例参考：
- [粘连定位](https://wangding.github.io/css-demo/07-layout/10-sticky-pos.html)

## 表格布局

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/YzZZZbr?editors=1100) 代码中进行如下 CSS 样式设置
- 使用表格布局，格式化个人信息提交表单
- 使表单呈现为三行两列
- 所有 label（第一列）的宽度为 200px，右侧内边距为 5%，文字右对齐，下外边距为 10px
- 所有文本框（第二列）的宽度为 300px，下外边距为 10px
- 将段落文字设置为表头文字，并显示在表格的底部，文字是斜体灰色，水平居中

示例参考：
- [表格布局](https://wangding.github.io/css-demo/07-layout/11-table.html)

## 多列布局

要求：
- 在 [code-pen](https://codepen.io/wangding/pen/MWppmWW?editors=1100) 代码中进行如下 CSS 样式设置
- 将整个页面设置为多列布局，列的宽度为 200px
- box1 的高度为 200px，背景色为淡绿色
- box2 的高度为 200px，背景色为淡蓝色

示例参考：
- [多列布局](https://wangding.github.io/css-demo/07-layout/12-multicol.html)
