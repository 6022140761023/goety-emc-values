# ProjectE EMC Values Pack

Minecraft 1.20.1（Forge 47.4.21）ProjectE 自定义 EMC 配置，包含：

- 诡厄巫法（Goety）
- 诡厄巫法：启示录（Goety: Revelation）
- 灾变（L_Ender's Cataclysm）
- 诡厄灾变（Goety Cataclysm）
- 永恒枪械工坊：零（TACZ）
- 暮色森林（Twilight Forest）
- 夸克（Quark）
- 车万女仆（Touhou Little Maid）

## 版本信息

| 模块 | 条目数 |
|---|---:|
| Goety 本体 | 1323 |
| 启示录 | 80 |
| 灾变 | 273 |
| 诡厄灾变 | 75 |
| TACZ | 191 |
| 暮色森林 | 511 |
| 夸克 | 838 |
| 车万女仆 | 74 |
| 其他修正 | 10 |
| **总计** | **3375** |

## v1.5.0 更新内容

- 新增 **夸克 Quark 838 条 EMC**。
- 新增 **车万女仆 Touhou Little Maid 74 条 EMC**。
- 两者数值整体贴近原版，偏亲民：
  - 夸克原木/木头 32
  - 夸克木板 8
  - 夸克台阶 4
  - 夸克楼梯/栅栏/墙 8
  - 夸克机器/功能物品 128–8192
  - 车万女仆背包 1024–4096
  - 车万女仆功能物品 128–4096
  - 隐藏技术物品 EMC=1

## 文件说明

| 文件 | 说明 |
|------|------|
| `custom_emc.json` | 全部模块完整配置，共 3375 条 |
| `goety_emc_only.json` | 仅 Goety |
| `revelation_emc_only.json` | 仅启示录 |
| `cataclysm_emc_only.json` | 仅灾变 |
| `goety_cataclysm_emc_only.json` | 仅诡厄灾变 |
| `tacz_emc_only.json` | 仅 TACZ |
| `twilightforest_emc_only.json` | 仅暮色森林 |
| `quark_emc_only.json` | 仅夸克 |
| `touhou_little_maid_emc_only.json` | 仅车万女仆 |

## 使用

将 `custom_emc.json` 放入：

```text
.minecraft/config/ProjectE/custom_emc.json
```

执行 `/projecte reload` 或重启游戏。
