# 株式会社SABABA コーポレートサイト

静的HTML1ページ構成。ビルド不要。

## ファイル
- `index.html`: ページ本体
- `style.css`: スタイル
- `favicon.svg` / `robots.txt`

## ローカル表示
`index.html`をブラウザで直接開く。
```bash
open sababa-corp/index.html
```

## 更新方法
- **会社概要5項目**: `index.html`の `dl.company-info` 内を編集
- **店舗情報**: `index.html`の `ul.stores` 内の `li.store-card` を編集。Googleマップリンクは住所をURLエンコードして `https://www.google.com/maps/search/?api=1&query=...` に埋め込む

## 公開（GitHub Pages）
`Settings` → `Pages` → `Branch: master`, `Folder: /sababa-corp` を選択。
