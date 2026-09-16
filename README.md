<div align="center">

# Jacob Brown

Rust · TypeScript ｜ 服务器监控与运维面板

</div>

---

## 当前在做什么

**[monitor-probe](https://github.com/monitor-probe) 二次开发** —— 给这套 Rust 探针重做公开状态页主题。四个仓库现已集中在 [**spot-probe**](https://github.com/spot-probe) 组织下。

- **主题改造**：浅色语义配色（明暗两套，全部过 WCAG AA）、分组页签、筛选与列表视图、图表调色板重建、卡片与详情页重构 —— 已发布 [v1.3.0](https://github.com/spot-probe/monitor-theme-default/releases/tag/v1.3.0)
- **工程化**：hub 已切到自己发布的主题版本，CI/CD 与发布流水线打通，3 个仓库产出 release 产物
- **顺手修的缺陷**：`install-hub.sh` 在 macOS 自带 bash 3.2 下会崩 —— 变量名紧跟中文全角标点时被解析错，导致**正常卸载路径直接中止**；已改为 `${var}` 显式界定

## 主题作品

给 Komari Monitor 写的两套主题，均为 MIT。

| 项目 | 说明 | |
|:--|:--|:--|
| **[komari-theme-ink](https://github.com/jacob-bytes/komari-theme-ink)** | shadcn 语言 · 深蓝黑 · 极简高级 · 双主题（黑 / 白） | ![stars](https://img.shields.io/github/stars/jacob-bytes/komari-theme-ink?style=flat-square&color=193cb8) ![language](https://img.shields.io/github/languages/top/jacob-bytes/komari-theme-ink?style=flat-square) |
| **[komari-theme-blueprint](https://github.com/jacob-bytes/komari-theme-blueprint)** | 给 Komari Monitor 的一套「工程蓝图 · 运维图纸」主题 | ![stars](https://img.shields.io/github/stars/jacob-bytes/komari-theme-blueprint?style=flat-square&color=193cb8) ![language](https://img.shields.io/github/languages/top/jacob-bytes/komari-theme-blueprint?style=flat-square) |

## 探针二次开发

fork 自 [**monitor-probe**](https://github.com/monitor-probe) —— Rust 写的轻量服务器探针：agent 经 WebSocket / JSON-RPC 2.0 上报，hub 用 axum + SQLite 收下并出图。

四个仓库集中在 [**spot-probe**](https://github.com/spot-probe)：`main` 保持上游镜像以便持续跟进上游的修复与新特性，自己的改动走分支。

| 项目 | 说明 | 语言 |
|:--|:--|:--|
| **[monitor](https://github.com/spot-probe/monitor)** | hub：后台、API、公开页宿主（axum + SQLite） | ![language](https://img.shields.io/github/languages/top/spot-probe/monitor?style=flat-square) |
| **[agent](https://github.com/spot-probe/agent)** | Linux 采集端 | ![language](https://img.shields.io/github/languages/top/spot-probe/agent?style=flat-square) |
| **[monitor-theme-default](https://github.com/spot-probe/monitor-theme-default)** | 公开状态页主题（Vite + React + TS） | ![language](https://img.shields.io/github/languages/top/spot-probe/monitor-theme-default?style=flat-square) |
| **[monitor-document](https://github.com/spot-probe/monitor-document)** | 探针文档（MDX） | ![language](https://img.shields.io/github/languages/top/spot-probe/monitor-document?style=flat-square) |

上游文档站：<https://monitor-document.pages.dev/>

> 语言徽章全部是**动态**的。GitHub 的 `language` 字段对 fork 返回 `null`（所以网页上那些 fork 不显示语言），但 shields.io 走的是 `/languages` 接口——**对 fork 同样有效**。用动态徽章就不必手工维护语言名，也不会随代码漂移。

---

<div align="center">
<sub>本页列表是手写的；新增仓库不会自动出现在这里。</sub>
</div>
