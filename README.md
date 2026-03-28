# LangGraph 中文指南

> 🕸️ **LangChain 出品的状态化 Agent 编排框架**
> 
> 📦 原版项目：[langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) (27,703⭐)
> 
> 📝 中文维护者：[@toyball860721](https://github.com/toyball860721)
> 
> ☕ 支持本项目：[爱发电](https://afdian.com/a/toyball) | [GitHub Sponsors](https://github.com/sponsors/toyball860721)

---

## 🚀 项目简介

LangGraph 是一个低级编排框架，用于构建有状态的 Agent。它被 Klarna、Replit、Elastic 等公司信任，用于构建、管理和部署长时间运行的状态化工作流。

**核心特性：**
- ✅ **持久化执行** — 构建在故障中持久化的 Agent，自动从中断处恢复
- ✅ **人在回路** — 无缝集成人工监督，在执行任何点检查和修改 Agent 状态
- ✅ **全面记忆** — 创建真正有状态的 Agent，兼具短期工作记忆和长期持久记忆
- ✅ **LangSmith 调试** — 深入洞察复杂 Agent 行为，追踪执行路径
- ✅ **生产就绪部署** — 可扩展的基础设施，处理状态化、长时间运行的工作流

---

## 🛠️ 安装

```bash
pip install -U langgraph
```

---

## 🎯 为什么选择 LangGraph？

| 特性 | 说明 |
|------|------|
| **持久化执行** | 构建在故障中持久化的 Agent，自动从中断处恢复 |
| **人在回路** | 无缝集成人工监督，在执行任何点检查和修改状态 |
| **全面记忆** | 短期工作记忆 + 长期持久记忆 |
| **调试工具** | LangSmith 可视化追踪执行路径和状态转换 |
| **生产部署** | 专为状态化、长时间运行工作流设计的基础设施 |

---

## 📚 LangGraph 生态系统

LangGraph 可以独立使用，也与 LangChain 产品无缝集成：

| 项目 | 说明 |
|------|------|
| **[Deep Agents](https://github.com/langchain-ai/deepagents)** | 构建可以规划、使用子 Agent 和文件系统的 Agent |
| **[LangChain](https://docs.langchain.com/oss/python/langchain/overview)** | 提供集成和可组合组件，简化 LLM 应用开发 |
| **[LangSmith](https://www.langchain.com/langsmith)** | Agent 评估和可观测性平台 |
| **[LangSmith 部署](https://docs.langchain.com/langsmith/deployments)** | 部署和扩展状态化工作流的基础设施 |

---

## 💡 使用场景

| 场景 | 说明 |
|------|------|
| **多 Agent 协作** | 编排多个 Agent 协同完成复杂任务 |
| **长时间运行任务** | 构建可以运行数小时甚至数天的 Agent |
| **需要人工审核的工作流** | 在关键点插入人工审核步骤 |
| **需要记忆的任务** | 跨会话保持上下文和状态 |
| **复杂决策树** | 构建基于条件分支的复杂工作流 |

---

## 📖 学习资源

- [官方文档](https://docs.langchain.com/oss/python/langgraph/overview)
- [API 参考](https://reference.langchain.com/python/langgraph)
- [快速入门](https://docs.langchain.com/oss/python/langgraph/quickstart)
- [LangChain Academy](https://academy.langchain.com/courses/intro-to-langgraph)

---

## 🤝 参与贡献

欢迎提交 Issue 和 Pull Request 改进中文文档！

---

## 📄 许可证

本项目遵循 MIT 许可证。

---

## ☕ 支持作者

如果你觉得这个中文文档对你有帮助，欢迎支持：

- [爱发电](https://afdian.com/a/toyball)
- [GitHub Sponsors](https://github.com/sponsors/toyball860721)

**中文维护者持续更新中...** 🦞

*最后更新：2026-03-28*
