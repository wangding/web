# 第 4 章：面向对象编程

## 阅读参考资料

- [使用对象](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Working_with_Objects)
- [面向对象的细节](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Details_of_the_Object_Model)

## 创建对象

要求：
- 用五种方式创建对象
- 第一种，用字面量的方式创建对象
- 该对象有 name 字段，值随意
- 该对象有 age  字段，值随意
- 该对象有 print 方法，打印该对象的 name 和 age 信息
- 在控制台打印该对象
- .
- 第二种，用 new 创建 Object 空对象
- 在控制台打印该对象
- .
- 第三种，原型法创建对象
- 以第一种方式创建的对象为原型，创建一个对象
- 在控制台打印该对象
- .
- 第四种，工厂函数创建对象
- 写一个工厂函数，返回车辆对象
- 包含两个字段，logo 字段，值随意，例如：奔驰
- price 字段，值随意
- 调用这个工厂函数创建对象
- 在控制台打印该对象
- .
- 第五种，对象组合
- 用对象字面量创建一个对象，包括两个字段
- sex 字段，值为 F 或 M
- department 字段，值随意，例如：数统学院
- 把上面这个对象，跟第一种方式创建的对象组合成一个新对象
- 在控制台打印组合后的对象

## 对象的基本操作

要求：
- 假设有 std 对象，代码如下

```javascript
const std = {
  name: 'lisi',
  age:  '20',
  print() {
    log(`name: ${this.name}`);
    log(`age : ${this.age}`);
  }
};
```
- 用两种方式使用属性和方法
- 添加 sex 属性和方法
- 在控制台打印该对象，确认属性或方法添加成功
- 删除属性或方法
- 在控制台打印该对象，确认属性或方法添加成功
- 查询 std 对象，是否存在 sex 属性和 print 方法
- `for...in` 遍历 std 的所有属性或方法
- 在控制台输出格式为：`key: value`

## 对象的高级操作

要求：
- 假设有 std 对象，代码如下

```javascript
const std = {
  name: 'lisi',
  age:  '20',
  print() {
    log(`name: ${this.name}`);
    log(`age : ${this.age}`);
  }
};
```
- 用 contact 对象通过展开运算符扩展 std 对象
- 在控制台打印扩展后的对象
- .
- 序列化 std 对象为 str
- 在控制台打印 str
- 反序列化 str 为对象
- 在控制台打印该对象
- .
- 声明一个对象，包含
- name 是 getter 属性方法，返回值随意
- age 是 getter 和 setter 属性方法
- `_age` 是普通属性，初始值随意，用来辅助 age 属性方法
- 使用 name 和 age
- .
- 在控制台打印 std 对象的 name 属性的属性描述符
- 在控制台打印 std 对象的所有属性的属性描述符

## 类

要求：
- 定义 Rectangle 类，类中成员如下
- 私有数据 w 代表矩形宽度，初始值为 0
- 私有数据 h 代表矩形高度，初始值为 0
- 构造函数有两个参数，width 和 height，用来初始化私有数据 w 和 h
- getter 属性方法 area，得到矩形的面积，`area = w × h`
- getter 属性方法 perimeter，得到矩形的周长，`perimeter = 2 × (w + h)`
- 周长和面积精确到小数点后两位，调用 `Number.toFixed` 方法
- .
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

## 继承

要求：
- 定义 Shape 类，两个空成员方法：area 和 perimeter
- .
- 定义 Circle 类，继承 Shape 类
- 成员如下：
- 私有数据 r 代表圆的半径，初始值为 0
- 构造函数有一个参数，radius 用来初始化私有数据 r
- getter 属性方法 area，得到圆的面积，`area = pi × r × r`
- getter 属性方法 perimeter，得到圆的周长，`perimeter = 2 × pi × r`
- 周长和面积精确到小数点后两位，调用 `Number.toFixed` 方法
- .
- 定义 Rectangle 类，继承 Shape 类
- 成员如下：
- 私有数据 w 代表矩形宽度，初始值为 0
- 私有数据 h 代表矩形高度，初始值为 0
- 构造函数有两个参数，width 和 height，用来初始化私有数据 w 和 h
- getter 属性方法 area，得到矩形的面积，`area = w × h`
- getter 属性方法 perimeter，得到矩形的周长，`perimeter = 2 × (w + h)`
- 周长和面积精确到小数点后两位，调用 `Number.toFixed` 方法
- .
- 定义 Triangle 类，继承 Shape 类
- 成员如下：
- 私有数据 b 代表三角行底边的长度，初始值为 0
- 私有数据 h 代表三角行底边垂线的高度，初始值为 0
- 构造函数有两个参数，base 和 height，用来初始化私有数据 b 和 h
- getter 属性方法 area，得到三角形的面积，`area = b × h / 2`
- 静态方法 perimeter，三个参数：s1, s2 和 s3，分别代表三角形的三个边长，得到三角形的周长，`perimeter = s1 + s2 + s3`
- 周长和面积精确到小数点后两位，调用 `Number.toFixed` 方法
- .
- 定义 App 类，类中成员如下
- 静态方法 main，功能：测试 Circle 类、Rectangle 类和 Triangle 类
- 调用 App 类的静态 main 方法

示例参考：
- [继承](https://codepen.io/wangding/pen/bGOoexo?editors=0011)
