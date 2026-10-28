<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=620&lines=Building+AI+Agents+that+actually+ship;Multi-Agent+%C2%B7+RAG+%C2%B7+Tool+Calling;From+prototype+to+production+pipeline" alt="Typing SVG" />

**Zachary** · 专注 LLM Agent 工程：任务规划、工具调用、检索溯源，以及把 AI 能力做成可批量运行的生产流水线。

</div>

## 🔭 Focus

- **Multi-Agent 编排**：主 Agent 拆解任务，子 Agent 并行执行，审查 Agent 校验结果；大小模型分工控制成本
- **可溯源 RAG**：文档解析与分块、BM25 + 向量混合检索、重排，每条结论都能回到出处
- **AI 生产流水线**：FastAPI + Celery 编排 TTS、Remotion、FFmpeg，处理幂等、补偿、并发与超时
- **可观测性**：Langfuse 追踪 Agent 每一步调用，Prometheus / Grafana / Loki 看服务状态

## 🧩 Featured Projects

| 项目 | 说明 | 技术 |
| --- | --- | --- |
| [personalized-travel-multi-agent](https://github.com/mizane446/personalized-travel-multi-agent) | 多 Agent 出行方案系统：搜索证据、偏好 Wiki 与方案生成串成一条可溯源的链路 | Hermes · Multi-Agent · Langfuse |
| [Travel_agent](https://github.com/mizane446/Travel_agent) | 基于 LangChain v1 Agent Loop 的旅行规划：模型自主调度攻略 RAG、地图、天气、路线、预算工具，输出结构化行程 | LangChain · Tool Calling · RAG |
| [AI-notebook](https://github.com/mizane446/AI-notebook) | 本地优先的 AI 文件整理工具：拖入即解析、自动分类，自然语言检索 | Python · LLM · Windows |

## 🌱 Open Source

正在给这些 Agent 框架提交修复（review 中）：

- **[run-llama/llama_index#23717](https://github.com/run-llama/llama_index/pull/23717)** — 修复 `FunctionTool` 在参数带 `Field` 默认值时签名丢失
- **[Aider-AI/aider#5907](https://github.com/Aider-AI/aider/pull/5907)** — `--message-file` 读取失败时返回非零退出码
- **[huggingface/smolagents#3072](https://github.com/huggingface/smolagents/pull/3072)** — 修复韩文安装文档的导航链接

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,redis,mysql,postgres,docker,react,ts,grafana,prometheus,git,linux&perline=12" alt="Tech stack" />
</p>

**Agent**：LangChain · LangGraph · Tool Calling · Agent Skills　**AI Coding**：Claude Code · Codex · Cursor

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mizane446/mizane446/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/mizane446/mizane446/output/github-snake.svg" alt="Contribution snake" />
</picture>

<p align="center"><sub>Made with <a href="https://github.com/mizane446/github-profile-optimizer">github-profile-optimizer</a></sub></p>
