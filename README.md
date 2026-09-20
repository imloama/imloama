# 马兆永 · imloama

**技术负责人 / 系统架构师 · 全栈工程师**

写了 17 年后端的工程师，主要用 Go 和 Java。

- 🔭 正在做：Agent 的企业落地——怎么让 Agent 安全地调用企业里那些老旧但关键的真实系统
- 🌱 最近在琢磨：Agent 的长期记忆怎么实现才靠谱，以及 AI Native 系统应该长什么样
- 👯 欢迎找我合作：复杂系统集成、架构设计、Agent 落地，也可以聊聊全职机会（技术负责人 / 架构师方向）
- 💬 可以跟我聊：分布式事务、对账与幂等、微服务拆分、Go 与 Java 的工程实践
- 📫 找我：[www.teamagent.site](https://www.teamagent.site)（技术与交付笔记，工作机会与合作直接联系即可）


**做过的一些事**

🪙 区块链与数字资产

- **数字资产交易平台** — 实时行情、策略执行与自动交易，支持人工决策与 Agent 自动执行两种模式。行情走 REST + WebSocket 双通道，含对账、幂等与熔断风控。Go + PostgreSQL
- **多链托管钱包** — 面向海外用户，支持 Bitcoin、Ethereum 等主流网络，覆盖稳定币收付款与消费场景。用 Saga 管理跨系统一致性，账户、交易与分布式事务是核心。Java + Spring Cloud
- **数字藏品交易平台** — 一站式平台：铸造、发售、转赠、C2C 交易、版权交易与支付对接。高峰抢购场景下支撑约 5 万并发，含私钥与密钥管理。Spring Boot + FISCO BCOS
- **区块链钱包与开放平台** — 跨平台钱包与开发者接入能力，覆盖聚合支付、商户管理、Token 管理与数据存证，对接支付宝、微信、网银及第三方支付。[开源项目](https://github.com/imloama/stellar-desktop-client)

📋 管理端与业务平台

- **智慧社区平台** — 社区管理、防疫管理、便民服务、商户运营与支付一体化。Java / Go 混合微服务架构，对接微信与支付宝
- **企业项目管理系统** — 建筑行业合约、支付与采购模块的架构与研发，完成与财务、供应链系统的集成，支持多个大型施工企业上线
- **AIGC 实训平台** — 多模态能力平台，覆盖文生文、文生图、文生视频与语音识别；含可视化工作流编辑、应用发布与算力计费。Python + Go

Backend engineer for 17 years, mostly in Go and Java. I spend my time on two kinds of things: external systems with no proper documentation, and distributed transactions that must not go wrong.

- 🔭 Working on: bringing AI agents into real enterprises — making it safe for agents to call those old-but-critical internal systems
- 🌱 Digging into: how agent long-term memory should actually work, and what an AI-native system looks like
- 👯 Open to: complex system integration, architecture design, agent adoption — or a full-time role (tech lead / architect)
- 💬 Ask me about: distributed transactions, reconciliation & idempotency, microservice decomposition, Go and Java engineering
- 📫 Reach me: [www.teamagent.site](https://www.teamagent.site) — my notes on engineering & delivery, and the best way to contact me
- ⚡ Fun fact: majored in nuclear engineering, then wrote software for 17 years without ever touching a reactor

**Selected work**

🪙 Blockchain & digital assets

- **Digital-asset trading platform** — real-time market data, strategy execution and automated trading, supporting both manual decisions and agent-driven execution. Market data over REST + WebSocket, with reconciliation, idempotency and circuit-breaker risk controls. Go + PostgreSQL
- **Multi-chain custodial wallet** — for overseas users, supporting Bitcoin, Ethereum and other major networks, covering stablecoin payments and spending. Saga-based cross-system consistency; accounts, transactions and distributed transactions were the core. Java + Spring Cloud
- **Digital collectibles marketplace** — one-stop platform for minting, releases, transfers, C2C and copyright trading, with payment integration. Sustained ~50,000 concurrent requests during high-traffic releases, including key management. Spring Boot + FISCO BCOS
- **Blockchain wallet & open platform** — cross-platform wallet and developer onboarding, covering aggregated payments, merchant management, token management and data attestation, integrated with Alipay, WeChat Pay, online banking and third-party gateways. [Open-source piece](https://github.com/imloama/stellar-desktop-client)

📋 Admin & business platforms

- **Smart community platform** — community management, services, merchant operations and payments in one system. Hybrid Java/Go microservices, integrated with WeChat Pay and Alipay
- **Enterprise project management system** — architecture and development of contract, payment and procurement modules for the construction industry; integrated with finance and supply-chain systems, supporting several large construction enterprises going live
- **AIGC training platform** — multimodal platform covering text/image/video generation and speech recognition, with visual workflow editing, app publishing and compute billing. Python + Go
