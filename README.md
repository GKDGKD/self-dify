# self-Dify 

# 一、项目简介

```
本项目是由Datawhale成员制作，针对Dify（大模型应用开发框架）使用的教程项目，并借助Dify通过零代码或低代码方式开发你的智能体项目。针对大语言模型入门学习者、有使用百度灵镜及coze智能体经验并且想做个人项目的开发者、有本地知识库搭建需求的开发者、对大语言模型有进阶需求的学习者。本次Dify项目中不乏经典智能体开发项目，助你在完成自己智能体时乘风破浪。我们也希望通过这个开源项目让更多的普通学生、开发者更好地使用大模型，帮助开源、自由的大模型更快融入到普通学习者的生活与工作中，推动AI+X快速发展！
```

本项目的主要内容包括：

1. Dify 框架理解与安装；
2. Dify 单智能体搭建及 api 调用；
3. Dify with WordPress （你的智能体网页）；
4. Dify 知识库；
5. Dify workflow 设计与实现。

   **项目的主要内容是制作教程，让更多的学生和未来的从业者了解和熟悉大模型项目开发过程！任何人都可以提出 issue 或是提交 PR，共同构建维护这个项目。**

  想要深度参与的同学可以联系我们，我们会将你加入到项目的维护者中。

# 二、立项理由

```
  经历过大语言模型如火如荼发展的2023年后，大家发现大语言模型的功能逐渐接近同质化，各个厂家的大语言模型也越来越相近。经过一年的迭代，目前的大语言模型有了一定的“智慧”，可以帮助我们稳定有效地完成一些简单的任务。然而目前我们在开发使用大语言模型时往往会遇到，单凭大语言模型无法完成某些专业知识的回答，有时需要借助专业知识来回答；单凭大语言模型无法满足所有任务需要，有时需要使用外部工具。但是结合大语言模型及各种工具知识又需要代码开发，无形中对很多不熟悉代码开发的小伙伴形成了门槛。遇到这种情况阻碍了很多学习和非本专业的开发者对大模型应用的开发。

  目前有了dify这样友好的工具，可以大大提升大语言模型的功能。所以我们想通过本项目教会大家快速上手dify，并且创建自己的大语言模型智能体。通过本项目，可以帮助各行业的小伙伴推进开发大语言模型应用的速度，对于一些开发上的技术难点将不再是困难。
```

_      _**我们希望借助 dify 框架，更友好的帮助大语言模型的开发者们完成自己的大语言模型应用，让 AI+X 来的更早一些。**

# 三、**项目受众**

  本项目适合以下学习者：

- 期望制作一个本地运行大模型项目；
- 快速实现智能体；
- 通过 api 或本地大模型方便使用本地知识库；
- 想用大模型完成行业内的 AI+X 升级；
- 本地实现大模型应用，有复杂大模型需求，需要封装好智能体应用 api；
- 想做智能体且有开发经验但是不想学 python 的非 python 语言玩家；
- 以及最广大、最普通的学生群体。

# 四、**项目亮点**

Datawhale 现有的大模型教程暂无快速让开发者快速系统且完善搭建智能体，我们有 self-llm 及 llm-universe 这样超受欢迎的大模型算法使用课程及 huggingllm 这样的硬核 metagpt 开发课程，但是缺少应用开发课程可以让开发者们方便快捷将大模型和应用打通，帮助自己完成自己大模型 + 应用。所以我们希望用 self-dify 项目带着大家快速入手智能体开发，用零代码或低代码方式，使用知识库、大模型 api、tools 搭建智能体应用，并支持在 autodl 部署。我们会适当涵盖一些前端开发内容，保证知识覆盖到开发大模型产品的全栈技术点。

# 五、项目框架

- 目录
- 第一章 Dify框架理解与安装
    - [1.1 Dify背景介绍](1.%20Dify框架理解与安装/1.1%20Dify背景介绍.md)
    - [1.2 Dify应用可以做出产品及本次课程涉及的内容](1.%20Dify框架理解与安装/1.2%20课程介绍.md)
    - [1.3 Docker安装（MAC、Linux、Windows）及常见的坑](1.%20Dify框架理解与安装/1.3%20环境配置及启动.md)
    - [1.4 Dify环境安装](1.%20Dify框架理解与安装/1.4%20Dify启动.md)
- 第二章 Dify单智能体搭建及api调用
    - [2.1 智能体介绍](2.%20Dify单智能体搭建及api调用/2.1%20智能体介绍.md)
    - [2.2 Dify大语言模型引入（Kimi为例）](2.%20Dify单智能体搭建及api调用/2.2%20Dify大语言模型引入（Kimi为例）.md)
    - [2.3 Dify单智能体如何搭建](2.%20Dify单智能体搭建及api调用/2.3%20Dify单智能体搭建.md)
    - [2.4 prompt工程](2.%20Dify单智能体搭建及api调用/2.4%20prompt工程.md)
    - [2.5 Dify单智能体帮手案例](2.%20Dify单智能体搭建及api调用/2.5%20Dify单智能体帮手案例.md)
    - [2.6 2.5 其他各类api及大模型如何接入？](2.%20Dify单智能体搭建及api调用/2.6%20其他各类api及大模型如何接入？.md)
    - [2.7 Dify接口化方法【如何作为项目的一部分】](2.%20Dify单智能体搭建及api调用/2.7%20Dify接口化方法.md)
