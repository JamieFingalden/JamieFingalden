# Hi, I'm Jamie Fingalden 👋

**全栈开发者 · macOS 原生应用 · AI 应用与工程工具**

已毕业，喜欢从自己的工作和生活中找问题，再把解决办法做成能用的软件。从业务系统、智能账单处理，到 Git 工作流、截图录屏、RSS 阅读和打印驱动，我关心的是：**它能不能把一件真实的事情做好。**

I'm a graduate and full-stack developer building native macOS apps, practical AI applications, and tools for everyday work.

[English](https://github.com/JamieFingalden/JamieFingalden/blob/main/README_en.md) · [中文](https://github.com/JamieFingalden/JamieFingalden/blob/main/README_zh.md) · [所有公开仓库](https://github.com/JamieFingalden?tab=repositories)

## 最近在做什么

近期的公开作品主要围绕 **macOS 原生体验和日常效率**，主要采用 **vibe coding（AI 辅助开发）** 的方式完成。我借助 AI 推进实现，把注意力放在需求、功能取舍、体验调整与结果验收上，让开发、阅读、记录和休息这些每天都会发生的事情更顺手。

同时，我也有全栈业务系统和 AI 应用的开发经历，关注从需求、界面、后端到交付的完整流程。

## 近期公开作品

### 🌳 [Grove](https://github.com/JamieFingalden/Grove) — 把 Git worktree 放在工作流中心

一个原生 macOS Git 客户端，将多个 worktree、代码改动和 GitHub PR / GitLab MR 放在同一个界面里。开发到一半收到审查任务时，可以检出独立的 worktree 处理，再回到原来的工作。

- 管理 worktree、查看差异、按行暂存、提交与推送。
- 浏览代码审查请求，处理 rebase 和合并冲突。
- 可选 AI 辅助生成，支持 Codex CLI 或兼容 API。

**Swift · SwiftUI · Git · GitHub / GitLab CLI** · [下载](https://github.com/JamieFingalden/Grove/releases/latest)

### ✂️ [轻截 LightSnap](https://github.com/JamieFingalden/LightSnap) — 从截图到演示录屏

面向 Apple Silicon 的原生 macOS 截图与录屏工具。截图后直接标注、复制或贴到桌面；需要展示操作过程时，可以录制屏幕、窗口或区域，再调整画面样式并导出。

- 智能选区、长截图、图形标注、可缩放的桌面贴图。
- 录制系统声音、麦克风与摄像头，支持暂停和继续。
- 录屏预览提供鼠标与点击效果、背景和画布调整，支持 MP4 / GIF 导出。

**Swift · AppKit · ScreenCaptureKit · 系统图形框架** · [下载预览版](https://github.com/JamieFingalden/LightSnap/releases)

### 💧 [Restly](https://github.com/JamieFingalden/Restly) — 认真工作，也记得休息

轻量的 macOS 菜单栏应用，把喝水、护眼、起身提醒和番茄钟放在一起。利用系统的锁屏、休眠等状态判断离开与返回，减少不合时宜的提醒。

- 喝水与起身浮窗提醒，全屏护眼倒计时。
- 可配置的专注与休息周期，支持暂停和状态恢复。
- 无需账号，设置保存在本地。

**Swift · macOS 原生框架** · [下载](https://github.com/JamieFingalden/Restly/releases/latest)

### 📰 [拾讯 Shixun](https://github.com/JamieFingalden/Shixun) — 一个安静的 RSS 阅读器

原生 macOS 三栏阅读界面，把订阅源、文章列表和正文放在一起。支持 RSS / Atom、搜索、收藏和离线缓存；阅读偏好保存在本机，帮助整理文章优先级，同时保留全部内容可见。

**Swift · SwiftUI · WebKit · 本地存储**

### 🖨️ [Apeos 2350 macOS 社区打印驱动](https://github.com/JamieFingalden/apeos2350-macos-driver)

为 FUJIFILM Apeos 2350 NDA 补上 Apple Silicon 下的打印能力。结合 macOS 的 PDF 渲染与 CUPS，将文档转换为打印机接受的 HBPL2 / JBIG 数据，通过网络发送。

**A4 单面、长边双面及正反面方向已实机验证。** 仓库包含协议分析、实现说明和验证记录；这是社区驱动，支持范围以项目文档为准。

**C · CUPS · HBPL2 / JBIG · 网络打印** · [下载与安装](https://github.com/JamieFingalden/apeos2350-macos-driver#下载与安装)

## 毕业设计与早期项目

这些仓库记录了我的全栈开发与 AI 应用实践，也保留着不同阶段的尝试。

### 🧾 [AstraFlow](https://github.com/JamieFingalden/AstraFlow) — 我的毕业设计：智能报销与账单管理

**AstraFlow 是我的毕业设计项目**，面向企业与个人财务场景。围绕票据上传、OCR 与 AI 信息提取、账单确认、财务审核和统计归档，探索如何让识别能力进入完整的业务流程。

采用 **Vue 3 + Go / Gin + Python**，通过 **RabbitMQ** 处理异步识别任务，结合 **MySQL** 与图表展示组织业务数据。仓库保留了应用代码、接口文档和设计资料。

| 项目 | 记录的实践 |
| --- | --- |
| [PocketFlow](https://github.com/JamieFingalden/PocketFlow) | Vue + Go / Gin 的个人记账实践，覆盖账户、账单与分类管理，并探索 OCR 接入。 |
| [myblog](https://github.com/JamieFingalden/myblog) | Spring Boot + Vue 的个人博客项目，围绕文章管理、内容展示与接口协作展开。 |
| [Spring-Template](https://github.com/JamieFingalden/Spring-Template) | Java / Spring Boot 项目起点，整合数据访问、身份认证与常见后端依赖。 |
| [Online_course_script](https://github.com/JamieFingalden/Online_course_script) | 早期 Python / Selenium 浏览器自动化实践，记录脚本交互与打包经验。 |

## 非公开项目经历

我也参与过一些非公开项目，这里只介绍应用方向与个人经历：

- **工程图纸审查与优化平台**：面向工程图纸审查，组织项目与专业信息，管理审查结果和优化建议。
- **图纸质量验证工具**：管理测试图纸与运行记录，对比不同版本的结果，辅助项目迭代和验收。
- **进销存与物流业务系统**：围绕销售、采购、仓储与物流管理，参与业务功能开发和团队协作。
- **无人机相关管理平台**：参与无人机业务管理系统的全栈开发。
- **在线口语测评平台**：参与面向语言学习的口语测评团队项目。
- **天气与穿着建议应用原型**：面向日常通勤，探索如何帮助用户根据天气选择穿着。

这些经历让我更关注需求是否清楚、前后端能否顺畅协作，以及功能能否在真实场景中交付。

## 项目涉及的技术

| 方向 | 技术 |
| --- | --- |
| 原生应用 | Swift、SwiftUI、AppKit、ScreenCaptureKit、WebKit |
| 前端 | Vue、JavaScript / TypeScript、Vite |
| 后端 | Java / Spring Boot、Go / Gin、Python / Flask |
| 数据与任务 | MySQL、Redis、RabbitMQ、OCR 与大模型应用集成 |
| 工程工具 | Git / worktree、Docker、GitHub Actions、uv、npm |
| 系统实践 | C、CUPS、打印协议与硬件适配 |

## 我的开发习惯

- **先理解问题，再写最少的代码。** 优先复用已有能力、标准库和平台原生功能。
- **修根因，也看相邻路径。** 一个共享逻辑的问题，尽量在共享位置解决。
- **让实现保持简单、可读、可验证。** 验证对准真正可能出错的地方。
- **把用户体验放进工程细节。** 关心窗口行为、快捷键、数据保存，也关心工具是否打断工作。

欢迎通过公开项目的 [Issues](https://github.com/JamieFingalden?tab=repositories) 交流问题和想法。
