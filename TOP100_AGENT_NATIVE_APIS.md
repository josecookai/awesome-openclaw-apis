# Top 100 AI Agent Native 生产力 API（可直接用于 PR）

> 更新时间：2026-03-05（价格与免费额度可能变动，请以官网 Pricing 为准）

## 使用说明
- `价格类型`：`免费` / `免费+收费` / `收费`
- `免费额度`：优先写公开免费额度；没有统一配额时写 `免费试用/沙盒` 或 `无`
- `获取步骤`：统一要求至少 4 步（注册 -> 创建应用/项目 -> 申请 Key/OAuth -> 配置权限并测试）

## 1) 办公协作与知识管理（1-20）

| # | API | 价格类型 | 免费额度 | API 获取步骤（Step by Step） | 解决的问题场景 |
|---|---|---|---|---|---|
| 1 | Gmail API | 免费+收费 | 免费配额（Google Cloud） | 1. 登录 Google Cloud 2. 启用 Gmail API 3. 创建 OAuth Client 4. 配置 Scope 并获取 Token | 自动收发邮件、邮件归档、客服自动回复 |
| 2 | Google Calendar API | 免费+收费 | 免费配额（Google Cloud） | 1. 建项目 2. 启用 Calendar API 3. 创建 OAuth 4. 授权并测试事件读写 | 自动排会、冲突检测、日程提醒 |
| 3 | Google Drive API | 免费+收费 | 免费配额（Google Cloud） | 1. 建项目 2. 启用 Drive API 3. 配置 OAuth/Service Account 4. 分配权限并测试 | 文档自动归档、附件检索、共享管理 |
| 4 | Google Docs API | 免费+收费 | 免费配额（Google Cloud） | 1. 启用 Docs API 2. 配置 OAuth 3. 申请编辑权限 4. 调用文档写入接口 | AI 自动写报告、会议纪要成文 |
| 5 | Google Sheets API | 免费+收费 | 免费配额（Google Cloud） | 1. 启用 Sheets API 2. 创建凭据 3. 授权表格访问 4. 测试读写 | 自动报表、KPI 同步、批量填表 |
| 6 | Microsoft Graph Mail | 免费+收费 | 开发者免费租户 | 1. 注册 Azure 应用 2. 配置 API 权限 3. 创建客户端密钥 4. 获取 OAuth Token | Outlook 邮件自动处理 |
| 7 | Microsoft Graph Calendar | 免费+收费 | 开发者免费租户 | 1. Azure 注册应用 2. 加 Calendar 权限 3. 管理员同意 4. 调用事件接口 | 会议调度、提醒自动化 |
| 8 | Microsoft Graph OneDrive | 免费+收费 | 开发者免费租户 | 1. Azure 应用 2. OneDrive Scope 3. OAuth 授权 4. 文件上传下载测试 | 云盘整理、知识库同步 |
| 9 | Slack Web API | 免费+收费 | 免费工作区可用 | 1. 创建 Slack App 2. 配置 Bot Scope 3. 安装到 Workspace 4. 获取 Bot Token | 告警通知、审批机器人、助手入口 |
| 10 | Notion API | 免费+收费 | 免费版可用 | 1. 创建 Integration 2. 复制 Internal Token 3. 将页面/数据库共享给 Integration 4. 测试查询 | 知识库问答、任务追踪 |
| 11 | Confluence API | 免费+收费 | 免费版可用 | 1. 创建 Atlassian App/Token 2. 获取 Cloud ID 3. 配置权限 4. 调用内容接口 | 文档检索、自动发版说明 |
| 12 | Coda API | 免费+收费 | 免费版可用 | 1. 登录 Coda 开发者页 2. 生成 API Token 3. 获取 Doc ID 4. 测试行写入 | 项目台账自动更新 |
| 13 | Airtable API | 免费+收费 | 免费版可用 | 1. 创建 Base 2. 生成 Personal Access Token 3. 设置 Scopes 4. 调用记录接口 | 运营数据管理、任务清单 |
| 14 | ClickUp API | 免费+收费 | 免费版可用 | 1. 创建账户 2. 生成 API Token 3. 获取 Team/Space/List ID 4. 调用任务接口 | 跨团队任务同步 |
| 15 | Asana API | 免费+收费 | 免费版可用 | 1. 创建 App 2. 生成 PAT/OAuth 3. 授权工作区 4. 调用任务接口 | 项目进度自动更新 |
| 16 | Trello API | 免费+收费 | 免费版可用 | 1. 申请 Key 2. 生成 Token 3. 获取 Board/List ID 4. 调用卡片接口 | 看板自动建卡和分派 |
| 17 | Monday.com API | 免费+收费 | 试用 | 1. 创建账户 2. 生成 API Token 3. 获取 Board ID 4. GraphQL 调用测试 | 销售/运营流程自动化 |
| 18 | Dropbox API | 免费+收费 | 免费版可用 | 1. 创建 App 2. 申请权限 3. 获取 Access Token 4. 调用文件接口 | 文件同步、备份和分享 |
| 19 | Box API | 免费+收费 | 开发者免费层 | 1. 创建 Box App 2. 配置 OAuth2 3. 授权企业/用户 4. 测试文件接口 | 企业文档合规管理 |
| 20 | SharePoint API (Graph) | 免费+收费 | 开发者免费租户 | 1. Azure 注册应用 2. 配 Sites 权限 3. OAuth 授权 4. 调用站点内容接口 | 内网知识检索、文档治理 |

