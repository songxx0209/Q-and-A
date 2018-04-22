---
title: find 查找
---



## find 查找

```
find . -name "[a-z][a-z][0–9][0–9].txt" -print   // 查以两个小写字母和两个数字开头的txt文件
```



#### 参考链接：

[cnblogs关于find的总结](https://www.cnblogs.com/wanqieddy/archive/2011/06/09/2076785.html)

[find主要讲解grep-正则](https://www.cnblogs.com/skynet/archive/2010/12/25/1916873.html)



### find语法介绍

copy命令的功能是将给出的文件或目录拷贝到另一文件或目录中，同MSDOS下的copy命令一样，功能十分强大。
语法： cp [选项] 源文件或目录 目标文件或目录
说明：该命令把指定的源文件复制到目标文件或把多个源文件复制到目标目录中。
该命令的各选项含义如下：
\- a 该选项通常在拷贝目录时使用。它保留链接、文件属性，并递归地拷贝目录，其作用等于dpR选项的组合。
\- d 拷贝时保留链接。
\- f 删除已经存在的目标文件而不提示。
\- i 和f选项相反，在覆盖目标文件之前将给出提示要求用户确认。回答y时目标文件将被覆盖，是交互式拷贝。
\- p 此时cp除复制源文件的内容外，还将把其修改时间和访问权限也复制到新文件中。
\- r 若给出的源文件是一目录文件，此时cp将递归复制该目录下所有的子目录和文件。此时目标文件必须为一个目录名。
\- l 不作拷贝，只是链接文件。

需要说明的是，为防止用户在不经意的情况下用cp命令破坏另一个文件，如用户指定的目标文件名已存在，用cp命令拷贝文件后，这个文件就会被新源文件覆盖，因此，建议用户在使用cp命令拷贝文件时，最好使用i选项。