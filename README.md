# Podium

![rspec](https://github.com/mochiz/podium-api/workflows/rspec/badge.svg)

## 必要なもの

* 必須
   * Ruby 2.6.5
   * PostgreSQL 9.5
* 任意
   * AWSアカウント

## セットアップ

```
$ git clone git@github.com:mochiz/podium-api.git
$ cd podium-api
```

## 環境変数について

.env に記述する

### direnv のインストール

TODO: 後で書く

### dotenv-rails

TODO: 後で書く

## ローカルでの起動

```
$ bin/rails s
```

サーバーへのアクセスは、ブラウザで[http://localhost:3000/](http://localhost:3000/)にアクセスしてください。

## テスト

セットアップ

    $ bin/rails db:test:prepare

テストの実行。

    $ bin/rspec

## デプロイ

TODO: 後で書く
