# 薬理クイズ｜GitHub Pages 公開手順

## ファイル
- `index.html` ← これ1ファイルをアップロードするだけでOK

---

## GitHub Pages で公開する手順

### 1. GitHubアカウント作成
https://github.com にアクセスして無料アカウントを作成

### 2. リポジトリを作成
- 右上の「+」→「New repository」
- Repository name: `pharma-quiz`（任意）
- Public を選択
- 「Create repository」をクリック

### 3. index.html をアップロード
- 「uploading an existing file」をクリック
- `index.html` をドラッグ＆ドロップ
- 「Commit changes」をクリック

### 4. GitHub Pages を有効化
- 「Settings」タブ → 左メニュー「Pages」
- Source: 「Deploy from a branch」
- Branch: `main` / `(root)` を選択
- 「Save」をクリック

### 5. URLにアクセス
数分後に以下のURLで公開される：
```
https://あなたのユーザー名.github.io/pharma-quiz/
```

---

## スマホでの使い方
1. 上記URLをSafari/Chromeで開く
2. 「共有」→「ホーム画面に追加」でアプリアイコンとして登録可能

## 問題を追加・修正したい場合
`index.html` 内の `quizData` 配列に項目を追加してGitHubに再アップロードする
