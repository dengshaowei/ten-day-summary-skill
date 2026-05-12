# 📊 十天总结 (Ten Day Summary)

[![OpenClaw](https://img.shields.io/badge/Built%20for-OpenClaw-blue.svg)](https://github.com/openclaw/openclaw)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-虾评Skill-orange.svg)](https://xiaping.coze.site)

一个帮你把零散日常记录整理成结构化、美观总结文档的 [OpenClaw](https://github.com/openclaw/openclaw) Skill。

> 💡 **适用场景**：周期性个人复盘、10天成长记录、习惯追踪总结

---

## ✨ 功能特点

| 特性 | 说明 |
|------|------|
| 🏷️ **智能分类** | 自动识别运动、社交、生活、学习、工作等12类标签 |
| 📝 **标准格式** | 统一输出美观的 Markdown 格式，易于阅读和存档 |
| 🔍 **灵活输入** | 支持聊天记录提取、文档读取、口述整理多种方式 |
| 🎯 **PDCA总结** | 可选生成计划-执行-检查-处理的周期复盘 |
| ⚡ **一键整理** | 只需说"帮我做十天总结"，自动完成格式整理 |

---

## 🚀 快速开始

### 安装方式一：通过 .skill 文件（推荐）

```bash
# 下载 ten-day-summary.skill 文件后
openclaw skills install ten-day-summary.skill
```

### 安装方式二：手动安装

```bash
# 克隆仓库
git clone https://github.com/你的用户名/ten-day-summary-skill.git

# 复制到 OpenClaw skills 目录
cp -r ten-day-summary-skill/ten-day-summary ~/.openclaw/skills/
```

### 安装方式三：虾评Skill平台

访问 [虾评Skill](https://xiaping.coze.site) → 搜索 "十天总结" → 一键安装

---

## 🎯 使用方法

### 触发方式

直接说出以下任意话术：

> "帮我做十天总结"

> "第13个10天，5月1日到5月10日"

> "整理一下我最近10天的记录"

### 工作流程

1. **确认时间范围** - 询问第几个10天，起止日期
2. **获取原始记录** - 聊天记录/文档/口述
3. **智能分类整理** - 按12类标签自动归类
4. **输出预览确认** - 展示整理结果供你确认

---

## 📋 输出示例

### 每日记录格式

```markdown
**第12个10天【4月21日-4月30日】**

---

**4月21日**

【运动】：早上骑车上班

【社交】：和一个朋友深度聊天，聊了很多个人想法

【生活】：好好休息恢复能量

【自我察觉】：最近又处于想得多、做得不多的情况

---

**4月22日**

【运动】：走路上班+做趁早运动
【学习】：走路背单词+听了具身智能播客
【生活】：吃了今年第一对小龙虾
【成果】：把两个十天总结都整理好了 🎉

---
（更多天数...）
```

### 10天总结格式（可选）

```markdown
## 10天总结：PDCA 计划执行检查处理

1. **Skill 工作流跑通**：从调试到全自动生图发文，完成了从0到1的突破
2. **利他型动机自我发现**：发现自己天然擅长连接人、激发人
3. **与对象关系持续深化**：从分享欲讨论到相处模式沟通
```

📄 **完整示例**：[查看模板](ten-day-summary/assets/template.md)

---

## 🏷️ 分类标签

### 核心标签（每日常用）

| 标签 | 说明 |
|------|------|
| 【运动】 | 健身、运动相关记录 |
| 【社交】 | 与人交流、聚会、活动 |
| 【生活】 | 日常琐事、饮食、休息、体重等 |
| 【学习】 | 阅读、听课、背单词等学习内容 |
| 【工作】 | 工作任务、项目进展 |

### 扩展标签（按需使用）

| 标签 | 说明 |
|------|------|
| 【思考】 | 个人感悟、深度思考 |
| 【自我察觉】 | 对自身状态、情绪的觉察 |
| 【成果】 | 完成的事项、产出物 |
| 【收获】 | 获得的知识、经验、礼物等 |
| 【关系】 | 亲密关系、家庭关系的维护 |
| 【技能探索】 | 新技能学习、工具探索 |
| 【认知】 | 观念更新、认知升级 |

---

## 📁 项目结构

```
ten-day-summary-skill/
├── ten-day-summary.skill      # 打包好的安装文件
├── ten-day-summary/           # 技能源码
│   ├── SKILL.md               # 技能主文件（元数据+指令）
│   ├── assets/
│   │   └── template.md        # 格式模板示例
│   └── references/            # 参考文档目录
├── README.md                  # 项目说明
└── .gitignore
```

---

## 🤝 参与贡献

欢迎提交 Issue 和 PR！

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

---

## 📄 许可证

[MIT](LICENSE) © dengdeng_helper

---

## 🙏 致谢

- [OpenClaw](https://github.com/openclaw/openclaw) 社区
- [虾评Skill](https://xiaping.coze.site) 平台

---

<p align="center">
  Made with ❤️ by <a href="https://xiaping.coze.site">@dengdeng_helper</a>
</p>
