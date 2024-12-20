# 最初の説明

https://zenn.dev/yuma_prog/articles/vscode-extension-development-with-copilot
1-6. 拡張機能のインストール
VS Code Marketplaceに公開しなくても、先ほど生成された.vsixファイルがあればVS Codeにインストールすることができます。

VS CodeでCtrl + Shift + Pを押して、Extensions: Install from VSIX...を選択して、先ほど生成された.vsixファイルを選択します。

# ODB-WorkBenchに欲しい機能
下記のそれぞれを適切に検索して、使えるようにしたい。


ODB-Pipeline:
完成したレシピ集

ODB-Library:
レシピになる前のプロンプト集

ODB-Archive:
変換したデータ一覧
ODB-ProxyAPIもここに含まれるだろう

ODB-Lab:
新しいデータ変換

# 利用ケース
## Webを検索して必要なデータセットを作成する
1. クロールするWebのリストを作成
1. Webリストに基づいてクロールして、必要な情報を抽出し、データセットに追加
1. データセットの中の揺らぎの統一

## J-クレジット申請書を作成して複数人で整備
![J-Credit Logo](J-Credit_Logo.png)