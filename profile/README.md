<p align="center">
  <img src="https://docs.gov.skin/favicon.png" width="96" alt="Mythicove" />
</p>

<h1 align="center">Mythicove</h1>

<p align="center">
  A source-available Minecraft ecosystem for <b>skin sites, private servers and mod communities</b><br />
  <sub><a href="./README.zh-CN.md">简体中文</a> · <a href="https://docs.gov.skin">Docs</a> · <a href="https://www.gov.skin">Website</a></sub>
</p>

---

## Products

| | Project | Description |
|---|---|---|
| 🪞 | [Mythic Mirror](https://github.com/Mythicove/mythic-mirror) | Skin site — custom Yggdrasil-based authentication + skin/cape hosting, authlib-injector compatible |
| 📦 | [Mythic Hoard](https://github.com/Mythicove/mythic-hoard) | Mod hosting — open mod/modpack distribution platform, Modrinth-API compatible |
| 🧭 | [Mythic Compass](https://github.com/Mythicove/mythic-compass) | Launcher — Yggdrasil login + 3D skin preview + one-click modpack install |
| 🖥️ | [web](https://github.com/Mythicove/web) | Unified frontend — deployable as a skin site, a mod site, or a hybrid |

## Infrastructure

| Repository | Description |
|---|---|
| [api](https://github.com/Mythicove/api) | Unified OpenAPI contract for the ecosystem (single source of truth, generates Go server & TS client) |
| [shared](https://github.com/Mythicove/shared) | Shared Go modules: auth / storage / search / cache / ratelimit / queue / mailer |
| [docs](https://github.com/Mythicove/docs) | Unified documentation site source: product plans, ADRs, deploy & ops → [docs.gov.skin](https://docs.gov.skin) |

## Design principles

- **Source-available** — products under Elastic License 2.0 (ELv2), API contracts MIT, docs CC BY-SA 4.0; self-hosting is free even for monetized communities, see the [licensing policy](https://docs.gov.skin/en/community/licensing/)
- **Protocol-compatible** — embracing existing standards (Yggdrasil, Modrinth API, `.mrpack`), no walled garden
- **Modern stack** — Go backend + TypeScript frontend, deployment- and ops-friendly
- **Elastic scale** — from a 1-player private server to a 10k-user platform, same codebase

📖 Documentation: [docs.gov.skin](https://docs.gov.skin) · 🌐 Website: [gov.skin](https://www.gov.skin)
