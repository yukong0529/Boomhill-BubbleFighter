<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/brand/replay-logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/brand/replay-logo-light.png">
  <img alt="REPLAY" src="assets/brand/replay-logo-light.png" width="240">
</picture>

# 버블파이터 (BubbleFighter)

물총으로 겨루는 PC 온라인 3인칭 슈팅 게임

> **경고: Lab Track 참가 승인을 받은 창작자만 이용할 수 있습니다.** 승인받지 않은 사내 제작, 학습, 연구, 개인 공부, 상업 등 목적과 관계없이 모든 이용을 제한합니다.

> 이용 조건은 저장소 루트의 [LICENSE](LICENSE) 와 [NOTICE](NOTICE) 를 따릅니다. 뷰어: [이 게임을 뷰어로 보기](https://nexon-replay.github.io/Boomhill/#/g/bubblefighter). 세계관과 다른 게임은 [허브](https://nexon-replay.github.io/Boomhill/)에 있습니다.

## 폴더

| 폴더 | 내용 |
|---|---|
| `2d/` | 2D 그림: 묶음마다 폴더 하나, 그림은 PNG(여러 프레임이면 스프라이트 시트)와 아틀라스 JSON |
| `3d/` | 3D 미리보기 모델: 분류마다 폴더 하나. `<id>.glb` 모델, `<id>.webp` 썸네일, `<id>.json` 부가 정보 |
| `3d/_shared/` | 여러 모델이 나눠 쓰는 텍스처, 표정 그림, 조립 파츠(이름은 원래 이름_짧은 해시) |
| `2d/manifest.json`, `3d/manifest.json` | 파일마다 크기와 SHA-256 |

## 2D 그림

| 묶음 | 제목 | 그림 | 프레임 |
|---|---|---:|---:|
| `010_ui` | UI | 2,300 | 6,024 |
| `020_ingame` | 인게임 HUD, 조준, 아이템 | 1,795 | 2,968 |
| `030_shop` | 상점, 아이템 아이콘 | 2,516 | 3,776 |
| `040_map` | 맵 미리보기, 미니맵 | 429 | 430 |
| | 합계 | 7,040 | 13,198 |

## 3D 미리보기 모델

브라우저에서 바로 보는 미리보기입니다(압축 GLB, 텍스처 긴 변 512px, 캐릭터는 기본 동작만). 게임 제작, 편집에는 아래 원본 zip 을 쓰세요.

| 폴더 | 분류 | 모델 |
|---|---|---:|
| `3d/010_character/` | 캐릭터 | 164 |
| `3d/020_weapon/` | 무기 | 976 |
| `3d/030_item/` | 장비, 아이템 | 431 |
| `3d/040_npc/` | NPC, 몬스터 | 11 |
| `3d/050_prop/` | 기타 오브젝트 | 17 |
| `3d/060_map/` | 맵 | 130 |
| `3d/070_scene/` | 연출 장면 | 21 |
| | 합계 | 1,750 |

## 3D 원본 zip

압축하지 않은 GLB, 원래 해상도 PNG 텍스처, 전체 동작을 분류마다 묶었습니다. 저장소의 Releases 에서 받습니다.

| 분류 | 파일 | 크기 | 모델 |
|---|---|---:|---:|
| 캐릭터 | [bubblefighter-3d-character.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-character.zip) | 172.3MB | 164 |
| 장비, 아이템 | [bubblefighter-3d-item.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-item.zip) | 13.3MB | 431 |
| 맵 | [bubblefighter-3d-map.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-map.zip) | 396.8MB | 130 |
| NPC, 몬스터 | [bubblefighter-3d-npc.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-npc.zip) | 2.0MB | 11 |
| 기타 오브젝트 | [bubblefighter-3d-prop.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-prop.zip) | 1.6MB | 17 |
| 연출 장면 | [bubblefighter-3d-scene.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-scene.zip) | 52.4MB | 21 |
| 무기 | [bubblefighter-3d-weapon.zip](https://github.com/NEXON-REPLAY/Boomhill-BubbleFighter/releases/download/3d-originals-v1/bubblefighter-3d-weapon.zip) | 57.6MB | 976 |

형식은 [허브 저장소의 docs/format.md](https://github.com/NEXON-REPLAY/Boomhill/blob/main/docs/format.md), 쓰는 법은 [자료 안내](https://nexon-replay.github.io/Boomhill/guide.html)에 있습니다.
