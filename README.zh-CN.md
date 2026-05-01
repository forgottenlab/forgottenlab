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

我的大多数项目并不是从空想开始的。

它们通常来自我在学习、开发或整理自己工作流时真实遇到的问题。在自己动手实现之前，我通常也会先尝试已有工具和常见解决方案。但在某些场景下，它们可能不够灵活、不够顺手，或者无法很好地适配我自己的使用方式。

于是，我开始自己研究这些问题，并围绕真实需求构建一些小工具。

举例来说：

- 当我需要把项目发布到多个 Git 远程仓库时，重复编写 Git 命令、管理版本 Tag、保持发布流程一致会变得很繁琐。  
  于是我开始构建 [`shipgit`](https://github.com/forgottenlab/shipgit)，一个轻量级 Git 发布助手。

- 当 Windows 下载目录和安装包逐渐变得混乱时，我希望有一个工具可以帮助整理文件，并引导软件安装到更合适的位置。  
  于是有了 [`pathpilot`](https://github.com/forgottenlab/pathpilot)。

- 当我经常需要在开始某项任务前同时打开多个软件、网页和命令时，我开始思考能不能做一个可视化的启动流程编排工具。  
  于是有了 [`launchflow`](https://github.com/forgottenlab/launchflow)。

- 当我在 Java 后端项目中反复编写 DTO、Response、Converter 等结构相似的代码时，我开始尝试用编译期代码生成来减少重复劳动。  
  于是有了 [`entity-model-generator`](https://github.com/forgottenlab/entity-model-generator)。

- 当我使用 MyBatis-Plus 时，希望能用更清晰的方式处理常见 CRUD、分页、关联查询和轻量级 SQL 执行。  
  于是有了 [`smartorm`](https://github.com/forgottenlab/smartorm)。

- 当我思考 Java 程序如何更简单、更结构化地调用 Python 能力时，我开始尝试构建 [`xbridge-runtime`](https://github.com/forgottenlab/xbridge-runtime) 这样的跨语言运行时原型。

- 当我搭建个人网络路线时，发现很多教程比较分散：有些命令属于服务端，有些属于客户端，而很小的配置错误也可能导致整个流程失败。  
  于是有了 [`reality-route-helper`](https://github.com/forgottenlab/reality-route-helper)，一个面向 Xray / VLESS + Reality 的双语、跨平台感知路线助手，并计划扩展到 Outline、Hysteria2、TUIC、sing-box 等方案。

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

### [`reality-route-helper`](https://github.com/forgottenlab/reality-route-helper)

一个双语、跨平台感知的网络连接路线助手，用于选择、生成、测试和管理不同网络连接方案。

当前第一版重点实现 Xray / VLESS + Reality，并提供环境扫描、安全配置生成、沙盒测试、菜单流测试，同时计划扩展 Outline、Hysteria2、TUIC、sing-box 与面板类方案。

**关键词：** Python、CLI Tool、Xray、VLESS、Reality、网络工具、自动化、安全测试

---

### [`entity-model-generator`](https://github.com/forgottenlab/entity-model-generator)

一个基于 Java APT 注解处理器的模型生成工具。

它的目标是在编译期自动生成常见的 DTO、Response、Converter 等模型代码，从而减少重复开发，提高项目结构的可维护性。

**关键词：** Java、Annotation Processing、Code Generation、APT、开发者工具

---

### [`smartorm`](https://github.com/forgottenlab/smartorm)

一个基于注解驱动的 MyBatis-Plus 增强工具。

它主要用于简化 CRUD、分页、关联查询与轻量级原生 SQL 执行，让 MyBatis-Plus 的使用体验更清晰、更工程化。

**关键词：** Java、Spring Boot、MyBatis-Plus、ORM、后端工具

---

### [`xbridge-runtime`](https://github.com/forgottenlab/xbridge-runtime)

一个跨语言运行时原型项目。

它尝试通过接口定义描述跨语言能力，并自动生成桥接代码，让 Java 调用 Python 能力变得更加简单。

**关键词：** Java、Python、代码生成、运行时、跨语言桥接

---

### [`shipgit`](https://github.com/forgottenlab/shipgit)

一个轻量级 Git 发布助手。

它用于辅助完成更安全的提交、版本 Tag 管理，以及多远程仓库发布流程。

**关键词：** Python、Git、CLI 工具、自动化

---

### [`launchflow`](https://github.com/forgottenlab/launchflow)

一个面向 Windows 的可视化启动流程编排工具。

它可以让用户可视化配置应用、网页、命令的启动顺序，并将流程打包成简单可执行的启动工具。

**关键词：** Python、Windows 工具、GUI、工作流自动化

---

### [`pathpilot`](https://github.com/forgottenlab/pathpilot)

一个 Windows 下载与安装路径治理助手。

它可以监听下载目录，自动整理文件，并建议将软件安装到系统盘以外的更合适位置。

**关键词：** Python、Windows 自动化、文件管理、桌面工具

---

## 🚧 当前关注方向

我目前主要关注：

- Java 注解处理器与编译期代码生成
- Spring Boot 后端开发与 MyBatis-Plus 增强
- 实用 CLI 工具与工作流自动化
- 安全配置生成与沙盒测试
- 跨语言运行时实验
- AI 辅助软件系统

---

## 📊 GitHub 数据

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=forgottenlab&show_icons=true&theme=github_dark&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=forgottenlab&layout=compact&theme=github_dark&hide_border=true)

---

## 📫 联系方式

- GitHub: [@forgottenlab](https://github.com/forgottenlab)
- Email: wangheran55@gmail.com

---

> 微小的脚步也许会被遗忘，但它们依然推动我们向前。
