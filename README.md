# Goety + Revelation + Cataclysm EMC Values for ProjectE

Minecraft 1.20.1（Forge 47.4.21） **诡厄巫法（Goety）**、**诡厄巫法：启示录（Goety: Revelation）**、**灾变（L_Ender's Cataclysm）** 与 **诡厄灾变（Goety Cataclysm）** 的 [ProjectE（等价交换重制版）](https://www.curseforge.com/minecraft/mc-mods/projecte) EMC 值配置。

## 版本信息

| 项目 | 内容 |
|------|------|
| 游戏版本 | Minecraft 1.20.1（Forge 47.4.21） |
| 诡厄巫法 | goety-2.5.57.3 |
| 启示录 | GoetyRevelation-2.3.3fix（内嵌 RevelationFix 4.4） |
| 灾变 | L_Enders_Cataclysm-3.31 |
| 诡厄灾变 | goety_cataclysm-1.20-1.9.1 |
| ProjectE | PE1.0.1 |
| 总条目 | **1,773 条** |
| Goety 本体 | 1,323 条 |
| 启示录 | 80 条 |
| 灾变 | 273 条 |
| 诡厄灾变 | 75 条 |
| 其他模组修正 | 22 条 |

## v1.2.0 更新内容

- 新增 **灾变（Cataclysm）273 条** EMC：
  - 物品、工具、武器、护甲、刷怪蛋、音乐唱片、装饰方块等。
- 新增 **诡厄灾变（Goety Cataclysm）75 条** EMC：
  - 聚晶、精华、复活素材、仆从刷怪蛋、方块物品等。
- 顶级武器按 **红物质 466,944 EMC 的 10 倍（4,669,440）** 以上配置。
- 示例：
  - 湮灭者 `the_annihilator`：18,677,760（40×）
  - 焚化者 `the_incinerator`：18,677,760（40×）
  - 灵魂撕裂者 `soul_render`：18,677,760（40×）
  - 天雷武器 `astrape / ceraunus / brontes`：9,338,880（20×）
  - 其余顶级 Boss 武器：9,338,880（20×）
  - 部分顶级护甲/饰品：4,669,440（10×）

## 文件说明

| 文件 | 说明 |
|------|------|
| `custom_emc.json` | 完整配置，包含 Goety + 启示录 + 灾变 + 诡厄灾变 + 其他修正，共 1,773 条 |
| `goety_emc_only.json` | 仅 Goety 本体条目 |
| `revelation_emc_only.json` | 仅启示录条目 |
| `cataclysm_emc_only.json` | 仅灾变条目，共 273 条 |
| `goety_cataclysm_emc_only.json` | 仅诡厄灾变条目，共 75 条 |

## 使用方法

1. 下载 `custom_emc.json`。
2. 放入：
   ```text
   .minecraft/config/ProjectE/custom_emc.json
   ```
3. 进入游戏后执行 `/projecte reload`，或重启客户端。
4. 在 Transmutation Table 中查看新增 EMC。

## 注意

- 本配置面向 ProjectE PE1.0.1。
- 顶级武器与 Boss 物品按高价值长线平衡配置。
- 如果某些价格不符合你的整合包平衡，欢迎提交 Issue。
