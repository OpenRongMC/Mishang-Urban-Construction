# 迷上城建

简体中文 · [English](./README-en.md)

用于城市与道路建设的方块模组，提供可着色或带标线的道路、告示牌、灯饰、栏杆和辅助建造工具。此移植调整了 26.3 运行时的客户端渲染注册。

## 下载与安装

- 版本 · [v1.6.7-beta.3-rongmc.1+mc26.3](https://github.com/OpenRongMC/Mishang-Urban-Construction/releases/tag/v1.6.7-beta.3-rongmc.1%2Bmc26.3) (预发布)
- 下载文件 · `rongmc-mishanguc-1.6.7-beta.3-rongmc.1.mc26.3.jar`
- 运行环境 · Minecraft Java 26.3, Fabric, Java 25
- Fabric 模组 ID · `rongmc_mishanguc`
- JAR 声明的依赖 · [Fabric API](https://modrinth.com/mod/fabric-api)

把发行 JAR 放入对应实例的 `mods/` 目录。联机两端装同一版。需要中国大陆交通标识、路牌立杆时，再添加匹配的 OcelotSign。Releases 中的 beta 版本请查看预发布条目。

## 如何验证

在新世界放一段道路和几块不同朝向的标线，放置并编辑告示牌，然后用专用服确认能启动、进服及显示原有方块。

## 从源码开始

```sh
./gradlew tasks
```

先用 Java 25 检查当前源码树提供的任务，再选择对应的构建任务。

## 文档与反馈

- [原 README（旧版指南、贡献者与署名）](https://github.com/OpenRongMC/Mishang-Urban-Construction/blob/3bdeedd07a9a60b60992678e4c419f666ca01d69/README.md)
- [上游项目与文档](https://github.com/SolidBlock-cn/mishanguc)
- [豹猫指示牌（OcelotSign）](https://github.com/OpenRongMC/OcelotSign)
- [报告 RongMC 移植问题](https://github.com/OpenRongMC/Mishang-Urban-Construction/issues) · 请附游戏版本、两端 JAR 文件名、复现步骤和相关日志。

## 许可与署名

请参阅本仓库的 [LICENSE](./LICENSE) 及原项目的许可、署名和第三方资源说明。
