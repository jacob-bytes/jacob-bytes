<div align="center">

# Jacob Brown

Rust · TypeScript ｜ 服务器监控与运维面板

</div>

---

## 主题作品

给 Komari Monitor 写的两套主题，均为 MIT。

| 项目 | 说明 | |
|:--|:--|:--|
| **[komari-theme-ink](https://github.com/jacob-bytes/komari-theme-ink)** | shadcn 语言 · 深蓝黑 · 极简高级 · 双主题（黑 / 白） | ![stars](https://img.shields.io/github/stars/jacob-bytes/komari-theme-ink?style=flat-square&color=193cb8) ![language](https://img.shields.io/github/languages/top/jacob-bytes/komari-theme-ink?style=flat-square) |
| **[komari-theme-blueprint](https://github.com/jacob-bytes/komari-theme-blueprint)** | 给 Komari Monitor 的一套「工程蓝图 · 运维图纸」主题 | ![stars](https://img.shields.io/github/stars/jacob-bytes/komari-theme-blueprint?style=flat-square&color=193cb8) ![language](https://img.shields.io/github/languages/top/jacob-bytes/komari-theme-blueprint?style=flat-square) |

## 探针二次开发

fork 自 [**monitor-probe**](https://github.com/monitor-probe) —— Rust 写的轻量服务器探针：agent 经 WebSocket / JSON-RPC 2.0 上报，hub 用 axum + SQLite 收下并出图。

主要改动落在公开状态页主题上（浅色语义配色、分组页签、列表视图、图表调色板）。

| 项目 | 说明 | 语言 |
|:--|:--|:--|
| **[monitor](https://github.com/jacob-bytes/monitor)** | hub：后台、API、公开页宿主（axum + SQLite） | ![language](https://img.shields.io/github/languages/top/jacob-bytes/monitor?style=flat-square) |
| **[agent](https://github.com/jacob-bytes/agent)** | Linux 采集端 | ![language](https://img.shields.io/github/languages/top/jacob-bytes/agent?style=flat-square) |
| **[monitor-theme-default](https://github.com/jacob-bytes/monitor-theme-default)** | 公开状态页主题（Vite + React + TS） | ![language](https://img.shields.io/github/languages/top/jacob-bytes/monitor-theme-default?style=flat-square) |
| **[monitor-document](https://github.com/jacob-bytes/monitor-document)** | 探针文档（MDX） | ![language](https://img.shields.io/github/languages/top/jacob-bytes/monitor-document?style=flat-square) |

上游文档站：<https://monitor-document.pages.dev/>

> 语言徽章全部是**动态**的。GitHub 的 `language` 字段对 fork 返回 `null`（所以网页上那些 fork 不显示语言），但 shields.io 走的是 `/languages` 接口——**对 fork 同样有效**，实测 `monitor` 返回 `rust 70.8%`。用动态徽章就不必手工维护语言名，也不会随代码漂移。

---

<div align="center">
<sub>本页列表是手写的；新增仓库不会自动出现在这里。</sub>
</div>
