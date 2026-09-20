# Goety + Revelation + Cataclysm + TACZ EMC Values for ProjectE

Minecraft 1.20.1（Forge 47.4.21）的 ProjectE 自定义 EMC 配置，包含：

- 诡厄巫法（Goety）
- 诡厄巫法：启示录（Goety: Revelation）
- 灾变（L_Ender's Cataclysm）
- 诡厄灾变（Goety Cataclysm）
- 永恒枪械工坊：零（TACZ）

## 版本信息

| 项目 | 内容 |
|------|------|
| 游戏版本 | Minecraft 1.20.1（Forge 47.4.21） |
| ProjectE | PE1.0.1 |
| 总条目 | **1,955 条** |
| Goety 本体 | 1,323 条 |
| 启示录 | 80 条 |
| 灾变 | 273 条 |
| 诡厄灾变 | 75 条 |
| TACZ | 191 条 |
| 其他模组修正 | 13 条 |

## v1.3.0 更新内容

- 新增 **TACZ 191 条 EMC**：
  - 全部 **24 种子弹 EMC=1**
  - 54 把枪械，统一 1000 EMC
  - 99 个配件，统一 256 EMC
  - 工作台、靶子、雕像、弹药箱等功能物品
  - 同时保留基础物品条目，作为 NBT 回退
- 顶级 MOD 物品（启示录、灾变）保持原有高价值档位。

## 文件说明

| 文件 | 说明 |
|------|------|
| `custom_emc.json` | 完整配置，共 1,955 条 |
| `goety_emc_only.json` | 仅 Goety 本体条目 |
| `revelation_emc_only.json` | 仅启示录条目 |
| `cataclysm_emc_only.json` | 仅灾变条目 |
| `goety_cataclysm_emc_only.json` | 仅诡厄灾变条目 |
| `tacz_emc_only.json` | 仅 TACZ 条目，共 191 条 |

## 使用方法

1. 下载 `custom_emc.json`。
2. 放入：
   ```text
   .minecraft/config/ProjectE/custom_emc.json
   ```
3. 执行 `/projecte reload` 或重启游戏。

## 注意

- ProjectE PE1.0.1。
- TACZ 的枪械/子弹使用 NBT 区分，已按常见默认 NBT 添加。
- 如果发现某些枪械在其他 NBT 状态下仍无 EMC，可以继续补充对应 NBT 变体。
