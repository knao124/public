# public

GitHub Pages で静的 HTML を公開するための repository です。

公開 URL:

- https://knao124.github.io/public/
- https://knao124.github.io/public/jahis-prescription-qr-format-v1-11.html
- https://knao124.github.io/public/static-html-publishing-guide.html
- https://knao124.github.io/public/codex-web-tailscale-remote-access-guide.html

## 使い方

- 公開したい `HTML` / `CSS` / `JavaScript` を repository 直下に置く
- 先頭ページは `index.html` にする
- 変更を `main` に push すると GitHub Pages 側に反映される

## 補足

- `.nojekyll` を置いているので、静的ファイルをそのまま配信できます
- 現在は `Pages` の公開元として `main` の `/(root)` を使う前提です

## 公開中のページ

- `/` : repository のトップページ
- `/jahis-prescription-qr-format-v1-11.html` : JAHIS 院外処方箋2次元シンボル Ver.1.11 のCSV形式を行ごとに読む解説
- `/static-html-publishing-guide.html` : 静的 HTML を手早く公開する方法の解説
- `/codex-web-tailscale-remote-access-guide.html` : codex-web の外部アクセスと Tailscale の基本をまとめた解説
