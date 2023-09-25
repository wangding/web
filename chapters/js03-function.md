# 第 3 章：函数

## 阅读参考资料

- [函数](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Functions)

## 二进熵函数

要求：
- 二进熵函数：`H(p) = -p*log(p) -(1-p)*log(1-p)`
- 实现该二进熵函数 h，参数 p
- 将计算结果输出到控制台，输出格式，如：`h(0.2) = 0.72 bit`

示例参考：
- [二进熵函数](https://codepen.io/wangding/pen/jOBYBxP?editors=0011)

## 递归函数

要求：
- 用递归函数实现 n! 计算功能
- `n! = n × (n-1)!`
- 在控制台输出 `n!` 运算结果，输出格式，例如：`4! = 24`

示例参考：
- [递归函数](https://codepen.io/wangding/pen/gOmomzE?editors=0011)

## 函数声明的不同方式

要求：
- 函数 sayHello，入口参数是 name
- 该函数在控制台打印信息：`Hello, ${name}.`
- 用四种不同的方式声明 sayHello
  - function 关键字声明
  - 函数表达式声明
  - 箭头函数声明
  - Function 对象实例化

## 法老的金字塔

要求：
- 给定金字塔的层数 n，例如：`n = 3`
- 在控制台打印如下图案（`.` 字符用空格代替），如：

```
..*
.***
*****
```
- 函数 pyramid，入口参数是 n
- 实现该函数在控制台打印如上图案

## 可变参数

要求：
- 实现 sum 函数，参数个数可变
- sum 函数对参数求和，例如：`sum(1,2,3) = 1+2+3 = 6`
- 用 `arguments` 和剩余参数两种方式实现

## 默认参数

要求：
- 实现 avg 函数，参数：total, years
- 该函数计算年平均销售额，`avg = total / years`
- years 参数的默认值是 1
- .
- 实现 sortArray 函数，参数：arr, type
- 该函数返回排序后的 arr 整数数组，type 可以是升序（asc）或降序（desc）
- type 默认值是升序 `asc`

## 箭头函数

要求：
- 实现 sum 函数，参数：x, y
- 该函数完成两数求和，`sum(x, y) = x + y`
- 用箭头函数实现

## 回调函数

要求：
- 实现定时器倒计时 3 秒后，执行回调函数
- 回调函数在控制台打印信息

## 改写递归

要求：
- 把上面的法老金字塔 pyramid，改写成递归函数
- 把上面的可变参数 sum，改写成递归函数
