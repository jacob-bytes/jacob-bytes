<div align="center">

# Jacob Brown

Rust · TypeScript ｜ 自托管的运维工具：状态页、探针、内网工具

</div>

---

## 主题作品

给 [Komari Monitor](https://github.com/elevenhq/komari-monitor) 写的两套状态页主题（Vue + Tailwind），均为 MIT。它们是我目前最常被用到的作品：

| 项目 | 是什么 | |
|:--|:--|:--|
| **[komari-theme-ink](https://github.com/jacob-bytes/komari-theme-ink)** | shadcn 语言 · 深蓝黑 · 极简 · 明暗双主题 | ![stars](https://img.shields.io/github/stars/jacob-bytes/komari-theme-ink?style=flat-square&color=193cb8) |
| **[komari-theme-blueprint](https://github.com/jacob-bytes/komari-theme-blueprint)** | 「工程蓝图 · 运维图纸」——把机房与线路画成一张可读的图 | ![stars](https://img.shields.io/github/stars/jacob-bytes/komari-theme-blueprint?style=flat-square&color=193cb8) |

## 探针与工具

**[spot-probe](https://github.com/spot-probe)** —— **此前的项目**：一套 Rust 写的服务器探针。hub（axum + SQLite）＋ 每台机器一个 agent ＋ 公开状态页主题 ＋ 文档站。fork 自 [monitor-probe](https://github.com/monitor-probe) 之后独立演进：`main` 就是发布线，改动走分支经 PR 合入。

- 延迟监控支持 TCP 与 ICMP；保留期可调到 365 天（分钟明细折叠成小时汇总）
- 远程升级：agent 把发布公钥编进二进制，hub 经同一条已认证的 WebSocket 下发，验签通过才替换，失败回滚

**[localcraft](https://github.com/jacob-bytes/localcraft)** —— 内网工具 / Skill 共享平台：上传 → 审批 → 发布 → 下载。systemd 原生部署，x86_64 / aarch64 **离线安装**，适合没有外网的内网环境。
![stars](https://img.shields.io/github/stars/jacob-bytes/localcraft?style=flat-square&color=193cb8)

## 链接

- 探针项目（组织）：<https://github.com/spot-probe>
- 文档站：<https://spot-probe-docs.hualala.workers.dev/>

---

<div align="center">
<sub>本页是手写的；新仓库不会自动出现在这里。</sub>
</div>
