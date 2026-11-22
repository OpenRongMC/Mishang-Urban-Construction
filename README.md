# 迷上城建模组

Users using English may read [the English version](README-en.md).

迷上城建（Mishang Urban Construction）是一个建筑与装饰类的模组，提供了一系列有用的方块，例如：

- 道路方块：可以设置标线以显得真实。道路标线有各种组合，并且在部分情况下可以自动生成。
- 道路标记：可以在道路上放置简单的导向箭头等路面标记，可以放在道路台阶上。
- 灯：具有各种形状，有白色、黄色、橙色、青色、绿色、粉色，有完整的灯方块，也有可以放在墙上、地上、天花板上的装饰物。
- 告示牌：可以显示文本，有多种样式，且与原版的告示牌相比，本模组的告示牌的文字可以灵活地调节颜色、大小、位置等参数。支持使用 `/mishanguc:signpreset` 命令管理告示牌预设。
- 栏杆方块：可以有多种纹理、外观和连接方式，并且可以放置在楼梯上。
- 自定义颜色的方块：任意指定一个颜色，而非像混凝土和羊毛那样只有16种颜色。

此外，本模组还提供了一系列实用工具，可用于放置与调试，例如：

- 快速建造工具：快速地放置一个平面上的多个方块。
- 柱建造工具：快速地放置一个柱上的多个方块。
- 强制放置工具：放置方块时忽略放置限制和方块更新。
- 瞬移工具：随心所欲地传送至任意一个地方。
- ID检查工具、方块状态工具、数据标签工具：查看某个方块、实体的属性和NBT或查询当前生物群系。
- 爆炸工具：点击即可产生爆炸。
- 旋转工具和镜像工具：点击方块即可将其旋转或翻转。
- 颜色工具：随意地获取和修改方块的颜色，仅支持部分支持自定义染色的方块。
- 文本工具：复制和粘贴告示牌的文本（包括原版告示牌）。
- 生长工具：使生物和作物生长或反向生长，副手持金蒲公英还可使生物冻龄或解除冻龄（26.1 版本以上）。
- 搬运工具：将方块或实体拾起并搬运至另一个地方。
- 道路工具：快速地添加或清除道路上的标线。
- ……

本模组的详细内容请参见 [GitHub](https://github.com/SolidBlock-cn/mishanguc/wiki) 或 [MC模组百科](https://www.mcmod.cn/class/5743.html)。

本模组**依赖 Fabric API**。自模组版本 1.4.0 开始，**不再**依赖[更好的运行时资源包](https://github.com/SolidBlock-cn/BRRP)（Better Runtime Resource Pack）模组。

请参见[更新记录](UpdateLog.md)。

本模组只有 Fabric 版本，没有 Forge 或 NeoForge 版本。

本模组是按照 LGPLv3 协议发布的，传播本模组时须遵守本协议。

欢迎加入QQ群 **587928350** 进行交流。如遇问题，可在 GitHub 中报告。

---

# Mishang Urban Construction

中文用户可阅读[中文版](README.md)。

Mishang Urban Construction is a building and decoration mod that provides a variety of useful blocks, including:

- Road blocks: lines can be painted on them to make them look realistic. The road lines have various combinations and can be generated automatically in some situations.
- Road marks: simple road markings, such as guide arrows; can be placed on roads and road slabs.
- Lights: available in various shapes and colors, including white, yellow, orange, cyan, green, and pink. There are full light blocks as well as decorations that can be placed on walls, floors, or ceilings.
- Sign blocks: available in different styles. Compared with vanilla signs, signs in this mod allow parameters such as color, size, and position to be adjusted flexibly. Sign presets can be managed via the `/mishanguc:signpreset` command.
- Handrail blocks: available with various textures, appearances, and connection methods, and can be placed on stairs.
- Custom-colored blocks: allow any color to be specified instead of being limited to the 16 colors available for concrete and wool.

Moreover, the mod contains a series of useful tools, such as:

- Fast Building Tool: quickly places multiple blocks on a plane.
- Column Building Tool: quickly places multiple blocks in a column.
- Force Placing Tool: places blocks while ignoring placement restrictions and block updates.
- Teleportation Tool: teleports you to any location.
- ID Checking Tool, Block State Tool, and Data Tag Tool: query the properties or NBT of a block or entity, or query the current biome.
- Explosion Tool: creates an explosion when clicked.
- Rotating or Mirroring Tool: rotates or flips a block when clicked.
- Color Tool: obtains and modifies block colors; only some blocks support custom coloring.
- Text Copy Tool: copies and pastes text on signs, including vanilla signs.
- Growth Tool: makes creatures and crops grow or regress. When holding a golden dandelion in the offhand, it can also freeze or unfreeze a creature's age (version 26.1 and above).
- Carrying Tool: picks up a block or entity and carries it to another location.
- Road Tool: quickly adds or removes road markings.
- ……

For detailed information about this mod, see [GitHub](https://github.com/SolidBlock-cn/mishanguc/wiki) or [MC模组百科](https://www.mcmod.cn/class/5743.html).

This mod **depends on Fabric API** and, since version 1.4.0, **no longer** depends on the [BRRP](https://github.com/SolidBlock-cn/BRRP) (Better Runtime Resource Pack) mod.

Only a Fabric version is available; there is no Forge or NeoForge version of this mod.

Please also refer to [the update log](UpdateLog-en.md).

This mod is published under the LGPLv3 license, which you must follow when propagating this mod.

You are welcome to join the Tencent QQ group **587928350** for discussion. You can also report issues on GitHub.

---

## RongMC · Minecraft 26.3 Fabric 移植说明

本仓库是 RongMC 维护的 **Minecraft 26.3 / Fabric / Java 25** 移植构建，不是上游官方发行渠道。

### 与原版的主要差异
- Minecraft 26.3 Fabric 移植；Fabric id `rongmc_mishanguc`（provides `mishanguc`）。
- 资源命名空间仍为 `mishanguc`。上游为 LGPLv3；本发布仓附加 GPL-3.0 `LICENSE` 文本，使用时请同时遵守上游 LGPL 义务。

### 已知问题 / 限制
- 纯服务端加载时，针对客户端 GUI/渲染器的 Mixin 会报警（找不到客户端类），一般不影响进服。
- 与 Extended Block Shapes 联动的部分标线/台阶逻辑依赖对方模组是否加载。
- 自定义染色与部分工具在超大建造场景可能带来额外卡顿（上游同类）。

### 构建与安装
- Fabric mod id：`rongmc_mishanguc`（`provides`：`mishanguc`，旧依赖名一般仍可解析）
- Release 产物见本仓库 Releases（jar 名带 `rongmc-` 前缀）
- 许可证：本仓以 **GPL-3.0** 发布（见 `LICENSE`）；请同时尊重上游原作者条款与署名

