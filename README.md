# tiny handy works

tiny-handy-works.com のトップページ。プレーンなHTML/CSSのみで、ビルド不要（GitHub Pagesの「Deploy from a branch」でそのまま公開する）。

## 構成

- `index.html` — トップページ（ツール一覧）
- `privacy.html` / `about.html` / `contact.html` — 共通の必須ページ
- `style.css` — 共通スタイル
- `CNAME` — カスタムドメイン設定（GitHub Pages用。中身は `tiny-handy-works.com`）

## ローカルで確認する

```
python3 -m http.server 8000
```

その後 http://localhost:8000/ を開く。

## 新しいツールを追加するとき

`index.html` の `.tool-list` に、同じ形式でカードを1つ追加する。