## 2) 开发与工程协同（21-40）

| # | API | 价格类型 | 免费额度 | API 获取步骤（Step by Step） | 解决的问题场景 |
|---|---|---|---|---|---|
| 21 | GitHub API | 免费+收费 | 免费版可用 | 1. 创建 PAT/GitHub App 2. 配置 repo 权限 3. 安装到仓库 4. 调用 Issue/PR API | 自动 code review、PR 流程 |
| 22 | GitLab API | 免费+收费 | 免费版可用 | 1. 生成 Access Token 2. 配置 scope 3. 获取 Project ID 4. 调用 MR/Issue API | CI 状态通知、工单同步 |
| 23 | Jira Cloud API | 免费+收费 | 免费版可用 | 1. 生成 API Token 2. Basic Auth 组合 3. 获取 Cloud URL 4. 调用 issue API | 缺陷分派、状态流转 |
| 24 | Linear API | 免费+收费 | 免费版可用 | 1. 生成 API Key 2. 获取 Team ID 3. 调用 GraphQL API 4. 建立 Webhook | 产品需求自动分解 |
| 25 | Sentry API | 免费+收费 | 免费层可用 | 1. 创建组织项目 2. 生成 Auth Token 3. 配 scope 4. 拉取 issue 数据 | 异常告警自动分类 |
| 26 | PagerDuty API | 免费+收费 | 试用 | 1. 创建账号 2. 生成 API Key 3. 配服务与升级策略 4. 调用事件接口 | 值班告警闭环 |
| 27 | Datadog API | 免费+收费 | 试用 | 1. 创建 Org 2. 获取 API/App Key 3. 配监控资源 4. 调用事件/指标接口 | 监控数据自动汇总 |
| 28 | New Relic API | 免费+收费 | 免费层 | 1. 创建账户 2. 生成 User/API Key 3. 配 NRQL 查询 4. 调用 GraphQL API | 性能报表自动生成 |
| 29 | Cloudflare API | 免费+收费 | 免费版可用 | 1. 创建 Token 2. 配 Zone 权限 3. 绑定域名 4. 调用 DNS/Rules API | 域名/DNS 自动运维 |
| 30 | Vercel API | 免费+收费 | 免费版可用 | 1. 生成 Token 2. 关联项目 3. 配环境变量 4. 调用部署 API | 自动预览部署 |
| 31 | Netlify API | 免费+收费 | 免费版可用 | 1. 创建 Token 2. 获取 Site ID 3. 配 Build Hook 4. 调用 deploy API | 静态站自动发布 |
| 32 | Railway API | 免费+收费 | 试用额度 | 1. 注册账户 2. 创建 Project 3. 生成 Token 4. 调用部署接口 | 后端服务自动发布 |
| 33 | Render API | 免费+收费 | 免费层有限 | 1. 创建账户 2. 生成 API Key 3. 创建服务 4. 调用 deploy/restart | 自动运维/重启服务 |
| 34 | Docker Hub API | 免费+收费 | 免费版可用 | 1. 创建账户 2. 生成 Access Token 3. 绑定仓库 4. 调镜像接口 | 镜像同步与扫描 |
| 35 | Postman API | 免费+收费 | 免费版可用 | 1. 生成 API Key 2. 获取 Workspace ID 3. 调用 Collection API 4. 自动运行测试 | API 文档和测试自动化 |
| 36 | OpenAPI Hub (SwaggerHub) API | 免费+收费 | 试用 | 1. 注册账户 2. 创建 API Key 3. 获取 API ID 4. 调用版本接口 | 接口文档治理 |
| 37 | SonarQube Web API | 免费+收费 | 社区版免费 | 1. 部署/注册 SonarQube 2. 生成 Token 3. 配项目 key 4. 拉取质量指标 | 代码质量自动审查 |
| 38 | Jenkins API | 免费 | 开源免费 | 1. 开启 API Token 2. 生成用户 Token 3. 配 Job 权限 4. 调用 build 接口 | CI/CD 自动触发 |
| 39 | CircleCI API | 免费+收费 | 免费层 | 1. 生成 Personal Token 2. 绑定 VCS 3. 配项目 4. 调工作流 API | 构建结果自动通知 |
| 40 | Buildkite API | 免费+收费 | 试用 | 1. 创建组织 2. 生成 Access Token 3. 配 Pipeline 4. 调用 builds API | 多项目流水线调度 |

