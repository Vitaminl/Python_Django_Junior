# Python_Django_Junior
*这是我准备在本地做的第一个Django Project。借此记录自己的一些心得。目标是用Python+Django的框架搭建一个网页。网页设计的是每次旅游的游记，最后会有一个统计页面，展示旅游的足迹和一些有意思的统计数据。图打算用pyecharts做。*

## 搭建环境
在搭建环境的时候遇到了不少的困难，主要是对环境的概念不算很熟。平时在公司用windows，在家用macOS，两者有些不同，一开始就有点弄混。现在情况有点混乱，先记录着，回头查。

+ OS:Anaconda+Python3.7+PyCharm，在terminal可以看到python3.7，但在conda和Pycharm的Interpreter就无法选择3.7；
+ OS:Django使用的是2.0.7，看介绍似乎有一些包还没来得及更新，需要在建项目的使用指定使用的django版本，降低掉坑风险。

+ windows：Anaconda+Python3.7+PyCharm，要添加一堆的环境变量，头大。

## 创建Django项目
```bach
$ django-admin startproject mysite
```
