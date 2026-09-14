# solegeo.github.io

合同会社Solegeoの公式サイトです。GitHub Pagesで `https://solegeo.github.io/` として公開されます。

## 構成

- `index.html`: サイト本体（1ファイルのSPA構成。ヘッダーのナビゲーションで各ページ内容をJavaScriptにより切り替える）
- `assets/img/`: ロゴ・チーム画像などの静的アセット

## ローカルで確認する方法

Node.jsがあれば、リポジトリ直下で以下を実行してください。

```bash
npx serve .
```

またはPythonがあれば

```bash
python -m http.server 8000
```

を実行し、ブラウザで `http://localhost:8000`（`serve`の場合は表示されたポート）を開いてください。

`index.html` を直接ブラウザで開くだけでも表示は確認できますが、相対パスの検証も兼ねて簡易サーバー経由での確認を推奨します。

## 現在の状態

初期実装段階です。詳細な要件・未確定事項は `Solegeo/solegeo-ai-workspace` リポジトリの `docs/WEBSITE_SPEC.md` を参照してください。
