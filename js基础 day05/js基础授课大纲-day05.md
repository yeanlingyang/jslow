# 函数

## 函数的回顾





## 函数的参数与返回值的说明

1. 函数的形参实参一一对应
2. return的代码不执行





## 函数的调试说明







## 变量的作用域 - 全局变量和局部变量

1. 全局作用域, 全局变量
2. 局部作用域, 局部变量





## 变量的访问规则

思考一下:

```js
  var num = 11;
  function fn() {
    var num = 22;
    console.log(num);  
  }  
  fn();
```





## 全局变量和局部变量的查找规则

如果自己有, 就会获取或者修改自己的变量, 如果没有, 就会往外找

```js
  var num = 22;

  function fn() {
    num = 11;
    console.log(num);
  }
  fn();
  console.log(num);
```









## 隐式全局变量的说明

隐式全局变量

```js
  function fn() {
    num = 30;
    console.log(num);
  }
  fn();
  console.log(num);
```



小demo

```js
var num = 20;
function fn() {
   num = 30;
   console.log(num);
}
fn();
console.log(num);
```







## 预解析

浏览器在代码执行之前, 会找到所有声明的变量和函数

思考一下:

```js
  console.log(num);
  var num = 11;
  console.log(num);
```





## 预解析小练习

1. getCool
2. 小练习







## 预解析 - 面试题

函数内部也会进行预解析





## 声明函数的两种方式

函数也是一种数据类型







## 匿名函数(没有名字的函数)

1. 赋值给变量  函数表达式
2. 匿名函数自调用







## 匿名函数自调用的作用

全局变量污染问题





# 对象

## 为什么要学习对象







## 创建对象的两种方式







## 对象中的两个核心概念

创建一个俊俊对象, 俊俊对象有着特征 和 行为!

1. 属性

2. 方法





## 对象的取值和赋值



