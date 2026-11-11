![GitHub Stats](https://coolreadme.xyz/api/stats-card?user=jian-lin-code&theme=dark&accent=jian-lin-code)



AI应用开发 / RAG & Agent 方向后端开发，专注企业知识库、智能Agent落地实践

## 🧑‍💻 关于我
深耕大模型应用层开发，主要做RAG检索增强、多工具AI Agent、文档解析、向量检索系统开发。
习惯用Python构建可工程化、可容器部署的AI应用，熟悉从文档入库、向量存储、检索重排到Agent工具调用全链路。

## 🛠 技术栈
### 大模型 & Agent
- LangChain 生态：Document加载器、文本分割、Retriever、Agent工具调用、记忆管理
- LLM接口封装：兼容OpenAI协议，硅基流动、通义千问等多家大模型接入
- RAG全流程：文档解析 → 文本切块 → Embedding向量化 → 向量检索 → 重排 → 问答生成

### 向量数据库
- Milvus：稠密向量、稀疏向量、混合检索、索引构建
- PGVector：PostgreSQL向量插件，向量+结构化数据一体存储
- Redis：向量检索，LangChain-Redis集成，元数据过滤检索

### ✅ 文档解析
- PDF：pdfplumber、MinerU（复杂表格/图文PDF解析）
- Markdown：MarkdownHeaderTextSplitter 按标题分层切割
- Word：Docx2txtLoader / python-docx
- 通用切块：RecursiveCharacterTextSplitter

## 📂 核心项目

| 项目名称 | 核心技术栈 | 项目简介 | 状态/热度 |
| :--- | :--- | :--- | :--- |
| **[AgentFlow](https://github.com/jian-lin-code/agent-flow)** | `Python` `LangChain` `FastAPI` <br> `PGVector` | 一个基于大模型的智能体（Agent）全栈应用：用户用自然语言完成企业报销办理、业务数据查询与知识库问答。本目录是后端服务，负责 FastAPI 接口、LangGraph 工作流编排、RAG 检索、异步任务与数据持久化。 | [![Stars](https://img.shields.io/github/stars/jian-lin-code/agent-flow?style=social)](https://github.com/jian-lin-code/agent-flow) |
| **[shopkeeper-wisdom](https://github.com/jian-lin-code/shopkeeper-wisdom)** | `Python` `LangChain` `FastAPI` <br> `Milvus` | 一个把 PDF/Markdown 手册解析成图文切片、用稠密 + 稀疏混合向量检索，配合 HyDE 改写召回与联网补充，经 RRF 融合和重排动态截断后，把最相关片段喂给大模型生成有出处、带配图答案的增强检索（RAG）系统。 | [![Stars](https://img.shields.io/github/stars/jian-lin-code/agent-flow?style=social)](https://github.com/jian-lin-code/shopkeeper-wisdom) |
*(注：把上面的 `agent-flow` 和 `agent-flow-admin` 换成你实际推上去的仓库名即可)*

![Hacker](https://coolreadme.xyz/api/hacker?user=jian-lin-code&status=SHIPPING%20CODE&accent=jian-lin-code)

- 邮箱：2367884500@qq.com
