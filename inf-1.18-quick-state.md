---
description: 创建日期：2022.12.24
---

# Inf 1.18 快速说明

我们的服务器已经升级到 1.18.2 版本，在此次更新后我们首次采用了官方服务端安装 Fabric 的服务端解决方案。

我们在服务端安装了 [Ledger](https://github.com/QuiltServerTools/Ledger) 来替代曾经 CoProtect 插件来记录方块的变化状态，并安装了 [Carpet Mod](https://github.com/gnembon/fabric-carpet) 以及 [Carpet TIS Addition](https://github.com/TISUnion/Carpet-TIS-Addition) 等 Mod 来优化玩家的游戏体验。

使用这些 Mod 我们可以开启诸多方便的辅助功能。目前我们在 Carpet Mod 以及 Carpet TIS Addition 中开启了以下功能：

* defaultLoggers:tps

这个功能将让你进入游戏后自动订阅 tps 展示。相关信息将在你的 Tab 栏列出。

* fakePlayerNamePrefix:bot_

这个功能将在所有由 Carpet Mod 生成的假人 ID 开头加上 "bot_" 前缀，用于方便的区分假人，同时防范违规使用 Carpet Mod 生成游戏内存在的玩家来避免线下玩家落入不安全的状态。

* fastRedstoneDust:true

这个功能可以在一定程度上优化红石粉带来的卡顿。

* flippinCactus:true

这个功能允许你使用仙人掌来简单调整部分方块的朝向或状态。

* lagFreeSpawning:true

这个功能可以在一定程度上优化生物生成带来的内存及 CPU 占用。

* optimizedFastEntityMovement:true

这个功能可以在实体运动时只计算运动的方向上的碰撞体积，可以在一定程度上减少卡顿。

* optimizedHardHitBoxEntitiesCollisions:true

这个功能可以优化实体碰撞体积计算。

* optimizedTNT:true

这个功能可以优化在同一落点或水中爆炸的多个 TNT 带来的卡顿。

* stackableShulkerBoxes:16

这个功能允许将潜影盒通过丢在地上的方式堆叠至 16 个。

* xpNoCooldown:true

这个功能去除了经验吸收冷却，极大程度上减轻了因为经验过多导致的卡顿。

值得注意的是，Carpet Mod 中存在可以很大程度上影响游戏行为的开关（如关闭重力方块通过末地传送门复制特性等），因此我们暂时不向全部玩家开放 Carpet Mod 的相关操作权限，如果有需要可以联系服务器管理员进行相关操作。