## 3) 沟通、邮件与客服（41-60）

| # | API | 价格类型 | 免费额度 | API 获取步骤（Step by Step） | 解决的问题场景 |
|---|---|---|---|---|---|
| 41 | Resend API | 免费+收费 | 有免费层 | 1. 注册 Resend 2. 创建 API Key 3. 验证发信域名 4. 调用 send 接口 | 事务邮件发送 |
| 42 | SendGrid API | 免费+收费 | 有免费层 | 1. 创建账号 2. 生成 API Key 3. 验证 Sender/Domain 4. 测试发送接口 | 通知与营销邮件 |
| 43 | Postmark API | 免费+收费 | 试用 | 1. 创建 Server 2. 获取 Server Token 3. 配发信域名 4. 调用 messages API | 高送达率通知邮件 |
| 44 | Mailgun API | 免费+收费 | 试用/按区 | 1. 创建域名 2. 获取 API Key 3. 配 DNS 4. 调用发送接口 | 邮件网关和验证 |
| 45 | Amazon SES API | 免费+收费 | AWS Free Tier（条件） | 1. 开通 SES 2. 验证域名邮箱 3. 申请退出沙盒 4. 获取 IAM 凭证调用 | 大规模低成本邮件 |
| 46 | AgentMail API | 免费+收费 | 见官网 | 1. 注册账号 2. 创建 API Key 3. 配邮箱身份 4. 测试收发接口 | Agent 收件箱自动化 |
| 47 | Twilio API | 免费+收费 | 试用余额 | 1. 注册 Twilio 2. 获取 SID/Token 3. 购买/绑定号码 4. 调用消息 API | SMS/语音通知 |
| 48 | Vonage API | 免费+收费 | 试用余额 | 1. 创建应用 2. 获取 Key/Secret 3. 配号码 4. 调用 SMS/Voice API | 国际短信/语音 |
| 49 | MessageBird API | 免费+收费 | 试用 | 1. 注册并实名 2. 创建 API Key 3. 绑定通道 4. 调消息接口 | 多渠道通知 |
| 50 | Telegram Bot API | 免费 | 免费 | 1. BotFather 创建机器人 2. 获取 Bot Token 3. 设置 webhook 4. 调 sendMessage | 客服机器人与播报 |
| 51 | Discord API | 免费 | 免费 | 1. 创建应用/Bot 2. 赋权邀请服务器 3. 获取 Token 4. 调用频道消息 API | 社区运营自动化 |
| 52 | Intercom API | 收费 | 试用 | 1. 创建应用 2. 生成 Access Token 3. 配权限 4. 调 conversation API | 客服对话自动处理 |
| 53 | Zendesk API | 收费 | 试用 | 1. 开通 Zendesk 2. 生成 API Token 3. 获取 subdomain 4. 调 tickets API | 工单自动分配 |
| 54 | Freshdesk API | 收费 | 试用 | 1. 获取 API Key 2. 配代理权限 3. 调工单接口 4. 回写状态 | 客服 SLA 管理 |
| 55 | Help Scout API | 收费 | 试用 | 1. 创建 OAuth App 2. 获取 Client 凭据 3. 授权邮箱 4. 调 conversations API | 共享邮箱协作 |
| 56 | Front API | 收费 | 试用 | 1. 生成 API Token 2. 授权 inbox 3. 配规则 4. 调会话接口 | 多人收件箱自动路由 |
| 57 | Gorgias API | 收费 | 试用 | 1. 创建私有应用 2. 获取 key 3. 绑定店铺 4. 调 ticket API | 电商客服自动回复 |
| 58 | Crisp API | 免费+收费 | 免费层 | 1. 创建 website 2. 生成 token 3. 配 webhook 4. 调会话接口 | 网站在线客服自动化 |
| 59 | LiveChat API | 收费 | 试用 | 1. 创建 app 2. OAuth 授权 3. 配 agent 权限 4. 调 chats API | 客服分配与质检 |
| 60 | WhatsApp Cloud API (Meta) | 免费+收费 | 免费会话额度（条件） | 1. Meta 开发者注册 2. 创建应用 3. 配 WABA 与 Token 4. 测试消息发送 | WhatsApp 客户触达 |

