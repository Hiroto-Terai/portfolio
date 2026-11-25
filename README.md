# Portfolio — 寺井 啓人 / Hiroto Terai

Shopifyフロントエンドエンジニアの個人ポートフォリオです（静的な1ページ）。国内の制作会社と、業務委託の発注担当の方に向けています。

- **公開URL**: https://hiroto-terai.github.io/portfolio/ （英語で開くときは `?lang=en`）
- **デザイン**: 月ごとに出る小さな雑誌の1号に見立てた1ページ。紙色の地・墨・苔の緑の3色、明朝（Shippori Mincho B1）とゴシック（IBM Plex Sans JP）の2書体。表紙は縦組みの一文
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
