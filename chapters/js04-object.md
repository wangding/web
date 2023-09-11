# 第 4 章：面向对象编程

## 阅读参考资料

- [使用对象](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Working_with_Objects)
- [面向对象的细节](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Details_of_the_Object_Model)

## 矩形计算器

要求：
- 定义 Rectangle 类，类中成员如下
- 私有数据 w 代表矩形宽度，初始值为 0
- 私有数据 h 代表矩形高度，初始值为 0
- 构造函数有两个参数，width 和 height，用来初始化私有数据 w 和 h
- getter 属性方法 area，得到矩形的面积，area = w * h
- getter 属性方法 perimeter，得到矩形的周长，perimeter = 2 * (w + h)
- 周长和面积精确到小数点后两位，调用 Util 类中的 roundFractional 实现


- 定义 Util 类，类中成员如下
- 静态方法 roundFractional，功能：保留小数点后 n 位
- 两个入口参数，x 做近似处理的数，n 小数点后的位数
- 函数返回值是近似处理后的 x
- 参考文章 [JavaScript 浮点舍入误差](https://segmentfault.com/a/1190000013431163)


- 定义 App 类，类中成员如下
- 静态方法 main，功能：测试 Rectangle 类
- 控制台输出 w = 20, h = 10，矩形的周长和面积
- 控制台输出 w = 0.2, h = 0.1，矩形的周长和面积
- 输出格式，例如：
```
r1: w = 20, h = 10, area = 200, perimeter = 60
r2: w = 0.2, h = 0.1, area = 0.02, perimeter = 0.6
```


- 调用 App 类的静态 main 方法

示例参考：
- [矩形计算器](https://codepen.io/wangding/pen/jOBvweW?editors=0011)
