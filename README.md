## ポモドーロタイマー

Tailwind CSS を使ったシンプルなポモドーロタイマーです。横向きでもタイマーの円は真円を維持し、アイコンは時計（⏱）に変更済みです。

### 使い方
- ブラウザで `index.html` または `pomodoro.html` を開きます。
- ▶️/⏸️ で開始・一時停止、🔄 でリセット。
- 作業/休憩の切替ボタンでモードを変更。

### GitHub Pages（自動デプロイ）
このリポジトリは GitHub Actions で `main` ブランチから GitHub Pages に自動デプロイされます。

初回のみ、以下の”1回だけの設定”が必要です：

1. GitHub のリポジトリ画面 → `Settings` → `Pages`
2. `Build and deployment` → `Source` を `GitHub Actions` に変更（保存）

以後は push するだけで公開が更新されます。公開 URL：

- https://shoei05.github.io/pomodoro/

### ローカル開発
特別なビルドは不要です。VS Code の Live Server 等で開くだけでOKです。

### ライセンス
特に指定がなければ、必要に応じて追記してください。
