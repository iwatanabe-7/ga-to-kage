# 蛾と影 — Moth & Shadow

廃旅館「月見荘」を舞台にした見下ろし型ホラーゲーム。ブラウザで動く単一の HTML ファイルです。

**Play:** https://iwatanabe-7.github.io/ga-to-kage/

- **影 (Shadow)** — 照らされている間だけ動けない
- **蛾 (Moth)** — 灯りに寄ってくる。照らすほど速い

五枚の札を集めて玄関から脱出すればクリア。日本語 / English 対応。

## 操作

| 操作 | キーボード / マウス | タッチ |
|---|---|---|
| 移動 | WASD / 矢印 | 左側をドラッグ |
| 照らす向き | マウス | 右側をタッチ |
| 灯りの点滅 | クリック / Space / F | 灯 ボタン |
| 走る | Shift | 走 ボタン |
| 一時停止 | Esc / P | — |

## ファイル

- `index.html` — ゲーム本体（依存なし。Google Fonts のみ読み込み）
- `itch-page.md` — itch.io ストアページ用の紹介文

## itch.io 用 zip の作り方

```bash
zip ga-to-kage-itch.zip index.html
```
