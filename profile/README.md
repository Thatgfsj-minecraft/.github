# Thatgfsj-minecraft

Minecraft 模组开发组织 —— 所有 Minecraft 模组项目都放在这里。
Minecraft mod development organization — every mod project by [@Thatgfsj](https://github.com/Thatgfsj) lives here.

## 项目 / Projects

| 仓库 | 简介 |
|---|---|
| [sky-islands](https://github.com/Thatgfsj-minecraft/sky-islands) | Sky Islands 空岛世界：创建新世界时可选的内置空岛类型（经典/小岛/单方块），生物群系正常、种子照常。 |
| [handy-shulkers](https://github.com/Thatgfsj-minecraft/handy-shulkers) | "拿着就用" 我管你这那的 |
| [compressed-blocks](https://github.com/Thatgfsj-minecraft/compressed-blocks) | 压缩方块 Compressed Blocks：把常见方块 3×3 压成 1~9 重方便携带；压缩工具耐久 9ⁿ 指数上升（六重起不可破坏）、挖掘速度与伤害逐重成长。 |
| [mc-mod-dev-skill](https://github.com/Thatgfsj-minecraft/mc-mod-dev-skill) | Minecraft 模组开发技能包（自用AI agent skill） |

## 技术栈 / Stack

- 加载器 Loaders：Fabric、NeoForge
- 版本 Versions：1.21.1、1.21.11（双版本同步维护）
- 映射 Mappings：Mojmap（官方映射）
- 语言与构建 Java & Build：Java 21、Gradle（每个子项目独立 Gradle 构建）
- 测试 Testing：专用服务器（离线模式）+ mineflayer 机器人 + RCON 服务端权威断言
- 开发技能 Skill：[mc-mod-dev-skill](https://github.com/Thatgfsj-minecraft/mc-mod-dev-skill) —— AI agent 可直接加载的模组开发技能包：Phase 0 环境侦察、不凭记忆猜 API、专用服务器 E2E 验证；已沉淀 1.7.10–1.21.11 共 18 个版本的版本卡与 Fabric ↔ NeoForge 差异经验

## 许可 / License

本组织所有仓库均基于 [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html)（GNU 通用公共许可证第 3 版）开源发布，以各仓库根目录的 LICENSE 文件为准：你可以自由地使用、学习、修改和分发这些项目，但基于它们修改或二次开发的作品必须同样以 GPL-3.0 协议开源，并保留相应的版权与许可声明。

All repositories in this organization are released under the [GNU General Public License v3.0 (GPL-3.0)](https://www.gnu.org/licenses/gpl-3.0.html), as defined by the LICENSE file at the root of each repository.
