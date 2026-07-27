# AI Product Operations / Casebook

[返回动态主页](README.md) · [查看全部仓库](https://github.com/ggz-max?tab=repositories)

我关注的不是“接入一个模型”，而是如何把 AI 变成真正可用、可控、可复盘的业务能力：识别问题、定义用户和指标、设计工作流、搭建 MVP、接入真实渠道，再根据反馈持续迭代。

## 工作框架

| 洞察 | 设计 | 落地 | 增长 |
| :--- | :--- | :--- | :--- |
| 定位重复劳动、信息断点和体验问题 | 定义场景、指标、状态机与人机边界 | 用 AI 与自动化搭建 MVP，打通业务渠道 | 通过审核、日志、看板和数据持续复盘 |

## 欢乐歌房内容自动化

**[Repository](https://github.com/ggz-max/hl-auto-operation)** · `AI Agent / Content Ops / Growth`

将多平台内容运营拆解成可配置、可审核、可追踪的 AI 工作流。

- 设计 Manager、Copywriter、Visual Designer、Publisher、Analyst 五类 AI 运营角色
- 串联选题、文案、图片/视频、待审队列、发布日志和数据复盘
- 接入快手 OAuth 与视频发布链路，并为抖音、小红书设计差异化发布策略
- 通过人工审核闸门和发布状态机控制内容质量与平台风险

## 企微智能客服系统

**[Repository](https://github.com/ggz-max/gf-kefu)** · `RAG / Customer Experience / Operations`

面向歌房 App 高频咨询，搭建从自动应答到人工兜底的客服闭环。

- 完成分阶段 PRD，覆盖欢迎语、关键词、RAG、转人工与运营看板
- 建设会员、投屏、歌曲、退款等高频场景的产品知识库
- 对接微信客服消息链路，记录会话、回复方式与问题类型
- 设计安全拒答、人工兜底和知识库持续优化路径

## K 歌销售智能复盘系统

**[Repository](https://github.com/ggz-max/sales-report-system)** · `AI Analysis / Sales Ops / CRM`

把分散的销售对话转化为可追踪的客户洞察、产品需求和下一步行动。

- 用 AI 生成商务总结、销售复盘、产品需求和待办
- 围绕厂商沉淀跨对话历史、合作阶段、痛点与跟进任务
- 设计销售端与管理端双视角，并通过飞书推送进入日常协作
- 将非结构化沟通内容转化为结构化业务资产

## HL 数据平台

**[Repository](https://github.com/ggz-max/hl-platform)** · `Data Product / BI / AI Assistant`

让渠道、收入、留存和转化数据从“能看”走向“能问、能解释、能决策”。

- 聚合总览、渠道、广告位、体验与设备到期等经营数据
- 面向管理、运营、商务与财务设计角色化数据视图
- 规划自然语言问数、趋势对比、异常检测和智能报告能力
- 用真实业务问题定义 AI Tool Use，让模型基于数据回答

## KTV 轻产品与小游戏矩阵

**[Repository](https://github.com/ggz-max/-ktv-h5-mini-games)** · `Consumer Product / H5 / Growth Experiments`

基于 KTV 手机点歌的大流量入口，探索可由 H5 快速验证、最终由 App 承接的轻娱乐与用户产品机会。仓库目前包含 11 个独立实验，每个方向都维护调研、产品方案、实现和验证记录。

| 实验 | 核心验证 |
| :--- | :--- |
| KTV 人格宇宙 | 人格卡、收集与分享能否形成唱后传播和 App 承接 |
| 包厢背锅王 | 多人实时选牌与熟人局互动是否具备复玩价值 |
| 搭子掼蛋 | 固定搭档协作、完整牌局和续局机制是否成立 |
| 包厢大扫除 | 90 秒收纳消除玩法能否在点歌入口快速起量 |
| 麦克风跳一跳 | 蓄力、落点与高分挑战能否带来“不服再来” |
| 挪开这个麦 | 顺序解谜、风险路线与关卡扩展是否具备留存潜力 |
| 箭头清场王 | 路径判断和逐层解锁是否适合轻量 H5 复制 |
| 切歌别手滑 | 反应节奏挑战能否形成分享与同局挑战 |

矩阵覆盖单人轻玩法、多人 WebSocket 房间、人格测试、情绪表达、fake-door 与轻量埋点。搭子掼蛋已完成可联机 MVP 并部署 ThunderBox 验证。

## AI 基础设施实践

**[CLIProxyAPI Plus](https://github.com/ggz-max/cliproxy-plus)** 是基于开源项目的定制 fork。在上游能力之上扩展 AnyRouter Provider、GitHub Copilot OAuth、配额展示和管理面板能力，用于理解多模型接入、账户管理、路由与可用性保障。

## 能力矩阵

| 产品与运营 | AI 应用 | 数据与增长 | 技术协作 |
| :--- | :--- | :--- | :--- |
| 用户场景与需求拆解 | Prompt 与 Agent 工作流 | 指标体系与运营看板 | API / OAuth / Webhook |
| PRD 与 MVP 规划 | RAG 与知识库运营 | 内容策略与效果复盘 | Python / JavaScript / SQL |
| 流程、权限与状态机 | Human-in-the-loop | 销售与客服流程优化 | Git / FastAPI / Vue |
