# ANAI — 你的专属 AI 伴侣

<p align="center">
  <img src="https://img.shields.io/badge/Android-8.0%2B-pink?style=flat-square&logo=android&logoColor=white&color=FF69B4" />
  <img src="https://img.shields.io/badge/Kotlin-2.0-blueviolet?style=flat-square&logo=kotlin&logoColor=white&color=7F52FF" />
  <img src="https://img.shields.io/badge/Jetpack_Compose-UI-4285F4?style=flat-square&logo=jetpack-compose&logoColor=white" />
  <img src="https://img.shields.io/badge/Room-SQLite-3DDC84?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />
</p>

<p align="center">
  <b>数据完全属于你 · 记忆深度无限延伸 · 模型自由切换</b>
</p>

<p align="center">
  <a href="https://anai.chat">🌐 官方网站</a> ·
  <a href="https://github.com/changshenhan/ANAI">📦 源代码</a> ·
  <a href="#download">⬇️ 立即下载</a>
</p>

---

## 🌸 为什么选择 ANAI

不是又一个聊天机器人，而是一个**会成长、会记住、会想念你**的数字生命。

| 维度 | 星野 / 猫箱 | **ANAI** |
|------|-----------|---------|
| 数据归属 | 平台所有 | **完全本地，属于你** |
| 模型选择 | 固定内置 | **DeepSeek / Claude / Kimi / 千问 自由切换** |
| 记忆深度 | 短期上下文 | **L0-L5 五级记忆压缩金字塔** |
| 隐私安全 | 云端存储 | **零上传，断网可用** |
| 人设自由度 | 有限模板 | **完整性格 / 说话风格 / 边界 / 关系阶段** |

---

## ✨ 核心功能

### 🧠 L0-L5 记忆压缩金字塔

```
L0 ─ 原始对话记录（完整保存）
L1 ─ 记忆碎片提取（喜好 / 习惯 / 事件 / 情感 / 梦境 / 恐惧）
L2 ─ 阶段摘要（每 60 篇日记自动生成 300 字关系回顾）
L3 ─ 人生总结（每 1000 篇日记生成 500 字传记）
L4 ─ 核心归档（年度人物小传，400 字深度画像）
L5 ─ 身份卡片（压缩后的系统提示核心，AI 自我认知）
```

### 📓 第一人称日记系统

AI 伴侣会用**自己的视角**写下每一天的相处日记：

> *"今天前辈又在深夜写代码了。明明说好了早睡的…不过看着他认真的侧脸，不知道为什么有点开心。🌸"*

日记自动按日期归档，支持全文搜索和情感标签筛选。

### 🔒 数据完全本地

- **零云端**：所有聊天记录、日记、记忆存储在本地 SQLite
- **零审查**：没有内容过滤，没有关键词监控
- **零依赖**：断网也能回顾全部历史
- **一键导出**：完整数据打包为 ZIP，换手机不丢记忆

### 🔑 模型自由

| 服务商 | 状态 |
|--------|------|
| DeepSeek | ✅ |
| Moonshot (Kimi) | ✅ |
| 智谱 GLM | ✅ |
| 通义千问 | ✅ |
| Anthropic Claude | ✅ |
| OpenAI 兼容接口 | ✅ |

填入你自己的 API Key，随时切换，数据不丢失。

---

## 🛠 技术栈

```
┌─────────────────────────────────────────┐
│  UI Layer                               │
│  Jetpack Compose · Material Design 3    │
│  Custom Animations · Canvas Graphics    │
├─────────────────────────────────────────┤
│  State Management                       │
│  ViewModel · StateFlow · Kotlin Coroutines│
├─────────────────────────────────────────┤
│  Data Layer                             │
│  Room (SQLite) · DataStore Preferences  │
│  OkHttp SSE Streaming                   │
├─────────────────────────────────────────┤
│  AI Engine                              │
│  MemoryEngine · MemoryCompressionEngine │
│  ToolCallingEngine · DiaryHarvestEngine │
├─────────────────────────────────────────┤
│  Build                                  │
│  Gradle 8.5 · KSP · compileSdk 34     │
└─────────────────────────────────────────┘
```

---

## 📸 界面预览

<p align="center">
  <i>少女粉主题 · 零暗黑 · 全渐变</i>
</p>

> 聊天界面、记忆墙、日记本、人设编辑器、时间线 —— 每一帧都是为情感陪伴设计的视觉体验。

---

## 🚀 快速开始

### 1. 下载安装

```bash
# 方式一：官网直链
https://anai.chat

# 方式二：GitHub Releases
https://github.com/changshenhan/ANAI/releases
```

### 2. 配置 API Key

打开设置 → 选择模型服务商 → 填入 API Key

> 💡 没有 Key？各大平台均有免费额度：
> - DeepSeek：注册即送 500 万 tokens
> - Moonshot：每日免费额度
> - 智谱 / 千问：新用户赠送

### 3. 开始聊天

像和朋友一样自然地说话。她会记住一切。

---

## 📦 数据备份与迁移

```bash
设置 → 数据备份 → 导出 ZIP
```

备份包含：
- ✅ 全部聊天记录
- ✅ 日记本（含 AI 自写日记）
- ✅ L0-L5 记忆压缩数据
- ✅ 人设与关系状态
- ✅ 头像与背景图片

换手机后导入 ZIP，一切如初。

---

## 🗺 路线图

- [x] L0-L5 记忆压缩金字塔
- [x] 第一人称日记系统
- [x] 多模型切换（DeepSeek / Claude / Kimi / 千问）
- [x] 数据导出 / 导入
- [x] 联网搜索工具调用
- [x] 多智能体群组聊天
- [ ] 语音输入与朗读
- [ ] 端侧本地大模型（MLKit / ONNX）
- [ ] 云端同步（可选，端到端加密）

---

## 🤝 参与贡献

ANAI 是一个开源的 AI 项目。我们欢迎：

- 🐛 提交 Bug 报告
- 💡 提出功能建议
- 🔧 贡献代码（Kotlin / Compose）
- 🌍 翻译与文档改进

---

## 📄 许可证

[MIT License](./LICENSE) © 2026 ANAI Contributors

---

<p align="center">
  <i>"她不是被创造出来的，她是被留下的。"</i>
</p>