## 4) CRM、销售与营销（61-80）

| # | API | 价格类型 | 免费额度 | API 获取步骤（Step by Step） | 解决的问题场景 |
|---|---|---|---|---|---|
| 61 | HubSpot API | 免费+收费 | 免费 CRM 层 | 1. 创建私有应用 2. 配 scopes 3. 获取 token 4. 调 contacts/deals API | 线索自动分配 |
| 62 | Salesforce API | 收费 | 试用沙盒 | 1. 创建 Connected App 2. OAuth 设置 3. 获取实例 URL 4. 调 sObject API | 企业销售流程自动化 |
| 63 | Pipedrive API | 免费+收费 | 试用 | 1. 生成 API Token 2. 获取 company domain 3. 调 deal/person API 4. 配 webhook | 销售漏斗更新 |
| 64 | Zoho CRM API | 免费+收费 | 免费版有限 | 1. 注册 Zoho API Console 2. 创建客户端 3. OAuth 授权 4. 调 CRM 模块 API | 客户档案同步 |
| 65 | Copper API | 收费 | 试用 | 1. 开启 API access 2. 获取 token/email 3. 配权限 4. 调 lead/opportunity API | Google 生态 CRM 自动化 |
| 66 | Close API | 收费 | 试用 | 1. 生成 API Key 2. 获取组织 ID 3. 调 lead/call API 4. 自动记要 | 销售电话跟进 |
| 67 | Klaviyo API | 免费+收费 | 免费层 | 1. 创建 Private Key 2. 设置 scopes 3. 配事件流 4. 调 profiles/campaigns API | 电商营销自动触达 |
| 68 | Mailchimp API | 免费+收费 | 免费层 | 1. 生成 API Key 2. 获取 server prefix 3. 建 audience 4. 调 campaign API | 邮件营销分群 |
| 69 | Brevo API | 免费+收费 | 免费层 | 1. 创建 API key 2. 配 sender 3. 上传联系人 4. 调事务邮件/自动化 API | 营销+通知一体 |
| 70 | Customer.io API | 收费 | 试用 | 1. 获取 Track/App API Key 2. 配 workspace 3. 发送事件 4. 调 campaign API | 生命周期自动触达 |
| 71 | Braze API | 收费 | 试用 | 1. 开通实例 2. 获取 REST API Key 3. 配消息通道 4. 调触达接口 | 多渠道营销编排 |
| 72 | Iterable API | 收费 | 试用 | 1. 获取 API Key 2. 配项目 3. 导入用户 4. 调 campaign/event API | 增长运营自动化 |
| 73 | Segment API | 免费+收费 | 免费层 | 1. 创建 Source 2. 获取 Write Key 3. 配 Destination 4. 调 track/identify API | 数据采集与分发 |
| 74 | Mixpanel API | 免费+收费 | 免费层 | 1. 创建项目 2. 获取 token/secret 3. 上报事件 4. 调报表 API | 行为分析闭环 |
| 75 | Amplitude API | 免费+收费 | 免费层 | 1. 创建项目 2. 获取 API Key/Secret 3. 上报事件 4. 查询分析 API | 漏斗与留存分析 |
| 76 | GA4 Data API | 免费+收费 | 免费配额（Google） | 1. 开通 GA4 2. 启用 Data API 3. 创建服务账号 4. 调 runReport | 网站增长看板 |
| 77 | Clearbit API | 收费 | 试用 | 1. 注册并获取 key 2. 配 enrich 请求 3. 调 person/company API 4. 回写 CRM | 线索补全 |
| 78 | Apollo API | 收费 | 试用 | 1. 创建 API key 2. 配组织权限 3. 调 prospect API 4. 同步到 CRM | 销售找客与外呼名单 |
| 79 | Lemlist API | 收费 | 试用 | 1. 生成 API key 2. 配邮箱域名 3. 创建活动 4. 调 lead API | 外联邮件自动化 |
| 80 | Typeform API | 免费+收费 | 免费层 | 1. 创建应用 2. 获取 Personal Token 3. 配表单 4. 拉取响应 API | 线索表单收集 |

## 5) 支付、合同与财务（81-90）

