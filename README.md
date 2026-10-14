# Portfolio — 寺井 啓人 / Hiroto Terai

Shopifyフロントエンドエンジニアの個人ポートフォリオです（静的な1ページ）。国内の制作会社と、業務委託の発注担当の方に向けています。

- **公開URL**: https://hiroto-terai.github.io/portfolio/ （英語で開くときは `?lang=en`）
- **デザイン**: モスグリーンの地を、線で区切ったグリッド。ヒーローに散らばった図形は、カートボタン・トグル・数量ボタンなどの小さなUI部品で、クリックすると実際に動く
- **作品の図**: スクリーンショットは使わない。各ストアをCSSで描いた小さなお店の図にしていて、画面に入ると組み上がる
- **言語**: 日本語と英語を切り替えられる。文言は `data-l="ja"` と `data-l="en"` の要素に両方持っている
- **テーマ**: ライト／ダーク。OSの設定に従い、ボタンでも切り替えられる。選んだものは localStorage に保存する
- **フォント**: Google Fonts の Bricolage Grotesque（名前・数字）と Zen Kaku Gothic New（本文）
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
.nojekyll    GitHub Pages の Jekyll 処理を無効化
```

## 載せる数字

実績の数値は、Lifelog リポジトリの `career/achievements.md`（実績・数値台帳）にあるものだけを使う。
