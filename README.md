# Hi, I'm MengLong Wang 👋

**AI application engineer based in Shanghai — I turn fuzzy product ideas into shipped AI tools, from data layer to UI.**

9 年研发经验，做过 6 年医疗影像信息化（RIS / PACS / 超声内镜 / 肺结节随访），近一年在车机智能语音场景做
大模型接入、Prompt 与 Function Calling 落地。现居上海，关注 AI Agent、RAG 与全栈交付，
喜欢把「一个模糊需求」独立走完设计、开发、上线与验收。

> 我记录自己做过的东西：项目、工程决策，以及踩过的坑。
> Portfolio & build log → [menglong-build-log.netlify.app](https://menglong-build-log.netlify.app)

## 现在在做什么 · What I'm working on

- 🎮 **LOL-RAG** — 用官方 Data Dragon 数据 + 手写 Function Calling 做的英雄联盟数据 Agent，
  Agent 必须查工具才能回答，前端把每次工具调用轨迹摊开给用户看。
  （173 英雄 / 254 件召唤师峡谷装备 / 数据版本 16.22.1）
- 🧩 **Agent 工具调用** — 研究 function calling 协议、工具白名单、错误回传与多轮循环的边界。
- 📚 **RAG** — 从向量检索的基本原理（embedding、余弦相似度）到可部署的检索服务。

## 关于我 · About

- **能独立交付**：从概要设计、详细设计、数据库设计到编码、测试、实施与验收，做过多个院区的客户化上线。
- **懂行业约束**：医疗数据的合规与交付要求、HIS / CA / 互认平台等第三方系统集成。
- **AI 落地导向**：用 Dify / n8n / Coze / Ollama 搭过知识库、Agent 与工作流；日常用 Cursor / Trae 做开发与重构；
  更关心「能不能稳定上线」，而不是只跑通 Demo。
- **技术底色**：C# / .NET 后端出身，Python、React 是现在的主力。

## Featured Projects

| 项目 | 说明 | 技术栈 | 链接 |
| --- | --- | --- | --- |
| 🆕 **LOL-RAG**<br/>英雄联盟数据 Agent | 官方 Data Dragon 数据入库，模型只能通过 3 个白名单工具回答英雄/装备问题；对话页展示可折叠的工具调用轨迹。 | React · FastAPI · DeepSeek Function Calling · SQLite · Render · Netlify | [repo](https://github.com/wml516518/lol-rag) · Demo: https://lol-rag.netlify.app |
| **KnowledgeOps RAG** | 公开文档问答 Demo：上传解析 → 向量检索 → 基于资料回答，强调可部署的服务边界。 | React · FastAPI · Supabase pgvector · DashScope · Render · Netlify | [repo](https://github.com/wml516518/knowledgeops-rag) · [live](https://knowledgeops-rag-menglong.netlify.app) |
| **Weekend Merge**<br/>周末共识局 | 双人周末决策 Agent：通过可观察的工具调用生成三套折中方案，一方否决后只重排受影响区段。 | React · TypeScript · Gemini Function Calling · Netlify Functions · Open-Meteo | [repo](https://github.com/wml516518/weekend-merge) · [live](https://weekend-merge-wml516518.netlify.app) |
| **个人主页 + 构建日志** | 中英双语作品入口与公开项目记录，中文为唯一人工编辑源，英文由 CI 自动翻译生成。 | React 19 · Vite · TypeScript · Netlify | [repo](https://github.com/wml516518/menglong-build-log) · [live](https://menglong-build-log.netlify.app) |

## 技术栈 · Tech Stack

**AI / LLM**

![DeepSeek](https://img.shields.io/badge/DeepSeek-Function%20Calling-4D6BFE?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Embedding-8A2BE2?style=flat-square)
![Prompt](https://img.shields.io/badge/Prompt-Engineering-FF6B35?style=flat-square)
![Dify](https://img.shields.io/badge/Dify-Workflow-1C64F2?style=flat-square)

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Data & Infra**

![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)

## 经历 · Background

- **上汽海外出行科技** · AI 应用开发工程师（2025.07 – 至今）— 车机智能语音交互系统：大模型接入、语义理解与意图识别、Prompt 迭代、React 前端界面。
- **富士胶片（中国）** · .NET 开发工程师（2019.04 – 2025.04）— 医疗影像信息系统（Fabric 3.0/4.x、Fantasy、CITA、PIS）：独立交付肺结节随访系统，负责跨系统集成与多院区客户化交付。
- **浙江轩威医疗科技** · .NET 软件工程师（2017.11 – 2019.04）— 护士监护信息系统（NIS）模块设计与交付。
- **浙江万里扬** · 软件开发工程师（2016.06 – 2017.10）— 内部管理系统开发与 ERP 二次开发。

详细履历见 [个人主页](https://menglong-build-log.netlify.app)。

## 构建日志 · Build Log

项目背后的取舍都写在 [Build Log](https://menglong-build-log.netlify.app/#/build-log) 里：

- [KnowledgeOps RAG 文档问答](https://menglong-build-log.netlify.app/#/build-log/knowledgeops-rag) — 上传解析、向量检索与可部署服务边界
- [AI Chat Playground](https://menglong-build-log.netlify.app/#/build-log/ai-chat-playground) — 流式聊天界面与 FastAPI 后端层
- [个人主页与构建日志](https://menglong-build-log.netlify.app/#/build-log/portfolio-homepage) — 双语内容与自动翻译流水线

## 联系 · Contact

- GitHub：[@wml516518](https://github.com/wml516518)
- Email：[wml565868@gmail.com](mailto:wml565868@gmail.com)
- Portfolio：[menglong-build-log.netlify.app](https://menglong-build-log.netlify.app)
