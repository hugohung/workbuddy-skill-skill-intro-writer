# 📝 Skill 介绍页文案生成器

> **WorkBuddy Skill** — 为 WorkBuddy Skill 自动生成介绍页文案，按照固定格式输出项目名称、描述、目标、状态和分类

[![Version](https://img.shields.io/github/v/release/hugohung/workbuddy-skill-skill-intro-writer?style=flat-square)](https://github.com/hugohung/workbuddy-skill-skill-intro-writer/releases)
[![License](https://img.shields.io/github/license/hugohung/workbuddy-skill-skill-intro-writer?style=flat-square)](LICENSE)
[![WorkBuddy](https://img.shields.io/badge/WorkBuddy-skill-orange.svg?style=flat-square)](https://www.codebuddy.cn)
[![GitHub Stars](https://img.shields.io/github/stars/hugohung/workbuddy-skill-skill-intro-writer?style=flat-square)](https://github.com/hugohung/workbuddy-skill-skill-intro-writer/stargazers)

---

## 📋 核心能力

本 Skill 自动为 WorkBuddy Skill 生成标准化的介绍页文案，确保格式统一、内容专业。

### ✨ 功能特性

- ✅ **固定格式输出** — 严格遵循「项目名称/项目描述/目标/状态/项目分类」5个字段规范
- ✅ **智能内容提取** — 自动识别 Skill 的核心功能、适用场景和价值点
- ✅ **价值导向输出** — 聚焦 Skill 的提效价值，生成可量化的目标说明
- ✅ **开箱即用** — 无需额外配置，在 WorkBuddy 对话中直接触发

---

## 🎯 适用场景

- 📝 **新 Skill 发布** — 为刚开发的 Skill 生成介绍页文案
- 🔄 **已有 Skill 优化** — 重新撰写更专业的介绍文案
- 📋 **批量生成** — 为多个 Skill 批量生成介绍页
- 🎨 **格式规范化** — 统一所有 Skill 的介绍页格式

---

## 🚀 快速开始

### 使用示例

在 WorkBuddy 对话中直接说：

```
帮我给这个 skill 写个介绍页
```

```
生成 skill 介绍页文案
```

```
为我的新 skill 输出介绍
```

### 输出示例

**输入**：上传一个短剧剧本生成 Skill

**输出**：
```
**项目名称**：京东AI短剧剧本助手

**项目描述**：通过对话生成符合京东规范的短剧剧本、人物设定、场景设定和封面提示词，支持横版/竖版视频格式。

**目标**：
💡 降低短剧剧本创作门槛，创作效率提升80%
💡 自动遵循京东AI短剧规范，减少人工审核次数
💡 一站式完成剧本、人物、场景、封面提示词生成

**状态**：已完成

**项目分类**：内容创作 / 短剧剧本生成
```

---

## 📋 输出格式规范

本 Skill 严格按照以下五个字段、分段文字输出，**不可遗漏或调换顺序**：

```
**项目名称**：<Skill 名称>

**项目描述**：<1-2 句话说明核心功能和用途>

**目标**：<2-3 条价值或提效点，每条以 💡 开头，写在同一段>

**状态**：<进行中 / 已完成 / 规划中 等>

**项目分类**：<一级分类 / 二级分类，如「内容创作 / 短剧剧本生成」>
```

### 字段填写规则

#### 📌 项目名称
直接写 Skill 的名称，不加任何修饰。

#### 📌 项目描述
用 1-2 句话说清楚：
- 这个 Skill 是做什么的（核心功能）
- 它如何工作（通过什么方式/流程）
- 最终交付什么（产出物）

> 💡 语言简洁，避免堆砌功能列表

#### 📌 目标
写 2-3 条该 Skill 带来的价值或提效点，每条以 💡 开头：
- 聚焦「降低了什么成本」「提升了什么效率」「解决了什么痛点」
- 用具体数字或明确结果描述，避免空泛
- 多条目标写在同一段，用换行分隔

#### 📌 状态
根据 Skill 实际情况填写，常用值：
- `进行中` — 正在开发或迭代中
- `已完成` — 功能完整，可正常使用
- `规划中` — 尚未开始开发

#### 📌 项目分类
格式：`<一级分类> / <二级分类>`

**常用一级分类参考**：
- 内容创作
- 内容制作
- 数据分析
- 开发工具
- 自动化
- 研究调研

**二级分类**根据 Skill 具体领域填写，如：短剧剧本生成、分镜与出片、数据可视化等。

---

## 📦 安装方式

### 方式一：WorkBuddy 用户

1. 下载 [最新 Release zip](https://github.com/hugohung/workbuddy-skill-skill-intro-writer/releases/latest)
2. 在 WorkBuddy **技能管理** → **上传技能**，选择 zip 文件
3. 上传完成后无需额外配置，即可在对话中直接使用

### 方式二：从源码安装

```bash
git clone https://github.com/hugohung/workbuddy-skill-skill-intro-writer.git ~/.workbuddy/skills/skill-intro-writer
```

重启 WorkBuddy 即可自动识别该技能。

---

## ⚠️ 注意事项

1. **输出格式严格** — 输出必须为纯文本，不使用表格、代码块或 Markdown 标题
2. **五个字段缺一不可** — 顺序不可调换
3. **项目描述简洁** — 控制在 1-2 句话，避免过长
4. **目标条目适中** — 控制在 2-3 条，过多会显得冗余

---

## 🔗 相关 Skill

- [**GitHub Skill 发布管理工具**](https://github.com/hugohung/workbuddy-skill-github-skill-publisher) — 将 Skill 发布到 GitHub
- [**热门话题及短剧题材调研专家**](https://github.com/hugohung/workbuddy-skill-drama-topic-research) — 调研短剧题材和热点话题

---

## 🐛 问题反馈

如果使用过程中遇到问题，可以通过以下方式反馈：

- 提交 [GitHub Issue](https://github.com/hugohung/workbuddy-skill-skill-intro-writer/issues)
- 在 WorkBuddy 社区寻求帮助

---

## 📄 License

[MIT License](LICENSE)

---

## 👨‍💻 作者

**honghaoxiang**

- GitHub: [@hugohung](https://github.com/hugohung)
- WorkBuddy: [codebuddy.cn](https://www.codebuddy.cn)

---

## 🙏 致谢

- [WorkBuddy](https://www.codebuddy.cn) — 提供 AI 助手平台
- 所有贡献者和用户的支持

---

**⭐ 如果这个 Skill 对你有帮助，欢迎 Star 和分享！**
