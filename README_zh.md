# clever-meme

## 介绍
基于TradingView开发的量化交易教程，包含技术指标详解及实现过程，量化策略实现过程，回测的方法，实盘操作检验，以及交易界的传奇们。持续更新中～～～



----------------------------------
## 项目章节
----------------------------------
### 1. 指标 indicator
#### 1.1 量化交易的简单指标
技术指标是多年来无数伟大交易员们总结出来的优秀指标集合，这些指标你在各大交易平台上都能找到。我会复现这些指标在tradingView的实现过程，这一部分旨在夯实基础，便于你了解交易的本质，从所谓的时间序列中找到某些潜在的规律，并实现简单的预测，判断未来的走势。

同时抛砖引玉，之后更多的复杂指标也大多是由这些基础指标组合而来。你可以使用这些基础代码直接改造，或者根据自己的需求进行重构。

##### 1.1.1 MACD
MACD被称为技术指标之王。详细介绍了关于MACD指标（Moving Average Convergence Divergence,异同移动平均线）的一切信息，详见 [MACD](Quant-code/indicator/MACD.md)。

内含计算方法，衍生指标，应用场景，优缺点等。

##### 1.1.2 RSI
详细介绍了关于RSI指标（Relative Strength Index,相对强弱指数）的一切信息，详见 [RSI](Quant-code/indicator/RSI.md)。

内含计算方法，衍生指标，应用场景，优缺点等。

另附上了一种新颖的RSI衍生指标，具体的实例用法在详见[RSI](Quant-code/indicator/RSI.md)，原始代码饮用可以直接参考[抛物线RSI](Quant-code/indicator/抛物线RSI.pine)。

##### 1.1.3 KDJ
关于KDJ指标（随机指标）的一切信息，详见 [KDJ](Quant-code/indicator/KDJ.md)。

##### 1.2 量化交易的进阶指标
由易到难，逐步介绍量化交易中常用的进阶指标。
##### 1.2.1 布林带
布林带的原理是通过计算价格的平均值和标准差来确定价格的波动范围，从而确定价格的高低。
详细介绍了关于布林带指标（Bollinger Bands,布林带）的一切信息，详见 [布林带](Quant-code/indicator/Bollinger-Bands.md)。

##### 1.2.2 唐奇安通道


----------------------------------
### 2. 策略 strategy
#### 2.1 那些经久不衰的经典策略

##### 2.1.1 双均线策略

##### 2.1.2 海龟策略



#### 2.2 天才量化交易员的不传之秘 -- 那些天马行空的交易策略

---------------------------------
### 3. 回测 backtest
---------------------------------
### 4. 实盘 trading
---------------------------------
### 5. 杂谈&交易传奇
#### 5.1 利弗莫尔

#### 5.2 巴菲特
---------------------------------
## 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


## 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
