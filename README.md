# Give Me More Salary — 涨薪参谋

> Not a summary of "how others got raises" — a full evidence chain designed to convince your boss to pay you more.
>
> 不是帮你总结"别人怎么涨薪"，而是帮你生成一份可以说服老板掏钱的证据链。

---

## What is this

An AI-powered salary negotiation preparation tool. It automatically:

- 📊 **Market research** — Analyzes salary ranges for your role and city
- 💎 **Value modeling** — Transforms your project experience into quantifiable business impact
- 💬 **3-stage script generation** — WeChat opener → face-to-face pitch → objection handling
- 🚨 **Forbidden moves checklist** — 8 universal red flags + personalized warnings based on your situation
- 🎭 **Negotiation simulator** — AI plays your manager so you can practice the real conversation

## Quick Start

1. Open `index.html` in any browser
2. Enter your DeepSeek API Key (get one at [platform.deepseek.com](https://platform.deepseek.com))
3. Fill in your role, city, and project achievements in the **Info** tab
4. Click **Generate My Battle Pack**
5. Review your value doc in **My Value Doc**, then rehearse in **Negotiation Simulator**

## Tab Guide

**Tab 1 — Info Input**
Fill in basic info and click generate. The supplement chat box lets you add context anytime. All fields are auto-saved locally — you'll be prompted to restore them next time you open the page.

**Tab 2 — My Value Document**
After generation, displays structured cards: market salary comparison, core project achievements, extra responsibilities taken on, skill upgrades, pitch scripts, and action checklist.

**Tab 3 — Forbidden Moves**
8 universal negotiation pitfalls + AI-generated personalized warnings based on your specific situation.

**Tab 4 — Negotiation Simulator**
Choose difficulty (Normal / Hard Mode 🔥), start the simulation, and practice your pitch against an AI manager who pushes back like a real boss.

## Claude Code Skill

Trigger with `/give-me-more-salary` in Claude Code.

Keywords: 涨薪、谈薪、加薪、薪资谈判、salary negotiation、raise

## File Structure

```
GiveMeMoreSalary/
├── SKILL.md                    # Claude Code skill definition
├── index.html                  # Single-file web UI (open directly in browser)
├── salary-negotiation-plan.md  # Example output for reference
├── conductor.json              # Skill metadata
├── VERSION                     # Version number
└── README.md                   # This file
```

## Notes

- API Key is stored only in browser localStorage — never sent to any third-party server
- Market salary data is estimated by AI from training data — treat as reference only, verify on job platforms
- All scripts are based on your real situation — do not fabricate numbers

## Changelog

### v1.0.0
- Initial release
- Four modules: Info Input, Value Document, Forbidden Moves, Negotiation Simulator
- DeepSeek API integration
- Local form memory with restore prompt

---

## 这是什么

一个专为职场人设计的涨薪准备工具，结合 AI 自动完成：

- 📊 **市场薪资调研** — 自动分析同岗位、同城市的市场薪资区间
- 💎 **个人价值建模** — 把你的项目经历转化为可量化的业务价值
- 💬 **三段式话术生成** — 微信约老板 → 当面展示脚本 → 反驳应对
- 🚨 **禁忌清单** — 8 条通用雷区 + 针对你的个性化提醒
- 🎭 **沟通模拟器** — AI 扮演领导，让你提前练习真实对话

## 快速开始

1. 用浏览器打开 `index.html`
2. 填入 DeepSeek API Key（在 [platform.deepseek.com](https://platform.deepseek.com) 申请）
3. 在「信息填写」Tab 填写你的岗位、城市、项目成果
4. 点击「生成我的涨薪作战包」
5. 在「我的价值文档」查看分区结果，在「沟通模拟器」反复练习

## 使用说明

### Tab 1 — 信息填写
填写基本信息后点击生成。底部的「补充输入」支持随时追加，信息会自动保存到本地，下次打开会提示是否填入。

### Tab 2 — 我的价值文档
生成完成后展示分区卡片：市场薪资对比、核心项目成果、额外承担职责、能力提升、话术脚本、行动清单。

### Tab 3 — 禁忌清单
8 条通用禁忌 + 生成后追加的个性化提醒。

### Tab 4 — 沟通模拟器
选择难度（普通/难搞），开始模拟，AI 扮演你的领导进行真实对话练习。

## Skill 使用（Claude Code）

在 Claude Code 中使用 `/give-me-more-salary` 触发完整的涨薪参谋流程。

触发词：涨薪、谈薪、加薪、薪资谈判、salary negotiation、raise

## 文件结构

```
GiveMeMoreSalary/
├── SKILL.md                    # Claude Code skill 定义
├── index.html                  # 网页前端（单文件，直接用浏览器打开）
├── salary-negotiation-plan.md  # 示例输出参考
├── conductor.json              # skill 元信息
├── VERSION                     # 版本号
└── README.md                   # 本文件
```

## 注意事项

- API Key 仅保存在浏览器本地 localStorage，不经过任何服务器
- 市场薪资数据由 AI 基于训练数据估算，仅供参考，以实际招聘平台为准
- 所有话术基于你提供的真实情况包装，不建议捏造数字

## 版本历史

### v1.0.0
- 初始版本
- 四大模块：信息填写、价值文档、禁忌清单、沟通模拟器
- DeepSeek API 接入
- 本地表单记忆功能
