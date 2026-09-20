# Goety + Revelation EMC Values for ProjectE

Minecraft 1.20.1（Forge 47.4.21） **诡厄巫法（Goety）** 与 **诡厄巫法：启示录（Goety: Revelation）** 的 [ProjectE（等价交换重制版）](https://www.curseforge.com/minecraft/mc-mods/projecte) EMC 值配置。

## 版本信息

| 项目 | 内容 |
|------|------|
| 游戏版本 | Minecraft 1.20.1（Forge 47.4.21） |
| 诡厄巫法版本 | goety-2.5.57.3 |
| 启示录版本 | GoetyRevelation-2.3.3fix（内嵌 RevelationFix 4.4） |
| ProjectE 版本 | PE1.0.1 |
| 总条目 | **1,426 条** |
| Goety 本体 | 1,323 条 |
| Goety: Revelation | 80 条 |
| 其他模组修正 | 23 条 |

## v1.1.0 更新内容

- 新增 **Goety: Revelation 80 条 EMC**：
  - 76 个物品/方块物品
  - 4 个 `mystery_fragment{fragment:0~3}` NBT 变体
- 关键物品按 **红物质 466,944 EMC 的 10 倍（4,669,440）** 作为最低档位。
- 终局/核心物品示例：
  - 天启七印、终末之环、维度意志：46,694,400
  - 恶意、天启长弓、冈格尼尔、末影守望者：18,677,760
  - 末日勋章、破碎之环、命运之矛头：9,338,880
  - 神灵金属锭、晋升之环、寂灭之星：4,669,440
  - 神灵金装备四件：9,338,880 / 件

## 文件说明

| 文件 | 说明 |
|------|------|
| `custom_emc.json` | 完整 EMC 配置，包含 Goety 本体 + 启示录 + 其他模组修正，共 1,426 条 |
| `goety_emc_only.json` | 仅 Goety 本体条目，供只使用本体或做合并的用户参考 |
| `revelation_emc_only.json` | 仅 Goety: Revelation 条目，共 80 条 |

## 使用方法

1. 下载 `custom_emc.json`。
2. 放入 Minecraft 实例目录：
   ```text
   .minecraft/config/ProjectE/custom_emc.json
   ```
3. 进入游戏后执行 `/projecte reload`，或直接重启客户端。
4. 在 Transmutation Table 中即可看到新增 EMC。

## 注意

- 本配置主要面向 **ProjectE PE1.0.1**。
- 数值偏 **高价值/长线平衡**，不是低配速通数值。
- 如果某些物品价格不符合你的整合包平衡，欢迎提交 Issue。
- `blessing_scroll` 等依赖可选模组的内容未纳入当前 80 条注册物品统计。
