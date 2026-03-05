# Awesome OpenClaw APIs

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> AI Native API 注册指南 - 为你的 OpenClaw 配置最强 AI 能力

[English](./README.md) | [中文](./README.zh.md)

---

## 📋 目录

- [核心 AI 模型](#核心-ai-模型)
- [搜索与知识](#搜索与知识)
- [生产力工具](#生产力工具)
- [社交媒体](#社交媒体)
- [开发工具](#开发工具)
- [多媒体](#多媒体)
- [生活服务](#生活服务)
- [Top 100 场景清单](#top-100-场景清单)
- [注册指南](#注册指南)
- [环境变量配置](#环境变量配置)

---

## 🧠 核心 AI 模型

### OpenAI (GPT-4o/o1)
```bash
# 注册地址: https://platform.openai.com/api-keys
# 费用: 免费+收费（按量）
# 免费额度: 新用户通常有试用额度（以账号页面为准）
# 步骤: 注册账号 → 创建 API Key → 绑定支付方式（可选）→ 调用 /v1 接口测试
export OPENAI_API_KEY="sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
export OPENAI_BASE_URL="https://api.openai.com/v1"  # 可选反代
```
**用途**: GPT-4o 对话、o1 推理、DALL-E 图像生成、Whisper 语音

### Anthropic (Claude)
```bash
# 注册地址: https://console.anthropic.com/settings/keys
# 费用: 按量付费
# 免费额度: 通常提供试用额度（以账号页面为准）
# 步骤: 注册控制台 → 创建 API Key → 配置 billing → 调用 messages 接口测试
export ANTHROPIC_API_KEY="sk-ant-api03-xxxxxxxx"
```
**用途**: Claude 3.5 Sonnet 长文本、代码生成

### Google (Gemini)
```bash
# 注册地址: https://aistudio.google.com/app/apikey
# 费用: 免费+收费（按量）
# 免费额度: 提供免费层（按模型和地区不同）
# 步骤: 登录 AI Studio → 创建 API Key → 配置项目权限 → 调用 Gemini 接口测试
export GOOGLE_API_KEY="AIzaSyxxxxxxxxxxxxxxxx"
export GOOGLE_CLIENT_SECRET="your-client-secret.json"
```
**用途**: Gemini Pro 多模态、Google 全家桶集成

### Kimi (Moonshot)
```bash
# 注册地址: https://platform.moonshot.cn/
# 费用: 免费+收费（按量）
# 免费额度: 新用户通常有试用额度（以平台为准）
# 步骤: 注册平台 → 创建 API Key → 充值或开通额度 → 调用对话接口测试
export MOONSHOT_API_KEY="sk-xxxxxxxx"
```
**用途**: 长文本处理、中文优化

---

## 🔍 搜索与知识

### Exa.ai (语义搜索)
```bash
# 注册地址: https://exa.ai/
# 费用: 免费+收费
# 免费额度: 免费版约 1000 次/月（以官网为准）
# 步骤: 注册账号 → 创建 API Key → 选择检索模式 → 调用 search 接口测试
export EXA_API_KEY="xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"
```
**用途**: 语义搜索、实体匹配、研究分析

### Tavily (AI 搜索)
```bash
# 注册地址: https://app.tavily.com/
# 费用: 免费+收费
# 免费额度: 免费层约 1000 次/月（以官网为准）
# 步骤: 注册账号 → 生成 API Key → 配置搜索参数 → 调用 search 接口测试
export TAVILY_API_KEY="tvly-xxxxxxxxxxxxxxxx"
```
**用途**: 实时搜索、新闻聚合

### Brave Search
```bash
# 注册地址: https://brave.com/search/api/
# 费用: 免费+收费
# 免费额度: 免费层约 2000 次/月（以官网为准）
# 步骤: 注册开发者账号 → 创建订阅/API Key → 配置请求参数 → 调用查询接口测试
export BRAVE_API_KEY="BSxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 隐私搜索、网页检索

### Perplexity
```bash
# 注册地址: https://www.perplexity.ai/settings/api
# 费用: 收费（按量/套餐）
# 免费额度: 通常无长期免费额度（以官网为准）
# 步骤: 开通账号 → 进入 API 设置页 → 创建 API Key → 调用 chat/completions 测试
export PERPLEXITY_API_KEY="pplx-xxxxxxxxxxxxxxxx"
```
**用途**: 实时问答、研究助手

---

## 💼 生产力工具

### AgentMail (Email API Service)
```bash
# 注册地址: https://www.agentmail.to/
# 费用: 免费+收费（以官网为准）
# 免费额度: 以官网套餐页为准
# 步骤: 注册账号 → 创建 API Key → 配置邮箱身份/域名 → 调用收发信接口测试
export AGENTMAIL_API_KEY="am_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: AI Agent 邮箱收发、一次性邮箱、自动化邮件工作流

### Google Workspace
```bash
# 注册地址: https://console.cloud.google.com/apis/credentials
# 费用: 免费+收费（Google Cloud 用量计费）
# 免费额度: Google Cloud 免费层/试用金（以账号为准）
# 步骤: 创建 OAuth 2.0 客户端 → 下载 credentials.json
goog auth credentials /path/to/credentials.json
goog auth add your@gmail.com --services gmail,calendar,drive
```
**用途**: Gmail、Calendar、Drive、Docs、Sheets

### Notion
```bash
# 注册地址: https://www.notion.so/my-integrations
# 费用: 免费+收费
# 免费额度: 免费版可用
# 步骤: 创建 Integration → 复制 Token
export NOTION_TOKEN="secret_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
export NOTION_DATABASE_ID="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 知识库、项目管理、笔记同步

### Resend (Email API)
```bash
# 注册地址: https://resend.com/emails
# 费用: 免费+收费（以官网为准）
# 免费额度: 提供免费层（以官网为准）
# 步骤: 注册账号 → 创建 API Key → 验证发信域名 → 调用发送接口测试
export RESEND_API_KEY="re_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 事务邮件发送、邮件模板、开发者友好 Email API

### Todoist
```bash
# 注册地址: https://developer.todoist.com/appconsole.html
# 费用: 免费+收费
# 免费额度: 免费版可用
# 步骤: 登录开发者后台 → 创建应用 → 获取 API Token → 调用任务接口测试
export TODOIST_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 任务管理、待办同步

### Zapier
```bash
# 注册地址: https://zapier.com/app/settings/api
# 费用: 免费+收费
# 免费额度: 免费版任务额度有限
# 步骤: 创建 Zapier 账号 → 进入开发者/API 页面 → 生成 Key 或创建 App → 连接并测试
export ZAPIER_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 连接 5000+ App 自动化

---

## 📱 社交媒体

### X/Twitter (Bird)
```bash
# 注册地址: https://developer.twitter.com/en/portal/dashboard
# 费用: 免费+收费（分层套餐）
# 免费额度: 免费层能力有限（以官网为准）
# 步骤: 创建 App → 获取 Bearer Token
export TWITTER_BEARER_TOKEN="AAAAAAAAAAAAAAAAAAAAA..."
export TWITTER_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxx"
export TWITTER_API_SECRET="xxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 社媒监听、自动发帖、舆情追踪

### Telegram Bot
```bash
# 注册地址: https://t.me/botfather
# 费用: 免费
# 免费额度: 免费
# 步骤: /newbot → 获取 Token
export TELEGRAM_BOT_TOKEN="123456789:ABCdefGHIjklMNOpqrsTUVwxyz"
```
**用途**: 机器人通知、客服问答、命令自动化

### Slack
```bash
# 注册地址: https://api.slack.com/apps
# 费用: 免费+收费（按工作区套餐）
# 免费额度: 免费工作区可用
# 步骤: 创建 App → OAuth & Permissions → Bot Token
export SLACK_BOT_TOKEN="xoxb-xxxxxxxxxxxx-xxxxxxxxxxxx-xxxxxxxxxxxxxxxxxxxxxxxx"
export SLACK_SIGNING_SECRET="xxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 团队协作通知、审批流、Agent 对话入口

---

## 💻 开发工具

### GitHub
```bash
# 注册地址: https://github.com/settings/tokens
# 费用: 免费+收费
# 免费额度: 免费版可用
# 步骤: Developer settings → Personal access tokens
export GITHUB_TOKEN="ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: PR/Issue 自动化、代码托管集成

### GitLab
```bash
# 注册地址: https://gitlab.com/-/profile/personal_access_tokens
# 费用: 免费+收费
# 免费额度: 免费版可用
# 步骤: 登录 GitLab → 创建 Personal Access Token → 选择 scopes → 调用 API 测试
export GITLAB_TOKEN="glpat-xxxxxxxxxxxxxxxxxxxx"
```
**用途**: 仓库管理、CI/CD 状态联动

### Docker Hub
```bash
# 注册地址: https://hub.docker.com/settings/security
# 费用: 免费+收费
# 免费额度: 免费版可用
# 步骤: 登录 Docker Hub → 创建 Access Token → 配置仓库权限 → 调用 API/CLI 测试
export DOCKER_USERNAME="your-username"
export DOCKER_PASSWORD="your-password"
```
**用途**: 镜像仓库同步、镜像发布自动化

---

## 🎨 多媒体

### ElevenLabs (语音合成)
```bash
# 注册地址: https://elevenlabs.io/app/settings/api-keys
# 费用: 免费+收费
# 免费额度: 免费版约 10k 字符/月（以官网为准）
# 步骤: 注册账号 → 创建 API Key → 选择语音模型/音色 → 调用 TTS 接口测试
export ELEVENLABS_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: TTS、语音克隆、多语言配音

### Replicate (AI 图像/视频)
```bash
# 注册地址: https://replicate.com/account/api-tokens
# 费用: 收费（按量）
# 免费额度: 通常无长期免费额度（以官网为准）
# 步骤: 注册账号 → 生成 API Token → 选择模型 → 调用 predictions 接口测试
export REPLICATE_API_TOKEN="r8_xxxxxxxxxxxxxxxx"
```
**用途**: Stable Diffusion、视频生成

### OpenAI DALL-E
```bash
# 注册地址: https://platform.openai.com/api-keys
# 费用: 收费（按量）
# 免费额度: 取决于 OpenAI 账户试用额度
# 步骤: 创建 OPENAI_API_KEY → 选择图像模型 → 调用图像生成接口 → 下载结果
export OPENAI_API_KEY="sk-xxxxxxxx"
```
**用途**: AI 图片生成、营销素材自动化

---

## 🏠 生活服务

### Spotify
```bash
# 注册地址: https://developer.spotify.com/dashboard
# 费用: 免费+收费（取决于业务场景）
# 免费额度: 开发者模式可用
# 步骤: 创建 App → 获取 Client ID/Secret → 配置回调地址 → 调用 Web API 测试
export SPOTIFY_CLIENT_ID="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
export SPOTIFY_CLIENT_SECRET="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 音乐检索、播放控制、内容推荐

### Uber
```bash
# 注册地址: https://developer.uber.com/
# 费用: 收费（按业务）
# 免费额度: 无统一免费额度（以官网为准）
# 步骤: 注册开发者账号 → 创建应用 → 获取凭证 → 调用可用业务 API
export UBER_SERVER_TOKEN="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 出行服务联动、行程状态同步

### Weather API (OpenWeather)
```bash
# 注册地址: https://openweathermap.org/api
# 费用: 免费+收费
# 免费额度: 免费层可用（调用次数有限）
# 步骤: 注册账号 → 生成 API Key → 选择天气接口 → 调用并校验返回
export OPENWEATHER_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 天气查询、出行建议、运营排班辅助

---

## 📚 Top 100 场景清单

- [Top 100 AI Agent Native 生产力 API 清单](./TOP100_AGENT_NATIVE_APIS.md)

---

## 📝 快速注册指南

### 优先级排序

| 优先级 | API | 注册时间 | 难度 | 免费额度 |
|--------|-----|---------|------|---------|
| ⭐⭐⭐⭐⭐ | OpenAI | 5分钟 | 简单 | $5 赠送 |
| ⭐⭐⭐⭐⭐ | Exa.ai | 3分钟 | 简单 | 1000次/月 |
| ⭐⭐⭐⭐⭐ | Notion | 10分钟 | 中等 | 免费 |
| ⭐⭐⭐⭐ | Anthropic | 5分钟 | 简单 | $5 赠送 |
| ⭐⭐⭐⭐ | Google | 15分钟 | 复杂 | 免费 |
| ⭐⭐⭐ | ElevenLabs | 5分钟 | 简单 | 10k字符/月 |
| ⭐⭐⭐ | Tavily | 3分钟 | 简单 | 1000次/月 |
| ⭐⭐ | Twitter | 30分钟 | 复杂 | 有限 |
| ⭐⭐ | Replicate | 5分钟 | 简单 | 按需付费 |

### 推荐注册顺序

**第1天（基础）:**
1. OpenAI API Key
2. Exa.ai API Key
3. Notion Integration

**第2天（增强）:**
4. Google OAuth
5. Anthropic API Key
6. Tavily API Key

**第3天（扩展）:**
7. ElevenLabs API Key
8. Telegram Bot Token
9. GitHub Token

---

## 🔐 环境变量配置模板

创建 `~/.openclaw_env` 文件：

```bash
#!/bin/bash
# OpenClaw API Keys 配置
# 使用方法: source ~/.openclaw_env

# === AI 模型 ===
export OPENAI_API_KEY=""
export ANTHROPIC_API_KEY=""
export GOOGLE_API_KEY=""
export MOONSHOT_API_KEY=""

# === 搜索 ===
export EXA_API_KEY=""
export TAVILY_API_KEY=""
export BRAVE_API_KEY=""
export PERPLEXITY_API_KEY=""

# === 生产力 ===
export AGENTMAIL_API_KEY=""
export NOTION_TOKEN=""
export RESEND_API_KEY=""
export TODOIST_API_KEY=""
export ZAPIER_API_KEY=""

# === 社交 ===
export TWITTER_BEARER_TOKEN=""
export TELEGRAM_BOT_TOKEN=""
export SLACK_BOT_TOKEN=""

# === 开发 ===
export GITHUB_TOKEN=""

# === 多媒体 ===
export ELEVENLABS_API_KEY=""
export REPLICATE_API_TOKEN=""

echo "✅ OpenClaw API 环境变量已加载"
```

添加到 `~/.bashrc`：
```bash
echo "source ~/.openclaw_env" >> ~/.bashrc
```

---

## 🤝 贡献指南

### 提交新 API

**PR 格式:**

```markdown
## 新增 API: [API名称]

**基本信息:**
- 名称: 
- 类型: [AI模型/搜索/生产力/社交/开发/多媒体/生活服务]
- 官网: 
- 定价: 

**注册步骤:**
1. 访问 [注册链接]
2. 步骤...
3. 获取 API Key

**环境变量:**
```bash
export API_NAME="your-key"
```

**使用示例:**
```bash
# 示例代码
```

**测试状态:**
- [ ] 已注册
- [ ] 已测试
- [ ] 已配置环境变量

**附加信息:**
- 是否有地区限制?
- 是否需要信用卡?
- 免费额度多少?
```

### API 收录标准

✅ **接受收录:**
- 稳定运行的服务
- 有明确的 API 文档
- 合理的定价策略
- 不违反法律法规

❌ **不接受:**
- 已停止服务的 API
- 无文档或支持
- 恶意或侵犯隐私
- 违反平台政策

---

## 📊 API 分类统计

```
总 API 数: 20+
AI 模型: 4
搜索知识: 4
生产力: 4
社交媒体: 3
开发工具: 3
多媒体: 3
生活服务: 3
```

---

## 📜 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

本清单采用 [CC0 1.0 Universal](LICENSE) 协议。

---

> **提示**: API Key 请妥善保管，不要提交到公开仓库！
