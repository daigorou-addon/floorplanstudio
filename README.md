# FloorPlanStudio（間取り図スタジオ）

部屋・家具・ドア・窓を置いて、間取り図をかんたんに作れる Windows 用ソフトです。
作った間取りは、ボタン1つで **立体パース風の「アニメ風」** にもできます。

> Web版「間取り図メーカー」は [Daigorou-Tools](https://daigorou-addon.github.io/daigorou-tools/) にあります。
> このソフト版は、アニメ風モード・ファイル保存・細かい設定などを追加した版です。

## 特長

### 3つの表示モード
| モード | 内容 |
|---|---|
| シンプル | 部屋と壁だけの、すっきりした平面図 |
| 詳細 | 家具・設備・ドア・窓まで描き込んだ平面図 |
| アニメ風 | 壁に高さがあり、床の素材（フローリング・畳・タイル・芝など）と家具の絵が付いた、立体パース風の絵 |

シンプルや詳細で作ったあと、モードを切り替えるだけでアニメ風になります。

### 作る
- 部屋（リビング・和室・寝室・水回りなど）、庭・駐車場・テラスなどの外構
- 家具・設備（ソファ、ベッド、キッチン、浴槽、車、木、花壇、階段 など）
- ドア・窓（種類の切り替えに対応）
- 複数階（階ごとにタブで切り替え）
- 元に戻す / やり直し、拡大・縮小、移動

### 細かい設定
- 家具: 色味・明るさ・個別の名前
- 部屋: 名前・面積の表示を隠す
- 全体: 壁の太さ、面積の表示（帖 / ㎡のみ / なし）、文字サイズ
- 家具にマウスを乗せると名前を表示

### 保存・出力
- 間取りを `.floorplan` ファイルに保存・読み込み（Web版の JSON も開けます）
- PNG 画像として保存
- 印刷
- 編集内容は自動保存されます

### その他
- 日本語 / English / 한국어 / 简体中文 / 繁體中文 / Español
- 起動時に GitHub の最新版を確認し、新しい版があれば知らせます（自動ダウンロードはしません）

## 動作環境
- Windows 10 / 11（64bit）

## インストール
[Releases](https://github.com/daigorou-addon/FloorPlanStudio/releases) から `FloorPlanStudio Setup x.x.x.exe` をダウンロードして実行してください。

## 主な操作
| 操作 | キー |
|---|---|
| 新規作成 | Ctrl + N |
| 開く | Ctrl + O |
| 保存 | Ctrl + S |
| 名前を付けて保存 | Ctrl + Shift + S |
| PNG で保存 | Ctrl + E |
| 印刷 | Ctrl + P |
| 元に戻す / やり直し | Ctrl + Z / Ctrl + Y |

## ライセンス・クレジット
- 同梱フォント Zen Kaku Gothic New は SIL Open Font License 1.1 です（`fonts/OFL.txt`）。
- Copyright (C) 2026 daigorou-tools. All rights reserved.

## 作者

作者の他のツール: [daigorou-Tools](https://daigorou-addon.github.io/daigorou-tools/)

## サポート
このソフトが役に立ったら、[Buy Me a Coffee](https://buymeacoffee.com/daigorou) で応援してもらえるとうれしいです。

---

# FloorPlanStudio

A Windows app for easily creating floor plans by placing rooms, furniture, doors, and windows.
With one click, your floor plan can also be turned into a 3D-perspective-style **"Anime Style"** illustration.

> The web version, "Floor Plan Maker," is available at [Daigorou-Tools](https://daigorou-addon.github.io/daigorou-tools/).
> This desktop version adds Anime Style mode, file saving, detailed settings, and more.

## Features

### Three Display Modes
| Mode | Description |
|---|---|
| Simple | A clean floor plan with just rooms and walls |
| Detailed | A floor plan that also draws in furniture, fixtures, doors, and windows |
| Anime Style | A 3D-perspective-style picture with walls that have height, floor materials (wood flooring, tatami, tile, grass, etc.), and furniture illustrations |

After building a plan in Simple or Detailed mode, just switch modes to get the Anime Style look.

### Create
- Rooms (living room, Japanese-style room, bedroom, bathroom/utility areas, etc.) and outdoor areas such as gardens, parking, and terraces
- Furniture and fixtures (sofa, bed, kitchen, bathtub, car, tree, flower bed, stairs, etc.)
- Doors and windows (multiple types selectable)
- Multiple floors (switch between floors with tabs)
- Undo / redo, zoom in / out, move

### Detailed Settings
- Furniture: tint, brightness, custom names
- Rooms: hide name and area display
- Global: wall thickness, area display (jo / ㎡ only / none), text size
- Hover over furniture to show its name

### Save & Export
- Save and load floor plans as `.floorplan` files (JSON files from the web version can also be opened)
- Save as a PNG image
- Print
- Your edits are saved automatically

### Other
- 日本語 / English / 한국어 / 简体中文 / 繁體中文 / Español
- Checks GitHub for the latest version on startup and notifies you if a newer one is available (no automatic download)

## Requirements
- Windows 10 / 11 (64bit)

## Installation
Download and run `FloorPlanStudio Setup x.x.x.exe` from [Releases](https://github.com/daigorou-addon/FloorPlanStudio/releases).

## Keyboard Shortcuts
| Action | Keys |
|---|---|
| New | Ctrl + N |
| Open | Ctrl + O |
| Save | Ctrl + S |
| Save As | Ctrl + Shift + S |
| Save as PNG | Ctrl + E |
| Print | Ctrl + P |
| Undo / Redo | Ctrl + Z / Ctrl + Y |

## License & Credits
- The bundled font Zen Kaku Gothic New is licensed under the SIL Open Font License 1.1 (`fonts/OFL.txt`).
- Copyright (C) 2026 daigorou-tools. All rights reserved.

## Author

Other tools by the author: [daigorou-Tools](https://daigorou-addon.github.io/daigorou-tools/)

## Support

If you find this software useful, I'd appreciate your support via [Buy Me a Coffee](https://buymeacoffee.com/daigorou).
