# 福島県内のCoderDojoを紹介するWEBサイト
福島県内のCoderDojoを紹介するWEBサイト

## このサイトの目的

- ネイキッドドメインの維持

# 更新方法

`dist/` 配下のHTMLを修正し、push してください。GitHub Actions によって自動的にサイトに反映されます。

# ToDo

- メンテナンスの簡略化
  - Dojoが増えたり、ロゴが変更になったりした場合にメンテナンスが面倒なので、いずれは [coderdojo.jp](https://coderdojo.jp/) から定期的にスクレイピングして自動更新させるか、DojoデータをJSONファイルで管理するなど、メンテナンスを簡略化したい。

- 各Dojoが持つWEBサイト・SNSのアグリゲーション
  - RSS, API で引っ張ってくる
