# 第 16 章：函数

## 阅读参考资料

- [函数](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Functions)

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

## 递归函数

要求：
- 用递归函数实现 n! 计算功能
- n! = n * (n-1)!
- 在控制台输出 n! 运算结果，输出格式，例如：4! = 24

示例参考：
- [递归函数](https://codepen.io/wangding/pen/gOmomzE?editors=0011)
