# Pandas中文手册
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/qzcool/DataCamp_pandas_cookbook/master)


[pandas](http://pandas.pydata.org/) 是一个用于数据分析的Python库，它能让你快速处理一些探索性的工作。

本教程改进自[IA-CAS](https://github.com/ia-cas/pandas-cookbook)对[pandas-cookbook](https://github.com/jvns/pandas-cookbook)的翻译。本手册的目的通过一些实际的例子来让你开始使用pandas。
Pandas 的[帮助文档](http://pandas.pydata.org/pandas-docs/stable/)已经相当全面了。不过，经常会有人询问应该怎样上手。接下来我讲讲如何用pandas来处理一些真实世界中的数据，如你所料，这些数据包含各种bug和异常值。

接下来我会使用以下3个数据集：这些数据已经包含在本目录下
* 311 calls in New York
* How many people were on Montréal's bike paths in 2012
* Montreal's weather for 2012, hourly

## 目录
* **Jupyter Notebook快速入门**
  <br> 展示了如何使用Jupyter的tab自动补齐和魔法函数
* **Chapter 1 - 读取CSV**
  <br> 将数据导入到pandas是相当容易的一件事，即使有编码错误也不是问题！
* **Chapter 2 - 选取数据和数据描述**
  <br>从pandas的DataFrame中选择数据有时候显得不那么直观,在这一部分我将解释一些基本的东西（比如怎么做切片操作，选取指定列）
* **Chapter 3 - 探索性数据分析_基础**
  <br>这部分将继续介绍如何对数据切片、切块以及过滤处理。
* **Chapter 4 - 探索性数据分析_Groupby和Aggregate**
  <br> groupby/aggregate操作 是我最喜欢pandas的地方，我几乎无时不刻都在用它。这部分必读！
* **Chapter 5 - 合并DataFrames和简单爬取数据**
  <br>这部分将会探索Montreal的冬天冷不冷（答案：冷！），用pandas来做网页抓取相当有意思。
* **Chapter 6 - 字符串操作**
  <br> pandas对string的操作非常好，它包含所有向量化的string操作。这部分内容将一系列包含Snow的字符串转换成向量化的数值来表示。
* **Chapter 7 - 清理杂乱数据**
  <br> 处理脏数据可不轻松，不过对于pandas来说，那就是另外一回事了
* **Chapter 8 - 如何处理时间戳**
  <br> 这个小技巧花了我两天才弄明白。。。
* **Chapter 9 - 从SQL数据库读取数据**
  <br> 本部分将介绍如何从 SQLite3, PostgreSQL及MySQL中导入数据到pandas

## 视频课程
本教程的完整视频和语音讲解演示版由`数据帮 (Data Camp)`在[网易云课堂](https://study.163.com)的`pandas应知必回课程`中付费提供，可根据个人情况酌情选择。

## 怎么使用Panda手册
### 在线环境
推荐使用Binder的出色在线Jupyter Notebook运行环境，[点击这里即可开始](https://mybinder.org/v2/gh/qzcool/DataCamp_pandas_cookbook/master)。对网速要求不高，基本均可流畅运行。

### 本地环境
首先，你需要更新下Jupyter Notebook(&gt;= 3.0) 以及 pandas(&gt;=0.13)

用pip可以完成更新操作：

```
pip install pandas
```

编译和配置这些有时候挺繁琐的，我自己是用的[Anaconda](https://www.anaconda.com/what-is-anaconda/),这个软件把几乎所有你能想到的库都包含了，并且是免费和开源的。

用conda也可以完成更新操作：
```
conda upgrade pandas
```

安装好Jupyter和pandas后，就可以使用Git命令或GitHub客户端下载

```
git clone https://github.com/qzcool/DataCamp_pandas_cookbook.git
cd DataCamp_pandas_cookbook/cookbook
jupyter notebook
```

执行完以上命令后，你的浏览器会自动打开一个地址为 `http://localhost:8888`的页面。

## 报错和改进
如果你发现某些地方有错误，或者是你想学习一些我在这里没有讲到的东西，又或者是你想分享些东西，赶紧发个issue，或者发邮件，pull request都行！

## 待办
- [ ] join 操作
- [ ] 使用 stack/unstack
- [ ] append

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)
