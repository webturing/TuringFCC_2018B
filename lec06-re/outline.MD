# lec06 -Regular Expression

## Regular Expression
-正则表达式（英语：Regular Expression，在代码中常简写为regex、regexp或RE）使用单个字符串来描述、匹配一系列符合某个句法规则的字符串搜索模式。
- 正则表达式是由一个字符序列形成的搜索:  ```模式。
当你在文本中搜索数据时，你可以用搜索模式来描述你要查询的内容。```-正则表达式可以是一简单的字符，或一个更复杂的模式。
-正则表达式可用于所有文本搜索和文本替换的操作。
## 语法
- 语法:  ```/正则表达式主体/修饰符(可选)```其中修饰符是可选的。
```
var patt = /runoob/i
```
其中： 
- /runoob/i  是一个正则表达式
- runoob  是一个正则表达式主体 (用于检索)。
- i  是一个修饰符 (搜索不区分大小写)。


## 使用字符串方法
在 JavaScript 中，正则表达式通常用于两个字符串方法 : search() 和 replace()。

- search() 方法 用于检索字符串中指定的子字符串，或检索与正则表达式相匹配的子字符串，并返回子串的起始位置。

- replace() 方法 用于在字符串中用一些字符替换另一些字符，或替换一个与正则表达式匹配的子串。

search() 方法使用正则表达式
实例
使用正则表达式搜索 "Runoob" 字符串，且不区分大小写：

```
var str = "Visit Runoob!"; 
var n = str.search(/Runoob/i);
输出结果为：6
```
search() 方法使用字符串
search 方法可使用字符串作为参数。字符串参数会转换为正则表达式：

```
检索字符串中 "Runoob" 的子串：

var str = "Visit Runoob!"; 
var n = str.search("Runoob");

replace() 方法使用正则表达式
```

```
使用正则表达式且不区分大小写将字符串中的 Microsoft 替换为 Runoob :

var str = document.getElementById("demo").innerHTML; 
var txt = str.replace(/microsoft/i,"Runoob");
结果输出为:Visit Runoob!

```

replace() 方法使用字符串
replace() 方法将接收字符串作为参数：
```
var str = document.getElementById("demo").innerHTML; 
var txt = str.replace("Microsoft","Runoob");
```
