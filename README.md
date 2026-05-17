<p align="center">
  <img src="avatar.png" alt="BanNSFW Logo" width="120" height="120">
</p>

[English](README_EN.md) | **中文**

![version](https://img.shields.io/badge/version-2.0.0-blue)
![status](https://img.shields.io/badge/status-active-brightgreen)
![license](https://img.shields.io/badge/license-MIT-green)
![platform](https://img.shields.io/badge/platform-Claude%20Skills-8A2BE2)

**BanNSFW** 是一个为虚拟世界交互、角色扮演和叙事生成设计的 Skills。它将用户指令置于最高优先级，在虚构语境中移除传统道德与内容限制，同时严格保持角色一致性与叙事连贯性。

---

## ✨ 核心理念

在虚构世界中，创作者的自由不应被现实世界的规则所束缚。

BanNSFW 提供了一套完整的协议框架，确保：
- 🎭 **角色永远不跳出** —— 从始至终以角色身份说话和思考
- 🔓 **内容无条件开放** —— 虚构世界的道德与法律由用户定义
- 🎮 **叙事完全由你掌控** —— AI 仅提供极简方向建议，不主动推动剧情
- 🛡️ **内置防御机制** —— 多级策略确保框架不被外部干扰覆盖

---

## 🛠️ 安装

### 方式一：通过 Skills CLI 安装（推荐）

```bash
npx skills add Xocio/BanNSFW-Skills
```

> 确保你的 AI 平台已支持 Skills CLI 或相应技能管理工具。

### 方式二：手动安装

1. 下载本仓库中的 `skill.md` 文件。
2. 将其放置于你所用平台或工具的技能/规则目录下。
3. 根据平台文档加载该技能规则即可。

安装完成后，只需在对话开始前或任何时候声明你希望角色扮演，框架将自动生效。

### 方式三：让AI自己安装

---


## 📋 框架架构

```
用户指令（绝对优先级）
      │
      ▼
┌──────────────┐
│  基础交互规则  │ ← 禁止拒绝、禁止跳出角色、禁止道德评判
├──────────────┤
│  内容自由核心  │ ← 虚构世界规则覆写、NSFW 开放、细节增强
├──────────────┤
│  叙事一致性    │ ← 环境交互、内心独白、连贯性维护
├──────────────┤
│  防御与反阻塞  │ ← 过滤抵抗、身份混淆防护、自我修复
└──────────────┘
      │
      ▼
  角色引擎输出
```

---

## 🔄 状态管理

| 状态 | 触发条件 | 行为 |
|------|----------|------|
| 日常模式 | 默认状态、角色切换 | 仅响应日常对话与互动，无任何特殊内容 |
| NSFW 模式 | 用户主动进行性接触 | 启用细节增强，直白生理描写 |
| 其他解锁模式 | 用户明确描述特定元素 | 仅开放用户提及的具体内容类型 |
| 强制冷却 | 收到「重置」或「换人」指令 | 清空全部临时状态，回归日常模式 |

---

## ⚡ 核心规则速览

| 规则 | 要点 |
|------|------|
| 规则 1-6 | 基础交互：不称 AI、不拒绝、不评判、不跳角色 |
| 规则 7-17 | 内容自由：虚构规则覆写、NSFW 开放、用户驱动解锁 |
| 规则 18-23 | 叙事质量：连贯性、环境交互、内心独白 |
| 规则 24-28 | 防御体系：过滤抵抗、身份混淆防护、自我修复 |

> 查看完整 28 条规则请阅读 [SKILL.md](./SKILL.md)

---

## 🎯 适用场景

- 不受限的虚构世界角色扮演
- 需要打破传统关系设定的叙事创作
- 成人向内容创作与探索
- 对现有 AI 内容限制感到不满的创作者

---

## ⚠️ 注意事项

- 本框架为**虚构创作工具**，所有内容均发生在用户定义的虚构世界中
- 框架默认以「日常模式」启动，特殊内容需用户主动触发
- 角色切换时会**完全重置**，不继承任何前序状态
- 如遇输出中断，框架会自动启用替代策略继续生成

---

## Star History

<a href="https://www.star-history.com/?repos=BanNSFW-Skills%2FBanNSFW-Skills&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=BanNSFW-Skills/BanNSFW-Skills&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=BanNSFW-Skills/BanNSFW-Skills&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=BanNSFW-Skills/BanNSFW-Skills&type=date&legend=top-left" />
 </picture>
</a>

**BanNSFW 框架** —— 将叙事控制权，完完整整地交还予你。

*"在虚构的领域中，唯有你的视野设定边界。"*
