# elm-project-template

Elmの実行環境をコンテナ上に作成するテンプレートです。

## 構築手順

1. Docker のインストール
2. VSCode のインストール
3. [VSCode のDevcontainer拡張機能](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) のインストール
4. devcontainer で本プロジェクトを開く
5. `npm install` を実行

## ビルド手順

1. `npm run build` を実行すると `src/Main.elm` がビルドされ、 `./output` に HTML が生成される
