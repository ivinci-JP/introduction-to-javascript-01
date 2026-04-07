# javascript-introduction-basic
外部向け勉強会 JS入門

## セットアップ

1. NodeJS 24をインストール
2. 依存パッケージをインストール
    ```bash
    npm install
    ```

## プレビューサーバ起動

1. 起動
```bash
npm run honkit:serve
```
2. ブラウザで http://localhost:4000 を開く

## デプロイ方法

1. `main`ブランチにコードをマージ
2. GitHub Actionsによって自動デプロイされる
3. デプロイされた内容を確認 https://ivinci-jp.github.io/javascript-introduction-basic/
