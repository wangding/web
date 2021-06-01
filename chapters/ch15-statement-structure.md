# 第 15 章：语句和程序结构

## 阅读参考资料

- [控制流与错误处理](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)
- [循环与迭代](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Loops_and_iteration)

## for 循环

要求：
- 用 for 循环实现 n! 计算功能
- n! = n * (n-1) * ... * 1
- 在控制台输出 n! 运算结果，输出格式，例如：4! = 24

示例参考：
- [for 循环](https://codepen.io/wangding/pen/KKWZWXp?editors=0011)

## 九九乘法表

要求：
- 用 for 循环在控制台打印九九乘法表
- 输出格式如下：
```
1*1=1
1*2=2 2*2=4
1*3=3 2*3=6 3*3=9
1*4=4 2*4=8 3*4=12 4*4=16
1*5=5 2*5=10 3*5=15 4*5=20 5*5=25
1*6=6 2*6=12 3*6=18 4*6=24 5*6=30 6*6=36
1*7=7 2*7=14 3*7=21 4*7=28 5*7=35 6*7=42 7*7=49
1*8=8 2*8=16 3*8=24 4*8=32 5*8=40 6*8=48 7*8=56 8*8=64
1*9=9 2*9=18 3*9=27 4*9=36 5*9=45 6*9=54 7*9=63 8*9=72 9*9=81
```

示例参考：
- [九九乘法表](https://codepen.io/wangding/pen/BaWYozR?editors=0011)

## do-while 循环

要求：
- 用 do-while 循环实现 n! 计算功能
- n! = n * (n-1) * ... * 1
- 在控制台输出 n! 运算结果，输出格式，例如：4! = 24

示例参考：
- [do-while 循环](https://codepen.io/wangding/pen/eYvyvyB?editors=0011)

## while 循环

要求：
- 用 while 循环实现 n! 计算功能
- n! = n * (n-1) * ... * 1
- 在控制台输出 n! 运算结果，输出格式，例如：4! = 24

示例参考：
- [while 循环](https://codepen.io/wangding/pen/yLMpMvO?editors=0011)

## for-in 循环

要求：
- 定义一个对象 me 如下：
```js
const me = {
  name: 'wangding',
  email: '408542507@qq.com',
  mobile: '13582027613'
};
```
- 用 for-in 循环在控制台输出 me 对象的各个字段

示例参考：
- [for-in 循环](https://codepen.io/wangding/pen/OJpzpQG?editors=0011)

## for-of 循环

要求：
- 用 while 循环生成斐波那契数列，并保存到数组中
- 用 for-of 循环将数组中的斐波那契数列，输出到控制台

示例参考：
- [for-of 循环](https://codepen.io/wangding/pen/YzZYZaj?editors=0011)

## 二进熵函数

要求：
- 实现二进熵函数计算功能
- 提示用户输入概率 p
- 对 p 做数据合法性校验，能够检查出如下错误：
  - p 为空值，例如：p = ''
  - p 的数据类型错误，例如：p = 'abc'
  - p 的取值范围错误，例如：p = 1.2 或者 p = -1.2
- 当检查 p 不合法时，继续提示用户输入概率 p
- H(p) = -plog(p) -(1-p)log(1-p)
- 二进熵函数计算结果，保留小数点后两位
- 将计算结果输出到控制台，输出格式，例如：h(0.2) = 0.72 bit

示例参考：
- [二进熵函数](https://codepen.io/wangding/pen/jOBYBxP?editors=0011)
