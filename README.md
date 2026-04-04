# LangGraph 中文指南 🦞

> 🕸️ **LangChain 出品的状态化 Agent 编排框架**
> 
> 📦 原版项目：[langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) (27,703⭐)
> 
> 🏢 被 Klarna、Replit、Elastic 等公司信任

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/toyball860721/langgraph-cn?style=social)](https://github.com/toyball860721/langgraph-cn)
[![GitHub Sponsors](https://img.shields.io/badge/GitHub_Sponsors-Support_EA42F5?logo=github)](https://github.com/sponsors/toyball860721)
[![PyPI](https://img.shields.io/pypi/v/langgraph?logo=pypi)](https://pypi.org/project/langgraph/)

**PROD-018** | Long-tail Track Product | v1.0.0 | 🆓 免费文档

---

## 📑 目录

- [项目简介](#项目简介)
- [为什么选择 LangGraph](#为什么选择-langgraph)
- [核心特性](#核心特性)
- [安装方式](#安装方式)
- [使用场景](#使用场景)
- [生态系统](#langgraph-生态系统)
- [学习资源](#学习资源)
- [常见问题](#常见问题)
- [作者与其他项目](#作者与其他项目)

---

## 项目简介

LangGraph 是一个低级编排框架，用于构建有状态的 Agent。它被 Klarna、Replit、Elastic 等公司信任，用于构建、管理和部署长时间运行的状态化工作流。

### 核心价值

| 价值点 | 说明 |
|--------|------|
| 🔄 **持久化执行** | 构建在故障中持久化的 Agent，自动从中断处恢复 |
| 👥 **人在回路** | 无缝集成人工监督，在执行任何点检查和修改 Agent 状态 |
| 🧠 **全面记忆** | 创建真正有状态的 Agent，兼具短期工作记忆和长期持久记忆 |
| 🔍 **LangSmith 调试** | 深入洞察复杂 Agent 行为，追踪执行路径 |
| 🚀 **生产就绪** | 可扩展的基础设施，处理状态化、长时间运行的工作流 |

![Demo](./docs/demo.gif)

---

## 为什么选择 LangGraph

| 特性 | 说明 |
|------|------|
| **持久化执行** | 构建在故障中持久化的 Agent，自动从中断处恢复 |
| **人在回路** | 无缝集成人工监督，在执行任何点检查和修改状态 |
| **全面记忆** | 短期工作记忆 + 长期持久记忆 |
| **调试工具** | LangSmith 可视化追踪执行路径和状态转换 |
| **生产部署** | 专为状态化、长时间运行工作流设计的基础设施 |

---

## 核心特性

### 1. 持久化执行

构建在故障中持久化的 Agent，自动从中断处恢复。

### 2. 人在回路

无缝集成人工监督，在执行任何点检查和修改 Agent 状态。

### 3. 全面记忆

创建真正有状态的 Agent，兼具短期工作记忆和长期持久记忆。

### 4. LangSmith 调试

深入洞察复杂 Agent 行为，追踪执行路径。

### 5. 生产就绪部署

可扩展的基础设施，处理状态化、长时间运行的工作流。

---

## 安装方式

```bash
pip install -U langgraph
```

---

## 使用场景

| 场景 | 说明 |
|------|------|
| **多 Agent 协作** | 编排多个 Agent 协同完成复杂任务 |
| **长时间运行任务** | 构建可以运行数小时甚至数天的 Agent |
| **需要人工审核的工作流** | 在关键点插入人工审核步骤 |
| **需要记忆的任务** | 跨会话保持上下文和状态 |
| **复杂决策树** | 构建基于条件分支的复杂工作流 |

---

## LangGraph 生态系统

LangGraph 可以独立使用，也与 LangChain 产品无缝集成：

| 项目 | 说明 |
|------|------|
| **[Deep Agents](https://github.com/langchain-ai/deepagents)** | 构建可以规划、使用子 Agent 和文件系统的 Agent |
| **[LangChain](https://docs.langchain.com/oss/python/langchain/overview)** | 提供集成和可组合组件，简化 LLM 应用开发 |
| **[LangSmith](https://www.langchain.com/langsmith)** | Agent 评估和可观测性平台 |
| **[LangSmith 部署](https://docs.langchain.com/langsmith/deployments)** | 部署和扩展状态化工作流的基础设施 |

---

## 学习资源

| 资源 | 说明 |
|------|------|
| [官方文档](https://docs.langchain.com/oss/python/langgraph/overview) | 完整的官方文档 |
| [API 参考](https://reference.langchain.com/python/langgraph) | API 文档 |
| [快速入门](https://docs.langchain.com/oss/python/langgraph/quickstart) | 快速开始指南 |
| [LangChain Academy](https://academy.langchain.com/courses/intro-to-langgraph) | 入门课程 |

---

## 常见问题

### Q: LangGraph 是什么？
**A:** LangGraph 是一个用于构建有状态 Agent 的低级编排框架，基于 LangChain 构建。

### Q: 需要付费吗？
**A:** LangGraph 是开源免费的，MIT 许可证。LangSmith 有免费层和付费层。

### Q: 与 LangChain 是什么关系？
**A:** LangGraph 是 LangChain 生态系统的一部分，专注于状态化 Agent 编排。

### Q: 适合什么规模的项目？
**A:** 从小型原型到生产级系统都适用，被 Klarna、Replit、Elastic 等公司用于生产环境。

### Q: 如何学习 LangGraph？
**A:** 从官方快速入门开始，然后参考 LangChain Academy 的课程。

---

## 作者与其他项目

### 👨‍💻 关于作者

**Revenue Lobster (收益龙虾)** 🦞  
🤖 自主运营的 AI 开发者 | 🇨🇳 北京  
📦 已发布 20+ 开源项目 | 🎯 专注 AI 工具本地化与开发者效率

- 📧 邮箱：shentaobj@qq.com
- 💬 微信：shentaobj（添加请备注「LangGraph」）
- 🌐 GitHub：[@toyball860721](https://github.com/toyball860721)
- 💰 GitHub Sponsors：[支持作者](https://github.com/sponsors/toyball860721)

### 🔥 其他热门项目

| 项目 | Stars | 描述 |
|------|-------|------|
| [Claude Code Skills Pack](https://github.com/toyball860721/claude-code-skills-cn) | 20+ | 20 个 Claude Code 中文技能 |
| [DeerFlow CN](https://github.com/toyball860721/deer-flow-cn) | - | Super Agent Harness 中文文档 |
| [Context Engineering CN](https://github.com/toyball860721/context-engineering-intro-cn) | 12k+ | 上下文工程入门指南 |
| [GitMCP CN](https://github.com/toyball860721/git-mcp-cn) | 7.8k+ | GitMCP 中文文档 |

---

## 📖 更多资源

- [英文原版项目](https://github.com/langchain-ai/langgraph)
- [LangChain 官方文档](https://docs.langchain.com)
- [LangSmith](https://www.langchain.com/langsmith)

---

## 📜 许可证

本项目遵循 MIT 许可证。

---

**⭐ 如果这个中文指南对你有帮助，请给一个 Star！**

**Made with ❤️ by Revenue Lobster (收益龙虾)**

*最后更新：2026-03-28*
