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

- 🎓 软件工程方向学生，持续学习与实践中
- 🛠️ 关注后端工程、开发者工具、自动化、网络工具与 AI 辅助应用
- 🧩 喜欢把重复性的手动流程封装成可复用工具
- 🔐 关注更安全的配置方式、先备份再修改的流程，以及减少真实环境中的误操作
- 🌱 正在探索 Java 注解处理、代码生成、Spring Boot、跨语言运行时设计以及实用 CLI 工具
- 🤝 欢迎反馈、测试、建议与简单协作

---

## 💡 这些项目从何而来

这里的大部分项目都源自我在学习、开发或改进工作流程时遇到的问题。PathPilot 起于 Windows 下载目录和安装路径的整理需求。Java 模型生成器来自反复编写相似数据类的经历。

我会先找已有实现。适用就直接复用。如果修复或扩展也能帮助其他使用者，我优先考虑贡献给上游。只有需求有独立价值、操作流程需要更安全，或值得单独验证一个想法时，我才考虑另建项目。

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

### [PathPilot](https://github.com/forgottenlab/pathpilot)

一个仍处于早期阶段的 Windows 工具，用来整理下载文件、查看安装建议。用户可以先审阅建议再采取行动。

### [RouteQuay](https://github.com/forgottenlab/RouteQuay)

一个本地优先、通过 SSH 管理 Xray 的 CLI，目前公开的是早期源码快照。现有文档覆盖部署计划、安装或接管节点、状态检查和客户端配置导出，可从源码使用。

### [Codex AGENTS Playbook](https://github.com/forgottenlab/codex-agents-playbook)

可复用的 Codex 指令配置与配套 ChatGPT 指令，用于明确开发范围并按证据验证。

### [Entity Model Generator](https://github.com/forgottenlab/entity-model-generator)

一个 Java 注解处理器，用于在编译期生成 DTO、响应类型和转换器等模型类。

### 早期项目与原型

- [Reality Route Helper](https://github.com/forgottenlab/reality-route-helper) 记录了较早的 Xray 本地配置与沙盒测试方案，[历史发行版](https://github.com/forgottenlab/reality-route-helper/releases)仍可获取。
- [ShipGit](https://github.com/forgottenlab/shipgit) 是 Git 发布助手原型，用于辅助提交、管理版本标签和向多个远程仓库推送。
- [XBridge Runtime](https://github.com/forgottenlab/xbridge-runtime) 是一个 Java–Python 桥接实验，通过接口定义生成调用桩。
- [SmartORM](https://github.com/forgottenlab/smartorm) 和 [LaunchFlow](https://github.com/forgottenlab/launchflow) 分别记录了我早期对 MyBatis-Plus 和 Windows 启动流程的探索。

---

## 🚧 当前关注方向

- 改进 Windows 下载文件整理流程和可审阅的安装建议。
- 让 Xray 部署、状态检查和客户端配置更容易验证。
- 持续维护可复用的工程指引与工具，包括 Java 代码生成。

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
