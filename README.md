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
- [注册指南](#注册指南)
- [环境变量配置](#环境变量配置)

---

## 🧠 核心 AI 模型

### OpenAI (GPT-4o/o1)
```bash
# 注册地址: https://platform.openai.com/api-keys
# 费用: 按量付费，新用户送 $5
export OPENAI_API_KEY="sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
export OPENAI_BASE_URL="https://api.openai.com/v1"  # 可选反代
```
**用途**: GPT-4o 对话、o1 推理、DALL-E 图像生成、Whisper 语音

### Anthropic (Claude)
```bash
# 注册地址: https://console.anthropic.com/settings/keys
# 费用: 按量付费
export ANTHROPIC_API_KEY="sk-ant-api03-xxxxxxxx"
```
**用途**: Claude 3.5 Sonnet 长文本、代码生成

### Google (Gemini)
```bash
# 注册地址: https://aistudio.google.com/app/apikey
# 费用: 免费额度充足
export GOOGLE_API_KEY="AIzaSyxxxxxxxxxxxxxxxx"
export GOOGLE_CLIENT_SECRET="your-client-secret.json"
```
**用途**: Gemini Pro 多模态、Google 全家桶集成

### Kimi (Moonshot)
```bash
# 注册地址: https://platform.moonshot.cn/
# 费用: 国内友好定价
export MOONSHOT_API_KEY="sk-xxxxxxxx"
```
**用途**: 长文本处理、中文优化

---

## 🔍 搜索与知识

### Exa.ai (语义搜索)
```bash
# 注册地址: https://exa.ai/
# 费用: 免费版 1000次/月
export EXA_API_KEY="xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx"
```
**用途**: 语义搜索、实体匹配、研究分析

### Tavily (AI 搜索)
```bash
# 注册地址: https://app.tavily.com/
# 费用: 1000次/月免费
export TAVILY_API_KEY="tvly-xxxxxxxxxxxxxxxx"
```
**用途**: 实时搜索、新闻聚合

### Brave Search
```bash
# 注册地址: https://brave.com/search/api/
# 费用: 2000次/月免费
export BRAVE_API_KEY="BSxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 隐私搜索、网页检索

### Perplexity
```bash
# 注册地址: https://www.perplexity.ai/settings/api
# 费用: $5/月起步
export PERPLEXITY_API_KEY="pplx-xxxxxxxxxxxxxxxx"
```
**用途**: 实时问答、研究助手

---

## 💼 生产力工具

### Notion
```bash
# 注册地址: https://www.notion.so/my-integrations
# 步骤: 创建 Integration → 复制 Token
export NOTION_TOKEN="secret_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
export NOTION_DATABASE_ID="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 知识库、项目管理、笔记同步

### Google Workspace
```bash
# 注册地址: https://console.cloud.google.com/apis/credentials
# 步骤: 创建 OAuth 2.0 客户端 → 下载 credentials.json
goog auth credentials /path/to/credentials.json
goog auth add your@gmail.com --services gmail,calendar,drive
```
**用途**: Gmail、Calendar、Drive、Docs、Sheets

### Todoist
```bash
# 注册地址: https://developer.todoist.com/appconsole.html
export TODOIST_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 任务管理、待办同步

### Zapier
```bash
# 注册地址: https://zapier.com/app/settings/api
export ZAPIER_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: 连接 5000+ App 自动化

### AgentMail (Email API Service)
```bash
# 注册地址: https://www.agentmail.to/
export AGENTMAIL_API_KEY="am_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: AI Agent 邮箱收发、一次性邮箱、自动化邮件工作流

---

## 📱 社交媒体

### X/Twitter (Bird)
```bash
# 注册地址: https://developer.twitter.com/en/portal/dashboard
# 步骤: 创建 App → 获取 Bearer Token
export TWITTER_BEARER_TOKEN="AAAAAAAAAAAAAAAAAAAAA..."
export TWITTER_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxx"
export TWITTER_API_SECRET="xxxxxxxxxxxxxxxxxxxxxxxxx"
```

### Telegram Bot
```bash
# 注册地址: https://t.me/botfather
# 步骤: /newbot → 获取 Token
export TELEGRAM_BOT_TOKEN="123456789:ABCdefGHIjklMNOpqrsTUVwxyz"
```

### Slack
```bash
# 注册地址: https://api.slack.com/apps
# 步骤: 创建 App → OAuth & Permissions → Bot Token
export SLACK_BOT_TOKEN="xoxb-xxxxxxxxxxxx-xxxxxxxxxxxx-xxxxxxxxxxxxxxxxxxxxxxxx"
export SLACK_SIGNING_SECRET="xxxxxxxxxxxxxxxxxxxxxxxx"
```

---

## 💻 开发工具

### GitHub
```bash
# 注册地址: https://github.com/settings/tokens
# 步骤: Developer settings → Personal access tokens
export GITHUB_TOKEN="ghp_xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

### GitLab
```bash
# 注册地址: https://gitlab.com/-/profile/personal_access_tokens
export GITLAB_TOKEN="glpat-xxxxxxxxxxxxxxxxxxxx"
```

### Docker Hub
```bash
# 注册地址: https://hub.docker.com/settings/security
export DOCKER_USERNAME="your-username"
export DOCKER_PASSWORD="your-password"
```

---

## 🎨 多媒体

### ElevenLabs (语音合成)
```bash
# 注册地址: https://elevenlabs.io/app/settings/api-keys
# 费用: 免费版 10k 字符/月
export ELEVENLABS_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
**用途**: TTS、语音克隆、多语言配音

### Replicate (AI 图像/视频)
```bash
# 注册地址: https://replicate.com/account/api-tokens
export REPLICATE_API_TOKEN="r8_xxxxxxxxxxxxxxxx"
```
**用途**: Stable Diffusion、视频生成

### OpenAI DALL-E
```bash
# 同 OpenAI API Key
export OPENAI_API_KEY="sk-xxxxxxxx"
```

---

## 🏠 生活服务

### Spotify
```bash
# 注册地址: https://developer.spotify.com/dashboard
export SPOTIFY_CLIENT_ID="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
export SPOTIFY_CLIENT_SECRET="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

### Uber
```bash
# 注册地址: https://developer.uber.com/
export UBER_SERVER_TOKEN="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

### Weather API (OpenWeather)
```bash
# 注册地址: https://openweathermap.org/api
export OPENWEATHER_API_KEY="xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

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
export NOTION_TOKEN=""
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
