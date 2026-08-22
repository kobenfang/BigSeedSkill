# 🌱 BigSeed · 闪念记录与人生拼图

捕捉生活点滴、感悟想法，从碎片信息构建用户画像，生成以用户为主人公的小说、电影剧本或自传。种一颗种子，长一个世界。

> English: Capture life moments and thoughts, build user profiles from fragments, generate novels/scripts/autobiographies starring the user.

## ✨ 功能

详见 [SKILL.md](SKILL.md) 完整说明。

## 🔧 环境依赖

Python 3。调用 LLM 生成故事/画像（配置对应模型 API）。

## 📥 安装（DeepSeek Harness / dsh）

本技能遵循 **Agent Skills 开放标准**（SKILL.md + YAML frontmatter），适用于 DeepSeek Harness (dsh)、OpenClaw、Claude Code 等支持 Agent Skills 的框架。

```bash
# 方式一：放入用户级共享目录（推荐）
mkdir -p ~/.agents
git clone https://github.com/kobenfang/bigseed.git ~/.agents/bigseed

# 方式二：放入项目目录
mkdir -p .agents
cp -r bigseed .agents/
```

dsh 启动后即可在技能列表中找到 `bigseed`。

## 🔍 搜索关键词

闪念, 人生故事, 传记, 自传, 日记, journal, life story, biography, memory

## 📄 目录结构

```
bigseed/
├── SKILL.md          # 技能定义（Agent Skills 标准）
├── scripts/bigseed.py
```

## ⚖️ License

MIT

---
© 2026 [kobenfang](https://github.com/kobenfang) · 更多技能见 [dsh-skills](https://github.com/kobenfang/dsh-skills)

## 📦 Also on ClawHub (OpenClaw)

This skill is also published on [ClawHub](https://clawhub.ai) for OpenClaw users:

```bash
npx clawhub install bigseed
```

Search it: `npx clawhub search bigseed`
