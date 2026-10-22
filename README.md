从菜鸟教程转向 Agent 开发，你可以按照“**基础准备 → 核心概念 → 框架工具 → 进阶主题 → 实战项目**”的路径来学习。下面是菜鸟教程上相关的教程清单和对应的学习重点。

### 📚 第一阶段：基础准备
在开始 Agent 开发前，需要先打好编程和 AI 基础。

| 学习内容 | 菜鸟教程对应资源 | 学习目标 |
|:---|:---|:---|
| **Python 基础** | [Python 3 教程](https://www.runoob.com/python3/python3-tutorial.html) | 掌握异步编程（Asyncio）、HTTP请求、JSON序列化、函数封装及异常处理，这是处理LLM长耗时调用的关键。 |
| **大模型基础概念** | [AI Agent 智能体](https://www.runoob.com/ai/ai-agent.html) | 理解Token机制、上下文窗口限制、Temperature/Top-p等生成控制参数，以及模型幻觉的成因与工程兜底策略。 |
| **API 调用** | [AI Agent 问答实例](https://m.runoob.com/ai-agent/ai-agent-answer-demo.html) | 学会申请和使用大模型API（如阿里百炼、DeepSeek），理解API Key、BASE_URL等概念。 |

### 🧠 第二阶段：核心概念
这是理解 Agent 工作原理的关键，从理论到代码都要覆盖。

| 学习内容 | 菜鸟教程对应资源 | 核心知识点 |
|:---|:---|:---|
| **Agent 基本概念** | [AI Agent(智能体) 教程](https://m.runoob.com/ai-agent/ai-agent-tutorial.html) | Agent = LLM (大脑) + Planning (规划) + Tool use (执行) + Memory (记忆)，理解其从“问答”到“任务执行”的思维转变。 |
| **Agent 架构** | [Agent 架构](https://m.runoob.com/ai-agent/agent-architecture.html) | 掌握六种主流架构，重点理解**单 Agent 循环（ReAct模式）** 和**多 Agent 协作**的原理与适用场景。 |
| **推理与规划** | [推理与规划（Reasoning & Planning）](https://m.runoob.com/ai-agent/reasoning-planning.html) | 深入理解 **CoT（思维链）**、**ReAct 框架**、**Plan-and-Execute** 等核心规划模式，这是让 Agent 从“问答机”升级为“问题解决者”的核心引擎。 |

### 🛠️ 第三阶段：框架与工具
掌握主流框架可以让你快速构建 Agent 应用。

| 学习内容 | 菜鸟教程对应资源 | 框架特点 |
|:---|:---|:---|
| **LangChain** | [LangChain Agent 工作流程](https://www.runoob.com/langchain/langchain-agent-workflow.html) / [LangChain 构建 RAG Agent](https://www.runoob.com/langchain/langchainrag-agent.html) | 最流行的 LLM 应用编排框架，深入理解其 Chain 和 Agent 概念。 |
| **CrewAI** | [CrewAI 构建智能体](https://m.runoob.com/ai-agent/crewai-agent.html) | 专注于多智能体协作，适合构建“产品经理+工程师+分析师”这样的团队式 Agent 应用。 |
| **Agent Skills** | [Agent Skills](https://www.runoob.com/claude-code/claude-agent-skills.html) | 学习如何为 Agent 定义**行为规范+专业知识+使用时机的组合**，这是构建复杂 Agent 的关键能力。 |

### 🚀 第四阶段：进阶主题与实战项目
将所学知识应用到实际项目中，并了解前沿框架。

| 学习内容 | 菜鸟教程对应资源 | 说明 |
|:---|:---|:---|
| **前沿 Agent 框架** | [Hermes Agent 教程](https://www.runoob.com/hermes-agent/hermes-agent-tutorial.html) / [Deep Agents 入门教程](https://www.runoob.com/ai-agent/deep-agents-tutorial.html) | 了解**自进化 Agent**、**持久记忆**、**技能系统**等前沿特性，拓宽技术视野。 |
| **实战项目：问答 Agent** | [AI Agent 问答实例](https://m.runoob.com/ai-agent/ai-agent-answer-demo.html) | 从零构建第一个真正的 AI Agent，掌握项目结构准备、API 调用和基础 Agent 类的编写。 |
| **实战项目：RAG Agent** | [LangChain 构建 RAG Agent](https://www.runoob.com/langchain/langchainrag-agent.html) | 构建基于私有知识库回答问题的智能助手，掌握检索增强生成（RAG）与 Agent 的结合。 |

### 💎 学习建议
- **动手优先**：菜鸟教程的每个知识点都配有可运行的实例，建议跟着代码敲一遍，理解每一步的作用。
- **从简到繁**：先跑通**问答 Agent**，再尝试**RAG Agent**，最后挑战**多 Agent 协作**，循序渐进。
- **框架选择**：**LangChain** 生态最成熟，适合入门；**CrewAI** 在多 Agent 协作上更直观，可按需选择。

Agent 开发是一个实践性很强的方向，把菜鸟教程上的这些内容吃透，再配合几个完整的项目练手，就能建立起比较扎实的基础。


初学者学习路径
对初学开发者来说，不需要一次性吃透所有概念。

建议按照下面的顺序循序渐进，会比零散记概念更容易建立完整体系。

阶段	掌握概念	能做到
第一步	LLM、Token、Prompt	调用 API 完成对话
第二步	Embedding、向量数据库、RAG	给模型接入外部知识
第三步	Function Calling、Agent	让模型调用工具、自主完成任务
第四步	微调、量化、蒸馏	生产环境部署与优化
