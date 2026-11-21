# 你好，我是 forgottenlab 👋

[English](README.md) | [简体中文](README.zh-CN.md)

> 一个用于记录真实问题、实践工具与技术实验的小小实验室。

我是一名仍在不断学习和实践中的软件工程学生。

我喜欢构建一些小而实用的工具，它们通常来自真实问题：减少重复劳动、改善开发流程、让软件使用起来更简单，并把复杂的配置过程变得更安全、更容易理解。

我知道自己的很多项目还很年轻，也并不完美。它们并不是为了替代成熟工具，而是希望在具体场景中探索更顺手的解决方式，并在真实使用中不断改进。

---

## 🌱 关于这个名字

**forgottenlab** 这个名字来自一个很简单的想法：

有时候，小人物也会想通过技术让世界变好一点。  
也许我们踩不出很深的脚印，也许很多微小的贡献最终会被遗忘。  
但这并不影响这些行动本身的意义，也不影响我们继续向前。

所以，**forgottenlab** 更像是一个小小的实验室：在这里不断构建、测试、学习、失败、改进，然后再次出发。

---

## 🧭 关于我

- 🎓 软件工程方向学生，在动手实践中持续学习
- 🛠️ 主要关注 Java 后端工程、框架设计、编译时代码生成、Spring Boot 生态和 Spring AI 集成
- 🧩 也实践 Windows 自动化、网络管理和 CLI 工具，并探索 AI 辅助开发流程
- 🔐 重视安全默认值、可审阅的改动，以及通过真实反馈验证和改进
- 🤝 欢迎反馈、测试报告和上游协作

---

## 💡 这些项目从何而来

我从学习和开发中反复遇到的问题出发。Java 项目关注重复的模型代码、常见的数据访问模式，以及 AI 应用如何组织业务上下文。Windows 和基础设施工具来自日常工作流程，希望让操作步骤更清晰、结果更容易验证。

我会先找已有方案。能帮助其他使用者的修复或扩展，优先考虑贡献给上游。只有解决独立需求时才考虑另建项目，再通过测试和反馈持续改进。

---

## 🤝 为什么需要反馈

这些工具大多仍处于早期阶段。

它们也许在我自己的环境中可以正常工作，但一个人的使用场景始终是有限的。真实用户、真实系统环境、真实项目结构和真实边界情况，往往能暴露出我一个人很难发现的问题。

如果你对我的某个项目感兴趣，欢迎尝试使用、参与测试、提交 Issue、提出建议，或者只是分享你的真实使用体验。

我并不期待每个项目从一开始就是完美的。  
但我希望它们能够在真实使用、真实反馈和持续迭代中慢慢变得更好。

---

## 🛠️ 技术栈

### 编程语言

![Java](https://img.shields.io/badge/Java-orange?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-blue?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

### 后端与框架

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MyBatis Plus](https://img.shields.io/badge/MyBatis--Plus-red?style=flat-square)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

### 工具与平台

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 📌 代表项目

### Java · 后端与 AI 工程

#### [Entity Model Generator](https://github.com/forgottenlab/entity-model-generator)

基于 Java APT 在编译期生成 DTO、响应类型、转换器和分组单表 View，减少重复的模型代码。GitHub 已发布 `v1.2.2`，采用 Apache-2.0 许可证，可从源码构建并安装到本地 Maven 仓库。

#### [SmartORM](https://github.com/forgottenlab/smartorm)

为 Spring Boot 和 MyBatis-Plus 提供按需启用的注解驱动 CRUD、分页、固定 JOIN 和参数化 SQL。Spring Boot Starter 为可本地安装的 `2.1.0-SNAPSHOT`，采用 Apache-2.0 许可证。

#### [AI Context Orchestrator](https://github.com/forgottenlab/spring-ai-context-orchestrator)

为 Spring AI 应用规划和加载业务上下文、处理冲突、按预算筛选内容，并将结果注入提示词。支持 Spring Boot 集成，提供离线示例，Starter 已通过模拟聊天模型验证。源码采用 Apache-2.0 许可证。

### Windows · 桌面与自动化

#### [PathPilot](https://github.com/forgottenlab/pathpilot)

整理 Windows 下载文件，并提供可以先审阅、再决定是否采纳的安装建议。GitHub 发行版 `v0.2.2` 是用于评估的 Alpha 原型，采用 MIT 许可证。

#### [LaunchFlow](https://github.com/forgottenlab/launchflow)

在 Windows 上可视化编排应用、网页、命令和等待步骤，将方案保存为 JSON 并导出启动器。GitHub 预发布版 `v0.1.0-beta.2` 处于 Beta 阶段，采用离线授权，保留所有权利。

### 基础设施 · 开发工具

#### [RouteQuay](https://github.com/forgottenlab/RouteQuay)

本地优先的 CLI，支持规划 Xray 部署、通过 SSH 安装或接管节点、检查状态及导出客户端配置。目前提供 MIT 许可的早期源码快照，尚未发布版本化安装器或 GitHub Release。

#### [Codex AGENTS Playbook](https://github.com/forgottenlab/codex-agents-playbook)

提供可复用的 Codex 指令配置和配套 ChatGPT 指令，用于明确协作范围、保护私有输入并验证执行结果。这是采用 MIT 许可证的独立社区项目。

---

## 🚧 当前关注方向

- Java 后端工程、可复用框架和编译期模型生成。
- Spring Boot 集成，以及可验证的 Spring AI 业务上下文编排。
- 可审阅的 Windows 自动化、可核查的网络操作，以及实用的 CLI 与 AI 辅助开发流程。

---

## 📘 工程实践

我维护一份轻量级双语工程手册，用于日常维护和协作。我会先找可复用的工作，尽量把通用修复贡献给上游，并根据实际反馈改进已有项目。值得保留的实验会注明范围和限制，方便后来回看。

[ForgottenLab Engineering Standards](https://github.com/forgottenlab/.github) · [English Handbook](https://github.com/forgottenlab/.github/blob/main/docs/standards/README.md) · [中文工程手册](https://github.com/forgottenlab/.github/blob/main/docs/standards/README.zh-CN.md)

---

## 📊 GitHub 数据

![GitHub Stats](https://github-stats-extended.vercel.app/api?username=forgottenlab&show_icons=true&theme=github_dark&hide_border=true)

![Top Languages](https://github-stats-extended.vercel.app/api/top-langs/?username=forgottenlab&layout=compact&theme=github_dark&hide_border=true)

---

## 📫 联系方式

- GitHub: [@forgottenlab](https://github.com/forgottenlab)
- Email: wangheran55@gmail.com

---

> 微小的脚步也许会被遗忘，但它们依然推动我们向前。
