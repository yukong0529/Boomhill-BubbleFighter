<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/brand/replay-logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/brand/replay-logo-light.png">
  <img alt="REPLAY" src="assets/brand/replay-logo-light.png" width="240">
</picture>

# 泡泡战士（BubbleFighter）

一款使用水枪对战的 PC 在线第三人称射击游戏。

> **警告：仅限获准参加 Lab Track 的创作者使用。** 未经批准的使用一律禁止，不因其属于内部制作、学习、研究、个人学习或商业用途而例外。

> 使用条件以仓库根目录中的 [LICENSE](LICENSE) 和 [NOTICE](NOTICE) 为准。查看器：[在查看器中浏览本游戏](https://nexon-replay.github.io/Boomhill/#/g/bubblefighter)。其他游戏请访问[资源中心](https://nexon-replay.github.io/Boomhill/)。

## 目录

| 目录 | 内容 |
|---|---|
| `2d/` | 2D 图像，按资源包分别存放；图像为 PNG，多帧图像使用精灵图集，并附有图集 JSON |
| `3d/` | 3D 预览模型，按类别分别存放；每个模型包含 `<id>.glb` 模型、`<id>.webp` 缩略图和 `<id>.json` 附加信息 |
| `3d/_shared/` | 多个模型共用的纹理、表情图和组装部件（文件名为原始名称_短哈希） |
| `2d/manifest.json`、`3d/manifest.json` | 记录每个文件的大小和 SHA-256 |

## 2D 图像

| 资源包 | 内容 | 图像数 | 帧数 |
|---|---|---:|---:|
| `010_ui` | UI | 2,300 | 6,024 |
| `020_ingame` | 游戏内 HUD、瞄准界面、道具 | 1,795 | 2,968 |
| `030_shop` | 商店、道具图标 | 2,516 | 3,776 |
| `040_map` | 地图预览、迷你地图 | 429 | 430 |
| | 合计 | 7,040 | 13,198 |

## 3D 预览模型

这些模型可直接在浏览器中预览（压缩后的 GLB、纹理最长边为 512 px，角色仅包含基础动作）。如需用于游戏制作或编辑，请使用下方的原始 ZIP 文件。

| 目录 | 类别 | 模型数 |
|---|---|---:|
| `3d/010_character/` | 角色 | 164 |
| `3d/020_weapon/` | 武器 | 976 |
| `3d/030_item/` | 装备、道具 | 431 |
| `3d/040_npc/` | NPC、怪物 | 11 |
| `3d/050_prop/` | 其他物件 | 17 |
| `3d/060_map/` | 地图 | 130 |
| `3d/070_scene/` | 演出场景 | 21 |
| | 合计 | 1,750 |

## 3D 原始 ZIP

原始文件按类别打包，包含未压缩的 GLB、原始分辨率的 PNG 纹理和完整动作。请从仓库的 Releases 下载。

| 类别 | 文件 | 大小 | 模型数 |
|---|---|---:|---:|
| 角色 | [bubblefighter-3d-character.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-character.zip) | 172.3 MB | 164 |
| 装备、道具 | [bubblefighter-3d-item.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-item.zip) | 13.3 MB | 431 |
| 地图 | [bubblefighter-3d-map.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-map.zip) | 396.8 MB | 130 |
| NPC、怪物 | [bubblefighter-3d-npc.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-npc.zip) | 2.0 MB | 11 |
| 其他物件 | [bubblefighter-3d-prop.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-prop.zip) | 1.6 MB | 17 |
| 演出场景 | [bubblefighter-3d-scene.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-scene.zip) | 52.4 MB | 21 |
| 武器 | [bubblefighter-3d-weapon.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-weapon.zip) | 57.6 MB | 976 |

文件格式见[资源中心仓库的 docs/format.md](https://github.com/NEXON-REPLAY/Boomhill/blob/main/docs/format.md)，使用方法见[资料指南](https://nexon-replay.github.io/Boomhill/guide.html)。
