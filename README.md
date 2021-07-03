#  serverless-lambda-boilerplate

これは SeverlessFramework を使って Lambda + Typscript の API をデプロイするボイラープレートです。

## 初めに

Visual Studio Code 等で `serverless-lambda-boilerplate` をご自分のプロジェクト名に置換して下さい。

## 開発環境の立ち上げ

```shell
$ git clone git@github.com:naogify/serverless-lambda-boilerplate
$ cd serverless-lambda-boilerplate
$ cp .envrc.sample .envrc
$ vim .envrc # ご自分の AWS アクセスキーとシークレットアクセスキーを貼り付けて下さい。
$ yarn
```

## API のデプロイ

```shell
$ npm run deploy:dev
```