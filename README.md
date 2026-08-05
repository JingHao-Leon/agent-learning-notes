<div align="center">

# agent-learning-notes

**Agent 学习资料集合 —— 书籍整理稿与阅读笔记，沉淀 AI Agent 从入门到生产落地的完整知识体系**

[![Top Language](https://img.shields.io/github/languages/top/JingHao-Leon/agent-learning-notes)](https://github.com/JingHao-Leon/agent-learning-notes)
[![Last Commit](https://img.shields.io/github/last-commit/JingHao-Leon/agent-learning-notes)](https://github.com/JingHao-Leon/agent-learning-notes/commits/main)
[![Repo Size](https://img.shields.io/github/repo-size/JingHao-Leon/agent-learning-notes)](https://github.com/JingHao-Leon/agent-learning-notes)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)

[![开始阅读](https://img.shields.io/badge/%F0%9F%93%96%20%E5%BC%80%E5%A7%8B%E9%98%85%E8%AF%BB-1f5fa8?style=for-the-badge)](./ai_agents_book_full.md)

</div>

---

本仓库用于沉淀个人的 Agent 学习资料与阅读整理：书籍的 Markdown 整理稿、导出 PDF，以及后续陆续补充的笔记与摘要。当前核心内容是《AI Agents 实战指南》中文整理稿 —— 基于 Micheal Lanham《AI Agents in Action》重写并大幅扩展，覆盖 **15 章 + 3 个附录**，含 70+ 图解、40+ 实战案例、100+ 中英术语对照。

## 📚 当前收录

<table>
<tr>
<td width="50%">

### 📖 《AI Agents 实战指南》
基于《AI Agents in Action》（Micheal Lanham）重写的中文整理稿。从「什么是 Agent」讲到多 Agent 协作、企业级落地，15 章循序渐进，每章配架构图解与可运行的 Python 示例。

- 📝 [Markdown 版](./ai_agents_book_full.md) —— 适合在线阅读、检索
- 📄 [PDF 版](./ai_agents_book_full.pdf) —— 适合下载收藏、离线阅读

</td>
<td width="50%">

### 🗺️ 内容覆盖
- **基础入门**（第 1-3 章）：Agent 概念、LLM 访问、第一个 Agent
- **核心组件**（第 4-7 章）：Profile、工具调用、记忆、推理评估
- **多 Agent 与编排**（第 8-13 章）：AutoGen、CrewAI、行为树、Semantic Kernel、Prompt Flow
- **前沿与落地**（第 14-15 章）：前沿主题、企业实战
- **附录**：工具速查表、中英术语表、学习路径

</td>
</tr>
</table>

## 🧭 全书知识路线

按附录 C 的推荐学习路径，全书 15 章分为五个递进阶段：

```mermaid
flowchart TD
    A["🌱 阶段一：入门<br>第1章 Agent 概述 · 第2章 访问 LLM · 第3章 第一个 Agent"]
    B["🧩 阶段二：单 Agent 开发<br>第4章 Profile/Persona · 第5章 工具调用 · 第6章 记忆知识 · 第7章 推理评估"]
    C["🤝 阶段三：多 Agent 系统<br>第8章 多 Agent 基础 · 第9章 AutoGen · 第10章 CrewAI"]
    D["🎛️ 阶段四：高级编排<br>第11章 行为树编排 · 第12章 Semantic Kernel · 第13章 Prompt Flow"]
    E["🏢 阶段五：落地生产<br>第14章 前沿探索 · 第15章 企业落地实战"]
    A --> B --> C --> D --> E
```

## 📋 章节目录速览

| 章节 | 主题 | 你会学到 |
|---|---|---|
| 第 1 章 | AI Agent 概述 | Agent 定义、六层架构、四层演进、五大核心组件 |
| 第 2 章 | 访问大语言模型 | OpenAI / Claude / Gemini / Ollama 等接入方式与 API 参数 |
| 第 3 章 | 构建你的第一个 Agent | Function Calling、Assistants API、日历助手等完整实战 |
| 第 4 章 | Profile 与 Persona 设计 | 角色定义、行为规范、人格化 Agent |
| 第 5 章 | Actions 与工具调用 | 工具设计、函数映射、多工具协同 |
| 第 6 章 | 记忆与知识系统 | 短期/长期记忆、向量数据库（Chroma）、RAG |
| 第 7 章 | 推理与评估机制 | CoT、自我反思、结果评估 |
| 第 8 章 | 多 Agent 系统基础 | 多 Agent 协作模式、AutoGen / CrewAI 入门 |
| 第 9 章 | AutoGen 高级应用 | 群组对话、Agent 互调、专家协作 |
| 第 10 章 | CrewAI 企业级应用 | 角色/任务/Crew、层级流程、并行执行 |
| 第 11 章 | 行为树与 Agent 编排 | py_trees 行为树、复杂任务编排 |
| 第 12 章 | Semantic Kernel 与插件系统 | 插件机制、原生函数注册 |
| 第 13 章 | Prompt Flow 与系统性评估 | 评估 rubric、对比测试、流程化管理 |
| 第 14 章 | 前沿主题深度探索 | Agent 前沿研究方向 |
| 第 15 章 | 企业落地实战 | 企业知识库 RAG、客服 Agent 完整方案 |
| 附录 A-C | 工具速查 / 术语表 / 学习路径 | 平台速查表、100+ 中英术语对照、0→1→生产路线 |

## 🚀 如何使用

- **在线阅读**：直接在 GitHub 上打开 [ai_agents_book_full.md](./ai_agents_book_full.md)，支持目录跳转与全文搜索
- **离线阅读**：进入 [ai_agents_book_full.pdf](./ai_agents_book_full.pdf) 文件页面，点击 Download 下载
- **克隆到本地**：

```bash
git clone https://github.com/JingHao-Leon/agent-learning-notes.git
```

## 📁 仓库结构

```
├── ai_agents_book_full.md    # 《AI Agents 实战指南》Markdown 整理稿（15 章 + 3 附录）
├── ai_agents_book_full.pdf   # 同内容 PDF 导出版
├── LICENSE                   # MIT License
└── README.md
```

## 🗓️ Roadmap

- [x] 《AI Agents 实战指南》整理稿（md + pdf）
- [ ] 分章节阅读笔记与摘要
- [ ] 更多 Agent 方向书籍/论文的整理与笔记

## ⚖️ 版权与合规

- 仓库中的整理稿为个人学习笔记性质的内容，仅供学习与交流使用。
- 如包含受版权保护的材料，发布/分发前请确保你拥有相应授权；如权利人要求移除内容，将及时配合处理。
- 仓库本身的原创内容（如本 README、后续笔记）按 [MIT License](./LICENSE) 开放。

---

<div align="center">
<sub>
个人学习沉淀，持续更新 ｜ 内容如有疏漏，欢迎 Issue 指正<br>
Made with ❤️ by <a href="https://github.com/JingHao-Leon">JingHao-Leon</a>
</sub>
</div>
