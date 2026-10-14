# Hi, I'm Jamie Fingalden 👋

**Full-stack developer · Native macOS apps · Practical AI & developer tools**

I've graduated and enjoy turning problems from everyday work and life into useful software. My projects range from business systems and intelligent bill processing to Git workflows, screen capture, RSS reading, and printer drivers. I care about whether a tool does its job well in a real setting.

[English](https://github.com/JamieFingalden/JamieFingalden/blob/main/README_en.md) · [中文](https://github.com/JamieFingalden/JamieFingalden/blob/main/README_zh.md) · [Public repositories](https://github.com/JamieFingalden?tab=repositories)

## Recent focus

My recent public projects focus on **native macOS experiences and everyday productivity**, and are built primarily through **vibe coding (AI-assisted development)**. I use AI to help implement them while focusing on requirements, feature choices, user experience, and checking the results. The goal is to make development, reading, capturing information, and taking breaks a little easier.

I also have experience with full-stack business systems and AI applications, working across requirements, interfaces, backend services, and delivery.

## Recent public projects

### 🌳 [Grove](https://github.com/JamieFingalden/Grove) — Git worktrees at the center of the workflow

A native macOS Git client that brings worktrees, local changes, GitHub pull requests, and GitLab merge requests together. When a review arrives mid-feature, check it out in a separate worktree, handle it, and return to your original work.

- Worktree management, diffs, line-level staging, commits, and pushes.
- Code review requests, rebase workflows, and conflict resolution.
- Optional AI assistance through Codex CLI or a compatible API.

**Swift · SwiftUI · Git · GitHub / GitLab CLI** · [Download](https://github.com/JamieFingalden/Grove/releases/latest)

### ✂️ [LightSnap / 轻截](https://github.com/JamieFingalden/LightSnap) — Screenshots and presentation recordings

A native macOS capture tool for Apple Silicon. Annotate, copy, or pin screenshots to the desktop; record a screen, window, or region, then adjust its presentation and export it.

- Smart selection, scrolling screenshots, annotations, and zoomable pinned images.
- System audio, microphone, and camera recording with pause and resume.
- Recording previews with cursor and click effects, backgrounds, canvas settings, and MP4 / GIF export.

**Swift · AppKit · ScreenCaptureKit · System graphics frameworks** · [Preview downloads](https://github.com/JamieFingalden/LightSnap/releases)

### 💧 [Restly](https://github.com/JamieFingalden/Restly) — Focus, hydrate, and take a break

A lightweight macOS menu bar app with water, eye-rest, and stand-up reminders, plus a pomodoro timer. It uses system states such as screen locking and sleep to handle absence and return.

- Floating water and stand reminders, with a full-screen eye-rest countdown.
- Configurable focus and break cycles, pause controls, and state restoration.
- No account required; settings stay local.

**Swift · Native macOS frameworks** · [Download](https://github.com/JamieFingalden/Restly/releases/latest)

### 📰 [Shixun / 拾讯](https://github.com/JamieFingalden/Shixun) — A quiet RSS reader

A native three-column macOS reader for feeds, articles, and content. It supports RSS / Atom, search, bookmarks, and offline caching. Reading preferences stay on the device and help prioritize articles while keeping all content accessible.

**Swift · SwiftUI · WebKit · Local storage**

### 🖨️ [Apeos 2350 macOS community printer driver](https://github.com/JamieFingalden/apeos2350-macos-driver)

Apple Silicon printing support for the FUJIFILM Apeos 2350 NDA. It combines macOS PDF rendering and CUPS to produce HBPL2 / JBIG data and send it to the printer over the network.

**A4 simplex, long-edge duplex, and front/back orientation have been verified on real hardware.** The repository includes protocol analysis, implementation notes, and validation records. This is a community driver; see its documentation for the supported scope.

**C · CUPS · HBPL2 / JBIG · Network printing** · [Installation](https://github.com/JamieFingalden/apeos2350-macos-driver#下载与安装)

## Graduation project and earlier work

These repositories document my full-stack and AI application work at earlier stages.

### 🧾 [AstraFlow](https://github.com/JamieFingalden/AstraFlow) — My graduation project: intelligent reimbursement and bill management

**AstraFlow is my graduation project**, built for business and personal finance scenarios. It explores how receipt uploads, OCR and AI extraction, bill confirmation, financial review, and reporting fit into a complete business workflow.

Built with **Vue 3, Go / Gin, and Python**, using **RabbitMQ** for asynchronous recognition tasks and **MySQL** with charts for business data. The repository preserves application code, API documentation, and design material.

| Project | What it explores |
| --- | --- |
| [PocketFlow](https://github.com/JamieFingalden/PocketFlow) | Personal bookkeeping with Vue and Go / Gin: accounts, bills, categories, and OCR integration experiments. |
| [myblog](https://github.com/JamieFingalden/myblog) | A Spring Boot + Vue blog project covering article management, content presentation, and API collaboration. |
| [Spring-Template](https://github.com/JamieFingalden/Spring-Template) | A Java / Spring Boot starting point with data access, authentication, and common backend dependencies. |
| [Online_course_script](https://github.com/JamieFingalden/Online_course_script) | Early Python / Selenium browser automation work, including script interaction and packaging. |

## Non-public project experience

I have also worked on projects that remain private. At a high level, these cover:

- **Engineering drawing review and optimization:** organizing projects and disciplines, review results, and optimization suggestions.
- **Drawing quality validation tools:** managing test drawings and run records, comparing results across versions, and supporting iteration and acceptance checks.
- **Inventory and logistics systems:** business features and team collaboration around sales, purchasing, warehousing, and logistics management.
- **Drone-related management platforms:** full-stack development for drone business management.
- **Online speech evaluation:** a team project for language learning and speaking assessment.
- **Weather and outfit advice prototype:** exploring how to help commuters choose clothing based on the weather.

These experiences shaped my attention to clear requirements, frontend/backend collaboration, and delivering features for real use.

## Technologies used in my projects

| Area | Technologies |
| --- | --- |
| Native apps | Swift, SwiftUI, AppKit, ScreenCaptureKit, WebKit |
| Frontend | Vue, JavaScript / TypeScript, Vite |
| Backend | Java / Spring Boot, Go / Gin, Python / Flask |
| Data and tasks | MySQL, Redis, RabbitMQ, OCR and LLM application integration |
| Development tools | Git / worktrees, Docker, GitHub Actions, uv, npm |
| Systems work | C, CUPS, printing protocols, hardware adaptation |

## How I build

- **Understand the problem, then write the minimum code.** Reuse existing capabilities, standard libraries, and native platform features.
- **Fix root causes and check neighboring paths.** Solve shared problems where the logic is shared.
- **Keep implementations simple, readable, and verifiable.** Focus checks on meaningful failure modes.
- **Treat user experience as an engineering concern.** Window behavior, shortcuts, data persistence, and interruptions all matter.

Questions and ideas are welcome through the issue trackers of my [public projects](https://github.com/JamieFingalden?tab=repositories).
