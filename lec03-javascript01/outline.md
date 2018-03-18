# javaScript
JavaScript 是属于网络的脚本语言！

JavaScript 被数百万计的网页用来改进设计、验证表单、检测浏览器、创建cookies，以及更多的应用。

JavaScript 是因特网上最流行的脚本语言。

## 数据类型
### 字符串String
### 数字类型 Number 
### 布尔 Boolean
### 数组类型 Array 
### 对象 Object
### Undefined
### NULL
## 算术运算
### + - * /
### == !=  === !==
#### == ！= 判断过程中会发生类型转换
var ret = "7" == 7;// ret = true;
#### === !== 判断过程中不会发生类型转换
var ret = "7" === 7 ;// ret = false;
### ++ --
### += -= *= /=
var a = 5;
a +=2;//a = 7;

## 数组（每个元素的类型可以不同）
可以通过下标来访问，例如 var arr = [1,2,3]; arr[i];
数组中四个常用的函数
### .push()从数组末尾加入一个元素进数组
### .pop()从数组末尾删除一个元素出数组
### .shift()从数组首位删除一个元素出数组
### .unshift()从数组首位加入一个元素进数组
var arr = [1,2,3];
arr = arr.push(4); //arr = [1,2,3,4];
var arr = [1,2,3];
var v = arr.pop(); arr = [1,2]; v = 3;