# Hi, I'm forgottenlab 👋

[English](README.md) | [简体中文](README.zh-CN.md)

> A small lab for overlooked problems, practical tools, and experiments that may become useful someday.

I'm a software engineering student who is still learning, building, and experimenting.

I enjoy creating small but practical tools that come from real problems: reducing repetitive work, improving development workflows, making software easier to use, and turning complex setup processes into safer, more understandable steps.

I know many of my projects are still young and imperfect. They are not meant to replace mature tools, but to explore better ways to solve specific problems and to keep improving through real use.

---

## 🌱 About the Name

The name **forgottenlab** comes from a simple thought:

Sometimes small people also want to make the world a little better through technology.  
Maybe we cannot leave very deep footprints, and maybe many small contributions will eventually be forgotten.  
But that does not make the effort meaningless, and it does not stop us from continuing forward.

**forgottenlab** is a small lab for those quiet attempts: building, testing, learning, failing, improving, and trying again.

---

## 🧭 About Me

- 🎓 Software engineering student, continuously learning and building
- 🛠️ Interested in backend engineering, developer tools, automation, network tooling, and AI-assisted applications
- 🧩 I like turning repeated manual workflows into reusable tools
- 🔐 I care about safer configuration, backup-first workflows, and reducing mistakes in real environments
- 🌱 Currently exploring Java annotation processing, code generation, Spring Boot, cross-language runtime ideas, and practical CLI tools
- 🤝 Open to feedback, testing, suggestions, and simple collaboration

---

## 💡 How These Projects Started

Most of my projects did not start from abstract ideas.

They usually came from real problems I encountered while learning, developing, or managing my own workflow. Before building my own tools, I usually tried existing tools and common solutions first. But in some scenarios, they were not flexible enough, not smooth enough, or did not fully match the way I wanted to work.

So I started to study these problems myself and build small tools around real needs.

For example:

- When publishing a project to multiple Git remotes, writing repeated Git commands, managing version tags, and keeping the release process consistent can become tedious.  
  This led me to build [`shipgit`](https://github.com/forgottenlab/shipgit), a lightweight Git publishing assistant.

- When downloaded files and installers gradually made my Windows environment messy, I wanted a tool that could help organize files and guide installation paths more safely.  
  This became [`pathpilot`](https://github.com/forgottenlab/pathpilot).

- When I often needed to open several apps, websites, and commands together before starting a task, I began to think about a visual workflow launcher for Windows.  
  This became [`launchflow`](https://github.com/forgottenlab/launchflow).

- When working with Java backend projects, I noticed that DTO, Response, and Converter code often involved a lot of repetitive structure.  
  This inspired [`entity-model-generator`](https://github.com/forgottenlab/entity-model-generator), a Java APT-based model generation tool.

- When using MyBatis-Plus, I wanted a cleaner way to handle common CRUD, pagination, join queries, and lightweight SQL execution.  
  This became [`smartorm`](https://github.com/forgottenlab/smartorm).

- When thinking about how Java programs could call Python capabilities in a simpler and more structured way, I started experimenting with [`xbridge-runtime`](https://github.com/forgottenlab/xbridge-runtime).

- When setting up personal network routes, I found that many tutorials were fragmented: some commands were server-side, some were client-side, and small configuration mistakes could break the whole setup.  
  This led to [`reality-route-helper`](https://github.com/forgottenlab/reality-route-helper), a bilingual, platform-aware route helper for Xray / VLESS + Reality and future routes such as Outline, Hysteria2, TUIC, and sing-box.

---

## 🤝 Why Feedback Matters

Most of these tools are still in early stages.

They may work well in my own environment, but one person's workflow is always limited. Real users, real operating systems, real project structures, and real edge cases can reveal problems that I may never notice by myself.

So if any project interests you, you are welcome to try it, test it, open issues, suggest improvements, or simply share your usage experience.

I do not expect every project to be perfect from the beginning.  
But I hope they can keep improving through real use, real feedback, and continuous iteration.

---

## 🛠️ Tech Stack

### Languages

![Java](https://img.shields.io/badge/Java-orange?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-blue?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

### Backend & Frameworks

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MyBatis Plus](https://img.shields.io/badge/MyBatis--Plus-red?style=flat-square)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

### Tools & Platforms

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 📌 Featured Projects

### [`reality-route-helper`](https://github.com/forgottenlab/reality-route-helper)

A bilingual, platform-aware route helper for choosing, generating, testing, and managing network connection routes.

The first implemented route is Xray / VLESS + Reality. It also includes environment scanning, safe config generation, sandbox tests, menu flow tests, and future expansion plans for Outline, Hysteria2, TUIC, sing-box, and panel-based solutions.

**Keywords:** Python, CLI Tool, Xray, VLESS, Reality, Network Tooling, Automation, Safe Testing

---

### [`entity-model-generator`](https://github.com/forgottenlab/entity-model-generator)

A Java APT-based model generation tool.

It aims to reduce repetitive DTO / Response / Converter code by generating common model classes during compilation.

**Keywords:** Java, Annotation Processing, Code Generation, APT, Developer Tooling

---

### [`smartorm`](https://github.com/forgottenlab/smartorm)

An annotation-driven enhancement toolkit for MyBatis-Plus.

It focuses on cleaner CRUD, pagination, join queries, and lightweight native SQL execution while keeping the development experience simple.

**Keywords:** Java, Spring Boot, MyBatis-Plus, ORM, Backend Tooling

---

### [`xbridge-runtime`](https://github.com/forgottenlab/xbridge-runtime)

A prototype cross-language runtime.

The goal is to describe cross-language capabilities through interface definitions, generate bridge code, and make Java-to-Python invocation easier.

**Keywords:** Java, Python, Code Generation, Runtime, Cross-language Bridge

---

### [`shipgit`](https://github.com/forgottenlab/shipgit)

A lightweight Git publishing assistant.

It helps with safer commits, version tags, and multi-remote repository publishing.

**Keywords:** Python, Git, CLI Tool, Automation

---

### [`launchflow`](https://github.com/forgottenlab/launchflow)

A visual launch workflow builder for Windows.

It allows users to define launch sequences for apps, URLs, and commands, then package them into a simple executable workflow.

**Keywords:** Python, Windows Tool, GUI, Workflow Automation

---

### [`pathpilot`](https://github.com/forgottenlab/pathpilot)

A Windows download and installation path governance assistant.

It watches download folders, organizes files, and suggests safer installation locations outside the system drive.

**Keywords:** Python, Windows Automation, File Management, Desktop Tool

---

## 🚧 Current Focus

I'm currently focusing on:

- Java annotation processing and compile-time code generation
- Spring Boot backend development and MyBatis-Plus enhancement
- Practical CLI tools and workflow automation
- Safe configuration generation and sandbox testing
- Cross-language runtime experiments
- AI-assisted software systems

---

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=forgottenlab&show_icons=true&theme=github_dark&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=forgottenlab&layout=compact&theme=github_dark&hide_border=true)

---

## 📫 Contact

- GitHub: [@forgottenlab](https://github.com/forgottenlab)
- Email: wangheran55@gmail.com

---

> Small steps may be forgotten, but they still move us forward.
