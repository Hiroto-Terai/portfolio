# Portfolio — 寺井 啓人 / Hiroto Terai

Shopifyフロントエンドエンジニアの個人ポートフォリオです（静的な1ページ）。国内の制作会社と、業務委託の発注担当の方に向けています。

- **公開URL**: https://hiroto-terai.github.io/portfolio/ （英語で開くときは `?lang=en`）
- **デザイン**: 冒頭が「売る側（段ボール色）」と「作る側（苔色）」の二つの色面。地は灰みの薄い緑、書体は Archivo と Zen Kaku Gothic New の2つ。連絡は苔色の全幅の面
- **画像は使わない**: 写真・イラスト・生成画像・スクリーンショットは入れない。作品は、触った範囲と作った本人のひとことで見せる
- **言語**: 日本語と英語を切り替えられる。文言は `data-l="ja"` と `data-l="en"` の要素に両方持っている
- **テーマ**: ライト／ダーク（ダーク表示）。OSの設定に従い、ボタンでも切り替えられる。選んだものは localStorage に保存する
- **技術**: 素の HTML / CSS / JS。ビルドは不要
- **ホスティング**: GitHub Pages

## ローカル確認

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## 構成

```
index.html   1ファイル完結（CSS/JS インライン）
cases/       事例の詳細ページ（1事例1ファイル。CSS/JS インライン）
  keboz-members-sale.html   KEBOZ：会員限定セールの入口をトップに出した事例
DESIGN.md    設計書（色・書体・レイアウト・使わないもの）
.nojekyll    GitHub Pages の Jekyll 処理を無効化
```

## 載せる数字

実績の数値は、Lifelog リポジトリの `career/achievements.md`（実績・数値台帳）にあるものだけを使う。
