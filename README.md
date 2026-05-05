# Hi, I'm LongJie

**AI 应用工程师 | Python 后端工程师（2026 应届）**

专注于 **AI 应用系统（RAG / Agent / 多模态） + 高并发后端架构** 的工程化落地，具备从模型接入到系统设计到部署上线的完整实践经验。

---

## 关于我

- 四川民族学院 - 数据科学与大数据技术（本科）
- 两段企业实习，参与多个真实业务系统开发
- 专注方向：
  - AI 应用工程（RAG / Text-to-SQL / Agent / 多智能体）
  - Python 后端架构（FastAPI / 异步 / 微服务 / 高并发）
  - 数据系统 & 数据分析

---

## 技术栈

### 后端开发

- Python / FastAPI / Django / AsyncIO 异步编程
- RESTful API / WebSocket 实时通信
- 微服务架构 / RBAC 权限系统

### AI 应用开发

- RAG（LangChain）/ Text-to-SQL / AI Agent / 多智能体系统
- MCP 工具调用 / Prompt Engineering
- LLM 集成（OpenAI / Anthropic / Ollama）

### 数据与存储

- MySQL / PostgreSQL / Redis
- pgvector 向量检索 / Kafka 消息队列
- 多级缓存设计（L1/L2）

### 多模态能力

- STT：Whisper / FunASR / SherpaONNX
- TTS：GPT-SoVITS / CosyVoice / Edge-TTS
- 情感分析 / 语音交互 / Live2D 控制

### 工程能力

- Docker 容器化部署 / Docker Compose 编排
- Git 协作开发 / 前后端分离架构
- 数据库设计 / 索引优化 / 性能调优

---

## 核心项目

### Synapse - 多智能体 AI 应用平台

> 面向复杂任务的多智能体 AI 平台，支持任务规划、RAG 检索与工具调用

**GitHub: [LongJie686/synapse](https://github.com/LongJie686/synapse)**

- 多智能体编排：Supervisor / Parallel / Hierarchical / Collaboration 四种模式 + Plan-Execute
- RAG 系统：文档解析 → 分块 → 向量化 → 检索 → 上下文注入（支持 5+ 文档格式）
- 成本优化：cost-aware routing + 自动降级 + 上下文压缩，Token 消耗降低约 40%~60%
- 记忆系统：短期对话 + 长期向量存储 + 用户画像，支持跨会话上下文
- 工具调用：基于 MCP 协议实现 15+ 工具接入与动态扩展

**关键词：Multi-Agent / RAG / LangChain / pgvector**

### 电商推荐系统（微服务架构）

> 基于微服务架构的电商推荐系统，支持高并发访问与推荐计算场景

**GitHub: [LongJie686/ecommerce-microservices](https://github.com/LongJie686/ecommerce-microservices)**

- 微服务架构：API 网关 + 用户 + 商品 + 推荐 + 爬虫 + 数据分析 6 个服务独立部署
- 高并发优化：L1 本地缓存 + L2 Redis 多级缓存，P90 延迟 42ms，较无缓存降低约 80%
- 系统稳定性：JWT 鉴权 + 限流（Redis + Lua）+ 熔断降级（Circuit Breaker）
- 数据管道：Kafka 异步消息 + 布隆过滤去重 + 行为日志处理
- 推荐策略：协同过滤 + 内容推荐 + 热度加权混合策略，支持 AB 测试分流
- 数据库优化：复合索引 + 覆盖索引 + EXPLAIN 调优

**关键词：微服务 / 高并发 / Redis 缓存 / Kafka / 推荐系统**

### 智能问数系统（ChatBI）

> 企业级 AI 数据分析平台：自然语言 → SQL → 可视化

- 多数据源支持（MySQL / PostgreSQL / ClickHouse 等）
- Text-to-SQL 智能查询引擎
- AI 看板（ECharts / AntV）+ PPT 导出
- 企业微信 OAuth 集成 + 数据权限隔离

**关键词：RAG / Text-to-SQL / 数据分析平台**

### AI 数字人交互系统

> 多模态 AI 实时交互平台（语音 + 情感 + 动作）

- STT → LLM → 情感分析 → 动作控制 → TTS 全链路
- WebSocket 实时通信（100+ 并发）
- 8+ STT 引擎 + 10+ TTS 引擎集成
- Live2D 动作控制 + 对话记忆

**关键词：多模态 AI / 实时交互 / Agent**

---

## 在线知识库

持续更新的技术沉淀：[longjie686.github.io/backend-notes](https://longjie686.github.io/backend-notes/)

内容涵盖：

- 后端架构设计 & 高并发系统
- AI 应用开发（RAG / Agent / 多智能体）
- 数据库 & 性能优化（MySQL / Redis）
- 微服务架构设计

---

## 实习经历

**成都矢量科技有限公司**（2025.10 - 2026.03）

- 智能问数系统（ChatBI）：NL2SQL + 多数据源 + AI 看板
- 链路健康监测系统（LinkMon）：iperf3 + SNMP + 告警
- 错误根因分析系统：配置化诊断流程 + 故障定位

**四川奇点引擎科技有限公司**（2025.07 - 2025.10）

- AI 数字人交互系统：全链路多模态交互
- 智能印刷管理系统（CRM + AI）：日处理订单 200+

---

## 联系方式

- Email: longchengjie686@gmail.com
- GitHub: [github.com/LongJie686](https://github.com/LongJie686)
- 知识库: [longjie686.github.io/backend-notes](https://longjie686.github.io/backend-notes/)

---

## 自我评价

具备 AI 应用系统与后端工程的综合能力，能够独立完成从系统设计、模型集成到工程落地的完整开发流程。在多智能体系统、RAG、Text-to-SQL 等方向有实际项目经验，具备较强的工程实现能力与性能优化意识（缓存、异步、消息队列等）。

有良好的问题拆解能力与技术自驱力，长期跟进前沿技术，持续总结 AI 应用与后端架构实践。
