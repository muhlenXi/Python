## Python 编程注意事项 
 
1、用 `#` 开头的语句是注释。 
 
2、Python 语法采用的是缩进的方式，约定俗成，一般为4个空格的缩进。 
 
3、Python 是大小写敏感的。 
 
4、`True`、`False`、`and`、`or`、`not`，用 `None` 表示空值。 
 
5、在 Python 中， 通常用全部大写的变量名来表示常量。 
 
6、`/` 精确除法，结果为浮点数; `//` 地板除，两个整数相除仍然是整数; `%` 为取模或取余数。 
 
7、文件开头代码表示： 
 
```python 
# !/usr/bin/env python3  
# _*_ coding: utf-8 _*_  
``` 

* 第一行注释，是告诉 Linux/OS X 系统，这是一个 python 可执行程序，windows 系统会忽略这个注释； 
* 第二行注释，是告诉 python 解释器，按照 UTF-8 编码读取源代码，否则你在源代码写的中文输出可能会有乱码。 
 
8、只有一个元素的 tuple 定义的时候，必须加一个 `,` 来消除歧义,如 `（1, ）`。 