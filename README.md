# erke_finder

md 二课不够，不给毕业。

## 运行环境

- selenium
- chrome
- 一些基本的xls包

## 流程

用当爬虫，收集xls表格的下载地址，然后一起下载，查找包含sno的Row，最后保存到新的xls文件中。

最后打开输出的xls文件统计自己有没有漏报分数。



## 变量

mySno 姓名/学号

rootUrl 学工网的地址

maxPage 要查找的页数

## 输出

临时文件和输出文件都保存在运行文件的相对根路径下