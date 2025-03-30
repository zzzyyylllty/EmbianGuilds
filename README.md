# EmbianGuilds

**项目使用 TabooLib Start Jar 创建**

<div align="center">

[ENGLISH README HERE](README-EN.md)

EmbianGuilds 是一个在 Minecraft Bukkit 平台下运行的公会插件。

旨在 Taboolib 的架构下的服务器中方便，简单地利用配置文件和 Kether 创建玩家公会。

基于 <a href = "https://tabooproject.org">Taboolib 6.x</a> 和 Kotlin.

这个项目的名字来源于：
<div style="text-align: center;">游戏 <a href = "https://needystreameroverload.wiki.gg/wiki/">主播女孩重度依赖</a> 中的海波隆CP (Embian)</div><br>
</div>

## 服务

EmbianGuilds 是免费的，但我们不提供开发版本的构建文件。

你可通过自行构建获取开发版本，或是在 Release 下载稳定版本。

## TODO
- [ ] 基本公会功能
  ...

## 友链
- [TabooLib 非官方文档](https://taboolib.feishu.cn/)
- [精神支柱](https://needystreameroverload.wiki.gg/wiki/Ame-chan)

## 贡献者

<a href="https://github.com/zzzyyylllty/EmbianGuilds/graphs/contributors">
  <img src="https://stg.contrib.rocks/image?repo=zzzyyylllty/EmbianGuilds" />
</a>

## 构建发行版本

发行版本用于正常使用, 不含 TabooLib 本体。

```
./gradlew clean build
```

## 构建开发版本

开发版本包含 TabooLib 本体, 用于开发者使用, 但不可运行。

```
./gradlew clean taboolibBuildApi -PDeleteCode
```

> 参数 -PDeleteCode 表示移除所有逻辑代码以减少体积。