<p align="center">
  <img src="https://docs.gov.skin/favicon.png" width="96" alt="Mythicove" />
</p>

<h1 align="center">Mythicove</h1>

<p align="center">
  一套面向 <b>皮肤站 / 私服 / Mod 站</b> 的开源 Minecraft 生态套件<br />
  <sub><a href="./README.md">English</a> · <a href="https://docs.gov.skin">文档</a> · <a href="https://www.gov.skin">官网</a></sub>
</p>

---

## 产品

| | 项目 | 说明 |
|---|---|---|
| 🪞 | [Mythic Mirror](https://github.com/Mythicove/mythic-mirror) | 皮肤站 —— 基于 Yggdrasil API 的自定义登录 + 皮肤/披风，兼容 authlib-injector |
| 📦 | [Mythic Hoard](https://github.com/Mythicove/mythic-hoard) | Mod 托管 —— 兼容 Modrinth API 的模组 / 整合包分发开源平台 |
| 🧭 | [Mythic Compass](https://github.com/Mythicove/compass) | 启动器 —— Yggdrasil 登录 + 3D 皮肤预览 + 一键安装整合包 |
| 🖥️ | [web](https://github.com/Mythicove/web) | 统一前端 —— 皮肤站 / Mod 站 / 混合站三种部署形态 |

## 基础设施

| 仓库 | 说明 |
|---|---|
| [api](https://github.com/Mythicove/api) | 生态统一 OpenAPI 契约（单一事实源，生成 Go server 与 TS client） |
| [shared](https://github.com/Mythicove/shared) | 共享 Go 模块：auth / storage / search / cache / ratelimit / queue / mailer |
| [docs](https://github.com/Mythicove/docs) | 统一文档站源码：产品计划、ADR、部署运维 → [docs.gov.skin](https://docs.gov.skin) |

## 设计原则

- **源码可得** —— 产品采用 Elastic License 2.0（ELv2），API 契约 MIT，文档 CC BY-SA 4.0
- **协议兼容** —— 拥抱 Yggdrasil、Modrinth API、`.mrpack` 等既有标准，不做封闭生态
- **现代技术栈** —— Go 后端 + TypeScript 前端，部署运维友好
- **弹性伸缩** —— 从 1 人私服到 10k 人平台，同一套代码按需扩展

📖 文档：[docs.gov.skin](https://docs.gov.skin) · 🌐 官网：[gov.skin](https://www.gov.skin)
