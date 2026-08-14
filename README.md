# Hi，我是 TTww 👋

> **AI Agent / LLM 应用工程师** · 专注把大模型从「能聊天」变成「能做事」

我专注于构建**会记忆、会推理、会调用工具**的智能应用：通过 RAG、记忆系统、工具调用与多 Agent 编排，让大模型真正理解用户、自主完成任务。工程底座是扎实的分布式后端能力，能独立完成从系统设计、多存储编排到异步任务的全链路开发。

---

## 🧠 关于我

- 🤖 **Agent 应用**：从单 Agent 工具调用到多 Agent 群聊，完整实现过 Agent 执行循环（原生 function calling / ReAct 回退 / SSE 流式输出）
- 🧬 **记忆系统**：基于 Neo4j 知识图谱的长期记忆——实体-关系三元组抽取、记忆巩固（短期→长期）、社区聚类、反思洞察
- 🔎 **RAG 与知识工程**：混合检索（BM25 + 稠密向量融合 + rerank）、父子块分块、AI 自动分类打标签
- ⚙️ **后端底座**：FastAPI 严格分层架构，PostgreSQL + Elasticsearch + Neo4j + Redis 四存储编排，Celery 异步任务队列

---

## 🛠️ 技术栈

**Agent / LLM 应用**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-混合检索-2FB59C?style=for-the-badge)
![Function Calling](https://img.shields.io/badge/Function_Calling-工具调用-FF6B5E?style=for-the-badge)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent-多智能体-8B7FF0?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-工具生态-2A2438?style=for-the-badge)
![Deep Research](https://img.shields.io/badge/Deep_Research-深度研究-B0885E?style=for-the-badge)

**后端 & 基础设施**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

**前端（辅助）**

![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

---

## 🚀 精选项目

### [CognitiveOS](https://github.com/ttww030126/myFriend)

> 原名 MyFriend（知己），已更名为 CognitiveOS

**个人 AI 知识库 + 记忆助手** —— 记住关于你的一切，把零散信息织成知识网，在对话中调用知识库 / 记忆 / 联网等工具回答问题。

- 🤖 **智能问答 Agent**：原生 function calling，弱模型自动降级 ReAct 模拟，SSE 流式输出
- 🧬 **记忆图谱**：原子陈述 → 三元组抽取 → Neo4j 知识图谱，LPA 社区聚类 + 记忆巩固 + 反思引擎
- 🔎 **混合检索 RAG**：BM25 + 稠密向量融合 + 可选 rerank + 父子块上下文，AI 自动分类打标签
- 🤝 **多 Agent 群聊**：多角色协作，流式编排
- 🔬 **深度研究**：规划 → 多查询检索 → 逐源提炼 → 反思补搜 → 分章节写作
- ⚙️ **工程底座**：FastAPI + PostgreSQL + Elasticsearch + Neo4j + Redis + Celery

`Python` `FastAPI` `Neo4j` `Elasticsearch` `RAG` `Multi-Agent` `Celery`

### [RepoPolit](https://github.com/ttww030126/RepoPolit)

**本地 Coding Agent Harness** —— 面向代码仓库长链路任务的本地 Agent 执行框架，把模型调用、仓库工具、上下文与记忆、权限沙箱、任务恢复、子 Agent 和运行证据统一到可审计的执行状态机。

- 🎛️ **Agent Harness 编排**：模型接入、上下文组装、工具循环、计划待办与工件落盘的统一执行链路，兼容 OpenAI / Anthropic 协议；主 Agent 按需派发只读 / 限域子 Agent，支持异步执行、任务续接与主动终止
- 🧭 **长上下文治理**：上下文拆 6 区段，观测→裁剪→剪枝→摘要 4 级压力治理，长工具输出落盘转摘要引用；5 类基准输入 Token 平均下降约 50.5%，5/5 通过
- 🔐 **工具与安全沙箱**：16 类工具、5 种权限模式，路径 / 符号链接检查 + 读后写校验 + Bubblewrap 沙箱，前后快照识别文件变更
- 🧠 **分层记忆与任务恢复**：工作记忆 / 每日记录 / 长期主题 / 检索索引 4 层记忆，后台 Dream 子 Agent 整理；重复读文件 60→0，Checkpoint 恢复 11 类场景重锚率 100%、误接受率 0%
- 📋 **评测与审计闭环**：Session / Event Stream / Task State / Run Trace / Report 5 类运行证据，224 项自动化测试 + 50 个进程级场景 50/50 通过

`Python` `Agent Harness` `Tool Calling` `Context Management` `Layered Memory` `Run Trace`

---

## 📚 研究 & 学习方向

- 🧠 **长时记忆系统**：短期→长期记忆巩固、知识图谱社区聚类、反思洞察
- 🤝 **多 Agent 协作**：角色编排、群聊、任务分解与执行
- 🔌 **MCP 工具生态**：通过 MCP Server 扩展 Agent 能力边界
- 🔬 **深度研究 Agent**：规划-检索-提炼-反思的自主研究流程
- 📏 **Agent 可靠性**：ReAct 回退、Verifier Loop 质量复核、LLM 评测

---

## 📫 联系我

- 📧 邮箱：599872477@qq.com
- 🐙 GitHub：[@ttww030126](https://github.com/ttww030126)
