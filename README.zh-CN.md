# Probe-Prove-Persuade

> **Probe · Prove · Persuade** — 基于 Randy Olson《Houston, We Have a Narrative》的科学文本叙事润色工具

[English](README.md) | [中文](README.zh-CN.md)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Language: EN/ZH](https://img.shields.io/badge/Language-EN%2FZH-blue.svg)](#)
[![Skill Type: AI Agent](https://img.shields.io/badge/Type-AI%20Agent%20Skill-purple.svg)](#)
[![Method: WSP Model](https://img.shields.io/badge/Method-WSP%20Model-teal.svg)](#)

将好莱坞叙事技法系统性地应用于科学写作，通过 **WSP 模型**（Word-Sentence-Paragraph）在三个层级重构论文叙事结构，让科研写作从"实验记录簿"变成"引人入胜的故事"。

**名字由来** —— 三个P开头的动词排比，既是科学传播的经典三步，也映射skill的核心工作流：

```
Probe     诊断叙事光谱，发现文本的AAA病灶
   │
   ▼
Prove     用WSP模型工具重构论证逻辑
   │
   ▼
Persuade  交付让读者信服的润色文本
```

---

## 目录

- [背景与动机](#背景与动机)
- [核心方法论：WSP 模型](#核心方法论wsp-模型)
- [三阶段工作流](#三阶段工作流)
- [安装与使用](#安装与使用)
- [示例](#示例)
- [IMRAD 分区指南](#imrad-分区指南)
- [反模式与常见错误](#反模式与常见错误)
- [文件结构](#文件结构)
- [致谢与引用](#致谢与引用)
- [许可协议](#许可协议)

---

## 背景与动机

科学写作的最大问题不是数据不足，而是**叙事结构的缺失**。

大多数论文遵循 **AAA 模式**（And-And-And）：事实的平铺罗列，没有张力，没有方向，没有转折。读者无法识别研究空白，无法感受"为什么这项研究重要"。

Randy Olson——一位从海洋生物学终身教授转型为好莱坞电影人的跨界学者——在 *Houston, We Have a Narrative: Why Science Needs Story* 一书中提出：

> **科学是一个叙事过程。叙事就是讲故事。因此，科学需要讲故事。**

本 skill 将书中的核心方法论系统化为可操作的润色工具。

### 理论渊源

| 来源 | 贡献 |
|------|------|
| Aristotle（亚里士多德） | 三幕结构：开端—中段—结尾 |
| Hegel（黑格尔） | 辩证法：正题—反题—合题 |
| Joseph Campbell | 英雄之旅（单体神话） |
| Christopher Vogler | 将英雄之旅改编为编剧实用工具 |
| Theodosius Dobzhansky | "Nothing in biology makes sense except in the light of evolution" |
| Randy Olson | ABT 模板形式化、WSP 模型、叙事光谱 |

---

## 核心方法论：WSP 模型

WSP 模型在三个层级运作，每个层级对应一种叙事工具：

```
WSP Model
  │
  ├── W (Word)        ──►  Dobzhansky Template     ──►  主题锚定
  │                                                    在词汇/短语层面工作
  │
  ├── S (Sentence)    ──►  ABT Template             ──►  逻辑重构
  │                                                    在单句层面工作
  │
  └── P (Paragraph)   ──►  Hero's Journey /         ──►  弧线构建
                           Story Spine                    在多段落层面工作
```

**核心原则**：三层必须按顺序应用。主题（词层）不清晰时无法修复句子问题；句子缺乏 ABT 结构时无法构建段落弧线。

### 层级一：Dobzhansky 模板（词层 — 主题锚定）

```
English:
"Nothing in [research domain] makes sense except in the light of [key concept]."

Chinese:
"如果不从 [关键概念] 的角度思考问题，[研究领域] 的一切都毫无道理。"
```

**作用**：锁定全文核心主题，减少"无目的的信息堆砌"，确保每一段都服务于锚定主题。

### 层级二：ABT 模板（句层 — 逻辑重构）

```
[Agreement/facts], AND [more context],
BUT [contradiction/problem/gap],
THEREFORE [conclusion/action].
```

```
______而且______，但是______，因此______。
```

**三种变体**，适配不同受众：

| 变体 | 名称 | 长度 | 适用场景 |
|------|------|------|----------|
| cABT | Concise（精简版） | 1 个短句 | 电梯演讲、公众演讲、新闻稿 |
| kABT | Keeper（成品版） | 2-4 句 | 会议摘要、论文摘要、基金摘要 |
| iABT | In-depth（深度版） | 完整段落 | 引言部分、详细技术提案 |

### 层级三：Story Spine / 英雄之旅（段层 — 弧线构建）

```
In an ordinary world, [背景]...
A flawed protagonist [研究问题]...
Encountered a catastrophic event [关键挑战/空白]...
Which upended their world, but after assessment, [认知]...
The protagonist decided to act, [方法]...
But with raised stakes, [困难]...
The protagonist had to learn a lesson, [发现]...
To confront the antagonist, [验证]...
And achieve the goal, [贡献]...
```

**高低原则**（Christopher Keane）：好故事只保留最高潮和最低谷，删掉中间无用的过渡。

---

## 三阶段工作流

```
┌─────────────────────────────────────────────────────────┐
│                    输入：待润色文本                        │
└─────────────────────────┬───────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────┐
│  PROBE: 诊断 — 叙事光谱评估                               │
│  逐段标记 AAA / ABT / 混合，定位需要重构的段落             │
│  填写 Dobzhansky 模板，锚定全文核心主题                    │
└─────────────────────────┬───────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────┐
│  PROVE: 论证 — WSP 模型重构                               │
│  词层：Dobzhansky 模板检查主题一致性                       │
│  句层：ABT 模板重构关键句子的逻辑骨架                      │
│  段层：Story Spine 构建多段落叙事弧线                     │
└─────────────────────────┬───────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────┐
│  PERSUADE: 说服 — 验证与交付                              │
│  朗读测试、电梯测试、"But"真实性检查                      │
│  输出润色后文本 + 诊断报告 + 修改日志                     │
└─────────────────────────┬───────────────────────────────┘
                          ▼
┌─────────────────────────────────────────────────────────┐
│                    输出：润色后文本                        │
└─────────────────────────────────────────────────────────┘
```

---

## 安装与使用

### 作为 AI Agent Skill 使用

将本仓库的 `SKILL.md`、`REFERENCE.md`、`EXAMPLES.md` 复制到你的 AI Agent 技能目录中。以 DuMate / OpenCode 类 agent 为例：

```bash
# 复制到技能安装目录
cp SKILL.md REFERENCE.md EXAMPLES.md /path/to/skills/user/probe-prove-persuade/
```

安装后，在对话中直接描述润色需求即可触发：

```
User: 帮我润色这段摘要
User: 检查这段引言的叙事结构
User: 用ABT模板重构这段讨论
User: 这段文字是不是AAA结构
User: 帮我写一个cABT电梯演讲
User: 用杜布赞斯基模板锚定论文主题
```

### 作为独立参考文档使用

即使不使用 AI Agent，这三个文件本身就是完整的叙事写作方法论手册：

| 文件 | 内容 | 用途 |
|------|------|------|
| [SKILL.md](SKILL.md) | 主指令：三阶段工作流 + WSP 概览 | 快速查阅工作流 |
| [REFERENCE.md](REFERENCE.md) | 方法论详解：全书 11 章理论体系 | 深入理解理论背景 |
| [EXAMPLES.md](EXAMPLES.md) | 8 个完整润色前后对比 + 速查表 | 实践参考 |

---

## 示例

### 润色前（AAA — 平铺直叙）

> We study multi-energy systems. We model electricity, heat, and gas networks. We use reinforcement learning. We train agents with PPO. We evaluate on benchmark datasets. We compare with baseline methods. We achieve 15% cost reduction. We conclude that our method is effective.

**诊断**：AAA 重度。无研究空白，无张力，无"But"。读者无法判断这项工作为什么重要。

### 润色后（ABT — 有张有合）

> Multi-energy systems integrate electricity, heat, and gas networks, **AND** reinforcement learning has shown promise for their coordinated optimization. **BUT** existing approaches assume homogeneous agent capabilities, failing to capture the structural heterogeneity of real-world energy components. **THEREFORE**, we propose a heterogeneous graph reinforcement learning framework that explicitly models component diversity, achieving 15% cost reduction over state-of-the-art baselines.

> 更多示例见 [EXAMPLES.md](EXAMPLES.md)。

---

## IMRAD 分区指南

| IMRAD 部分 | 叙事工具 | 目标 |
|------------|----------|------|
| **I**ntroduction | ABT + Story Spine + Dobzhansky | 建立空白，制造张力，激发研究动机 |
| **M**ethods | 最少叙事；聚焦清晰度 | 准确、可复现的描述 |
| **R**esults | 最少叙事；聚焦清晰度 | 呈现发现，不加粉饰 |
| **A**nd **D**iscussion | ABT + Dobzhansky | 解读发现，回扣主题 |

---

## 反模式与常见错误

| 反模式 | 症状 | 修复 |
|--------|------|------|
| **AAA 罗列** | "We did A. We did B. We did C. We found D." | 找到"But"——什么是意外的？什么空白存在？ |
| **虚假 ABT** | 制造数据中不存在的冲突 | 如无真实"But"，研究可能是描述性的——不要强行套叙事弧 |
| **过度戏剧化** | 把方法部分写成惊悚片 | Methods/Results 保持事实性，叙事工具只用于 I 和 D |
| **主题漂移** | 每段讨论不同话题，无统一线索 | 重新应用 Dobzhansky 模板，每段必须服务锚定主题 |
| **忽视受众** | 对公众演讲和专家论文使用相同 ABT 密度 | 根据受众选择 cABT / kABT / iABT |

---

## 文件结构

```
probe-prove-persuade/
├── README.md              # 项目主页（英文版）
├── README.zh-CN.md        # 本文件 — 中文版项目主页
├── LICENSE                # MIT 许可协议
├── .gitignore             # Git 忽略规则
├── CONTRIBUTING.md        # 贡献指南（英文版）
├── CONTRIBUTING.zh-CN.md  # 中文版贡献指南
├── SKILL.md               # 主指令：三阶段工作流 + WSP 概览
├── REFERENCE.md           # 方法论详解：全书 11 章理论体系
└── EXAMPLES.md            # 8 个润色前后对比 + 速查表
```

---

## 致谢与引用

### 原著

```
Olson, Randy. Houston, We Have a Narrative: Why Science Needs Story.
Chicago: University of Chicago Press, 2015. ISBN: 978-0-226-27098-6
```

### 中文译本

```
兰迪·奥尔森. 科学需要讲故事. 高爽 译. 重庆: 重庆大学出版社, 2018.
ISBN: 978-7-5689-0920-4
```

### 核心理论来源

- **Dobzhansky 模板**：源自 Theodosius Dobzhansky 1973 年经典论文标题
- **ABT 模板**：Olson 于 2011 年形式化，根源可追溯至亚里士多德三幕结构和黑格尔辩证法
- **Story Spine**：由 Dolly Barton（Olson 工作坊合作者）开发
- **英雄之旅**：Joseph Campbell《千面英雄》(1949)，Christopher Vogler 改编为编剧工具

---

## 许可协议

本项目基于 [MIT License](LICENSE) 开源。

书中方法论内容版权归 Randy Olson 及 respective publishers 所有。本项目是对书中方法的二次提炼和工具化实现，仅供学习和研究使用。
