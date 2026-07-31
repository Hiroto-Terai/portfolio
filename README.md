# Portfolio — Hiroto Terai

Shopifyフロントエンドエンジニアの個人ポートフォリオ（静的1ページ）。

- **デザイン**: スイス／エディトリアル（大活字グロテスク + モノスペースのラベル、モノクロ+朱赤1色、罫線と連番）
- **フォント**: Archivo / Space Mono（`assets/fonts/` に woff2 を同梱・外部依存なし）
- **技術**: 素の HTML / CSS / JS。ビルド不要。ライト／ダーク自動対応。
- **ホスティング**: GitHub Pages

## ローカル確認

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

`file://` で直接開いてもフォント・レイアウトは表示されます。

## 構成

```
index.html            1ファイル完結（CSS/JS インライン）
assets/fonts/*.woff2  Archivo(400/600/700/800) + Space Mono(400/700)
.nojekyll             GitHub Pages の Jekyll 処理を無効化
```
