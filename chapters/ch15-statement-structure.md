# 第 15 章：语句和程序结构

## 阅读参考资料

- [控制流与错误处理](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Control_flow_and_error_handling)
- [循环与迭代](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Loops_and_iteration)

## for 循环

要求：
- 用 for 循环实现 n! 计算功能
- n! = n * (n-1) * ... * 1
- 在控制台输出 n! 运算结果，输出格式，例如：4! = 24

## do-while 循环

要求：
- 用 do-while 循环实现 n! 计算功能
- n! = n * (n-1) * ... * 1
- 在控制台输出 n! 运算结果，输出格式，例如：4! = 24

## while 循环

要求：
- 用 while 循环实现 n! 计算功能
- n! = n * (n-1) * ... * 1
- 在控制台输出 n! 运算结果，输出格式，例如：4! = 24

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

## for-of 循环

要求：
- 用 while 循环生成斐波那契数列，并保存到数组中
- 用 for-of 循环将数组中的斐波那契数列，输出到控制台

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
