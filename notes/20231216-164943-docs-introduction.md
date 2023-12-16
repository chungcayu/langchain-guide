# Introduction

LangChain 是一个专为开发由语言模型提供动力的应用程序而设计的框架。它赋予应用程序以下能力：

- 上下文感知：将语言模型与各种上下文来源（如提示指令、少样本（few-shot）示例、为回应提供依据的内容等）相连。
- 推理能力：依赖于语言模型进行推理，比如根据提供的上下文决定如何回答问题，或者决定采取什么样的行动等。

这个框架由几个部分组成：

- LangChain Libraries：包括 Python 和 JavaScript 的库。这些库包含了众多组件的接口和集成，一个基本的运行时环境用于组合这些组件成链和智能体（agent），以及一些现成的链和智能体的实现。
- LangChain Templates：这是一个包含了适用于多种任务的易于部署的参考架构的集合。
- LangServe：一个用于将 LangChain 链部署成 REST API 的库。
- LangSmith：一个开发者平台，让您能够在任何大语言模型（LLM）框架上对链进行调试、测试、评估和监控，同时它还能与 LangChain 无缝整合。

这些产品共同简化了应用程序的整个生命周期：

- 开发阶段：您可以在 LangChain 或 LangChain.js 中编写应用程序，并利用模板快速入门。
- 产品化阶段：利用 LangSmith 来检查、测试和监控您的链条，这样您就可以不断完善并自信地部署。
- 部署阶段：通过 LangServe 将任何链条转化为 API。

## LangChain Libraries

LangChain 库的主要价值在于：

- 组件：这些是与语言模型协作的可组合工具和集成。这些组件不仅模块化，而且使用简便，无论您是否使用 LangChain 框架的其他部分。
- 现成的链条：这是内置的组件组合，用于实现更高层次的任务。

现成的链条让初次使用变得简单。而组件的易用性让定制现有链条和构建新链条变得轻松。

LangChain 库本身包括几个不同的包：

- langchain-core：包含基础抽象和 LangChain 表达式语言。
- langchain-community：提供第三方集成。
- langchain：包含构成应用程序认知架构的链条、智能体和检索策略。

## LangChain 表达式语言 (LCEL)

LCEL 是一种用于组合链的声明式方法。从一开始，LCEL 就被设计用于支持将原型直接用于生产环境，而无需更改代码，适用于从最简单的“prompt + LLM”链条到最复杂的链条。

- 概述：介绍 LCEL 及其优点
- 接口：LCEL 对象的标准接口说明
- 操作指南：介绍 LCEL 的主要特点
- 食谱：提供完成常见任务的示例代码

## 模块

LangChain 提供了标准且可扩展的接口和集成，用于以下模块：

- Model I/O（模型 I/O）：用于与语言模型交互的接口。
- Retrieval（检索）：用于与应用程序特定数据交互的接口。
- Agents（智能体）：允许模型根据高层指令选择使用哪些工具。


## Reference

- [Introduction | 🦜️🔗 Langchain](https://python.langchain.com/docs/get_started/introduction)

## Changelog

- 2023-12-16 16:49 Created by Jiayu