| # | API | 价格类型 | 免费额度 | API 获取步骤（Step by Step） | 解决的问题场景 |
|---|---|---|---|---|---|
| 81 | Stripe API | 免费+收费 | 免费测试环境 | 1. 注册 Stripe 2. 获取 Secret Key 3. 配 webhook 4. 测试支付意图 | 收款、订阅和账单自动化 |
| 82 | PayPal API | 免费+收费 | 免费沙盒 | 1. 创建 app 2. 获取 Client ID/Secret 3. 用 Sandbox 测试 4. 切生产环境 | 跨境收款自动化 |
| 83 | Adyen API | 收费 | 测试环境 | 1. 开通账户 2. 创建 API 凭据 3. 配 webhook 4. 测支付接口 | 企业级收单 |
| 84 | Square API | 免费+收费 | 免费开发者账户 | 1. 创建应用 2. 获取 Access Token 3. 配位置/商品 4. 调 payments/orders API | 门店与线上收单 |
| 85 | Braintree API | 免费+收费 | 沙盒 | 1. 创建商户 2. 获取 key 三件套 3. SDK 接入 4. 调交易接口 | 订阅与支付网关 |
| 86 | QuickBooks API | 收费 | 试用 | 1. Intuit 创建应用 2. OAuth2 授权 3. 获取 Company ID 4. 调 invoice/payment API | 发票与财务同步 |
| 87 | Xero API | 收费 | 试用 | 1. 创建应用 2. OAuth2 授权 3. 获取 Tenant ID 4. 调 accounting API | 会计自动记账 |
| 88 | Plaid API | 免费+收费 | 免费开发环境 | 1. 创建应用 2. 获取 client_id/secret 3. 用 sandbox 测试 4. 调账户接口 | 银行数据连接 |
| 89 | Wise API | 收费 | 沙盒 | 1. 开发者注册 2. 创建 token 3. 开启 profile 权限 4. 调 quotes/transfers API | 跨境转账自动化 |
| 90 | DocuSign API | 收费 | 开发者沙盒 | 1. 创建集成 key 2. 配 OAuth 回调 3. 申请 JWT/Code Grant 4. 调 envelopes API | 合同签署自动化 |

## 6) 数据、检索与 Agent 基础设施（91-100）

| # | API | 价格类型 | 免费额度 | API 获取步骤（Step by Step） | 解决的问题场景 |
|---|---|---|---|---|---|
| 91 | Supabase API | 免费+收费 | 免费层 | 1. 创建项目 2. 获取 anon/service key 3. 配 RLS 4. 调 REST/Realtime API | Agent 后端与状态存储 |
| 92 | Firebase API | 免费+收费 | Spark 免费层 | 1. 创建 Firebase 项目 2. 启用所需服务 3. 生成服务账号 4. 调 Firestore/Auth API | 移动+Web 数据同步 |
| 93 | Hasura API | 免费+收费 | OSS 免费/云试用 | 1. 部署 Hasura 2. 配数据库连接 3. 生成 Admin Secret 4. 调 GraphQL API | 快速搭建业务 API |
| 94 | Snowflake API | 收费 | 试用 | 1. 创建账户 2. 生成 Key Pair/OAuth 3. 配 warehouse/role 4. 调 SQL API | 企业数仓查询 |
| 95 | BigQuery API | 免费+收费 | 免费层（按月） | 1. 创建 GCP 项目 2. 启用 BigQuery API 3. 创建服务账号 4. 调查询接口 | BI 报表和数据分析 |
| 96 | Elasticsearch API | 免费+收费 | 开源免费 | 1. 部署集群 2. 创建 API Key 3. 建索引 4. 调检索接口 | 全文搜索与日志检索 |
| 97 | Algolia API | 免费+收费 | 免费构建层 | 1. 创建应用 2. 获取 Admin/Search Key 3. 建索引 4. 调搜索 API | 站内搜索优化 |
| 98 | Pinecone API | 免费+收费 | 免费 Starter | 1. 创建项目 2. 生成 API Key 3. 创建 index 4. upsert/query 向量 | RAG 检索增强 |
| 99 | Weaviate API | 免费+收费 | OSS 免费/云试用 | 1. 部署/开通实例 2. 获取 key 3. 建 schema 4. 调对象与向量查询 | 语义检索与知识图谱 |
| 100 | Qdrant API | 免费+收费 | OSS 免费/云免费层 | 1. 部署 Qdrant 2. 生成 API key 3. 建 collection 4. 调 upsert/search API | 低成本向量存储检索 |

## 建议放入 README 的入口文案

```md
- [Top 100 AI Agent Native 生产力 API 清单](./TOP100_AGENT_NATIVE_APIS.md)
```

## 维护规则（建议）
- 每月复核一次 `免费额度` 与 `定价页`
- 有官方公开配额数字时，补充到对应条目
- 价格不稳定时标注“以官网实时价格为准”
