# javascript 语言记录
1. 变量提升（hoist）
  - 如果用var声明变量则全部会被提升到头部，function变量提升
2. 模块化
  - AMD规范， requirejs，define(id, deps, callbask), require加载, 依赖前置， 异步加载
  - CMD & commonjs， module, exports, require，依赖按需，
  - es6 import， export， default
  
- 根据国际标准 IEEE 754，JavaScript 浮点数的64个二进制位，从最左边开始，是这样组成的。

- 第1位：符号位，0表示正数，1表示负数
- 第2位到第12位（共11位）：指数部分
- 第13位到第64位（共52位）：小数部分（即有效数字）
