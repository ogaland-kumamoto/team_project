# チーム開発における開発環境の統一


## 概念図
![](./images/develop_image.svg)

## 以下の観点で統一を図る
* Visual Studio Codeのワークスペース設定
* 拡張機能
* 拡張機能の設定

## 前提
* 下記がインストール済みである事
    * [Visual Studio Code](https://azure.microsoft.com/ja-jp/products/visual-studio-code/)
    * [Node.js](https://nodejs.org/ja/)（推奨版）

## テンプレートプロジェクトの構築手順
1. 拡張機能の導入
2. ワークスペース設定
3. node.jsによる導入

# 拡張機能と設定


* [prettier](https://prettier.io/)
  * .prettierrc.json
  * .prettierignore

## 要検討
* [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)：Visual Studio Codeの設定
   * .editorconfig