# Mishang Urban Construction

[简体中文](./README.md) · English

An urban-building mod with paintable or marked roads, signs, lights, handrails and construction tools. This port adapts client renderer registration for the 26.3 runtime.

## Download and installation

- Version · [v1.6.7-beta.3-rongmc.1+mc26.3](https://github.com/OpenRongMC/Mishang-Urban-Construction/releases/tag/v1.6.7-beta.3-rongmc.1%2Bmc26.3) (Prerelease)
- Release asset · `rongmc-mishanguc-1.6.7-beta.3-rongmc.1.mc26.3.jar`
- Runtime · Minecraft Java 26.3, Fabric, Java 25
- Fabric mod ID · `rongmc_mishanguc`
- Dependencies declared by the JAR · [Fabric API](https://modrinth.com/mod/fabric-api)

Place the release JAR in the instance’s `mods/` directory. Install the same build on both sides. Add the matching OcelotSign release for mainland Chinese traffic signs and posts. Beta builds can be found among the prereleases.

## How to try it

Lay a short road with markings at different orientations and edit a sign. Boot a dedicated server and check login and rendering of existing blocks.

## Working from source

```sh
./gradlew tasks
```

Inspect the tasks available in this checkout with Java 25 before selecting a build task.

## Documentation and support

- [Previous README (historical guide, contributors and credits)](https://github.com/OpenRongMC/Mishang-Urban-Construction/blob/3bdeedd07a9a60b60992678e4c419f666ca01d69/README-en.md)
- [Upstream project and documentation](https://github.com/SolidBlock-cn/mishanguc)
- [OcelotSign](https://github.com/OpenRongMC/OcelotSign)
- [Report a RongMC port issue](https://github.com/OpenRongMC/Mishang-Urban-Construction/issues) · Include the game version, client and server JAR names, reproduction steps and relevant logs.

## License and credits

See this repository’s [LICENSE](./LICENSE) and the original project’s license, credits and third-party asset notices.