- 第三章 Dify with WordPress （你的智能体网页）
    - [3.1 WordPress 介绍](3.%20Dify%20with%20WordPress/3.1%20WordPress%20介绍.md)
    - [3.2 WordPress 环境搭建及Dify结合](3.%20Dify%20with%20WordPress/3.2%20WordPress%20环境搭建及Dify结合.md)
    - [3.3 Dify 创建一个“AI 文本生成”应用](3.%20Dify%20with%20WordPress/3.3%20Dify%20创建一个“AI%20文本生成”应用.md)
    - [3.4 制作 WordPress 标题生成插件](3.%20Dify%20with%20WordPress/3.4%20制作%20WordPress%20标题生成插件.md)
- 第四章 Dify 知识库
    - [4.1 知识库介绍及数据准备](4.%20Dify%20知识库/4.1%20知识库介绍及数据准备.md)
    - [4.2 wordpress的知识库搭建](4.%20Dify%20知识库/4.2%20wordpress的知识库搭建.md)
    - [4.3 知识库agent设计](4.%20Dify%20知识库/4.3%20知识库agent设计.md)
    - [4.4 RAG配置](4.%20Dify%20知识库/4.4%20RAG配置.md)
    - [4.5 实现知识库的应用](4.%20Dify%20知识库/4.5%20实现知识库的应用.md)
- 第五章 Dify workflow设计与实现
    - [5.1 智能体及工具介绍（各种agent框架介绍）](5.%20Dify%20workflow设计与实现/5.1%20智能体及工具介绍.md)
    - [5.2 Dify工作流的实现方式（单元测试）](5.%20Dify%20workflow设计与实现/5.2%20Dify工作流的实现方式.md)
    - [5.3 Dify 实现一个论文抓取工作流](5.%20Dify%20workflow设计与实现/5.3%20Dify%20实现一个论文抓取工作流.md)
    - [5.4 Dify论文分析工作流项目的设计与实现](5.%20Dify%20workflow设计与实现/5.4%20Dify论文分析工作流项目的设计与实现.md)
- 第六章 多智能体
    - [6.1 多智能体设计思路（SOP & React）](6.%20多智能体/6.1%20多智能体设计思路（SOP%20&%20React）.md)
    - [6.2 多智能体workflow](6.%20多智能体/6.2%20多智能体workflow.md)
    - [6.3 多智能体SOP设计思路——以房树人项目为例](6.%20多智能体/6.3%20多智能体SOP设计思路——以房树人项目为例.md)
    - [6.4 多智能体React设计思路——以辩论赛项目为例](6.%20多智能体/6.4%20多智能体React设计思路——以辩论赛项目为例.md)
    - [6.5 基于Dify的一个综合应用项目（UI是streamlit  带知识库 带workflows【sop】的多模态项目）](6.%20多智能体/6.5%20基于Dify的一个综合应用项目（UI是streamlit%20带知识库\).md)
    - [6.6 比赛](#)
#### 5 月 12 日完成第一版

## Dify 框架理解与安装

#### 宇文

1.1 Dify 背景介绍

1.2 Dify 应用可以做出产品及本次课程涉及的内容

1.3 Docker 安装（MAC、Linux、Windows）及常见的坑

1.4 Dify 环境安装

## Dify 单智能体搭建及 api 调用

#### 杜哥  Amy

（应用向 No1 配合直播一节）

2.1 智能体介绍

2.2 Dify 大语言模型引入（Kimi 为例）

2.3 Dify 单智能体如何搭建

2.4 prompt 工程

2.4 Dify 单智能体帮手案例（写个啥案例？还没想好。可以拿往期 agent 比赛的 sota 项目）

2.5 附录：其他各类 api 及大模型如何接入？

2.6 Dify 接口化方法【如何作为项目的一部分】

## Dify with WordPress （你的智能体网页）

#### Amy

（应用向 No2 配合直播一节 可以设计比赛）

3.1 **WordPress 介绍**

3.2 **WordPress 环境搭建及 Dify 结合**

3.3 Dify **创建一个“AI 文本生成”应用**

3.4 **制作 WordPress 标题生成插件**

3.5 Docker 配置

## Dify 知识库

#### 高

（应用向 No3 配合直播一节 可以设计比赛）

4.1 知识库介绍及数据准备

4.2 wordpress 的知识库搭建

4.3 知识库 agent 设计

4.4 RAG 配置

4.5 实现知识库的应用

## Dify workflow 设计与实现

#### 笃驿

（应用向 No4 配合直播一节 可以设计比赛）

5.1 智能体及工具介绍（各种 agent 框架介绍）

5.2 Dify 工作流的实现方式（单元测试）

5.3 Dify 实现一个论文抓取工作流

5.4 Dify 论文分析工作流项目的设计与实现

## 多智能体

#### 杜哥  徐姐姐

（复杂任务设计 这一章写起来很困难……，写好更难）

6.1 多智能体设计思路（SOP & React）

6.2 多智能体 workflow

6.3 多智能体 SOP 设计思路——以房树人项目为例

6.4 多智能体 React 设计思路——以辩论赛项目为例

6.5 基于 Dify 的一个综合应用项目（UI 是 streamlit  带知识库 带 workflows【sop】的多模态项目）

6.6 比赛

## 引用

[1] 使用 Dify 和 Moonshot API 构建你的 AI 工作流（一）：让不 AI 的应用 AI 化- [https://mp.weixin.qq.com/s/qOBZdDiVbv5uSZDKd83-EQ](https://mp.weixin.qq.com/s/qOBZdDiVbv5uSZDKd83-EQ)

[2]最佳实践 ｜ 如何在 Dify 用 Workflow 构建一个 Blog SEO AI 应用？- [https://mp.weixin.qq.com/s/g9Bc777PiliBWtd5I9rJFQ](https://mp.weixin.qq.com/s/g9Bc777PiliBWtd5I9rJFQ)
