# 不動産収支分析 AI

物件概要書、レントロール、収支表などをアップロードして、不動産投資の収支を試算するブラウザアプリです。

## 使い方

1. `index.html` をブラウザで開きます。
2. Anthropic APIキーを入力します。
3. PDF、画像、Excel、CSVなどの資料をアップロードします。
4. AIで読み取った項目を確認し、必要に応じて修正します。

## GitHub Pages

このリポジトリは静的サイトとしてそのまま公開できます。`main` ブランチへpushすると、`.github/workflows/pages.yml` によりGitHub Pagesへデプロイされます。

## 注意

APIキーはブラウザの `localStorage` に保存されます。GitHubにはAPIキーをコミットしないでください。
