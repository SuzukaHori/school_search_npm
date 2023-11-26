# Gakkou search

ターミナル上で、日本の学校を検索することができる npm です。

[![Image from Gyazo](https://i.gyazo.com/1a9531424d3b0ec8e319edd9985895ee.gif)](https://gyazo.com/1a9531424d3b0ec8e319edd9985895ee)

## 準備

このツールの使用には「学校コード検索 API」への登録が必要です。以下の手順に従って登録を行ってください。

1. 「学校コード検索 API」のウェブサイトにアクセスします。https://api.edu-data.jp/
1. 利用登録を完了し、アカウントを作成します。「学校コード検索 API」の利用規約を確認し、同意する必要があります。
1. ログイン後、「トークンの一覧」ページから「トークンの生成」を行ってください。

## 使用方法

### 1. API トークンの設定

API トークンは環境変数に設定する必要があります。以下のコマンドを実行してトークンを設定してください。

```
export API_TOKEN='あなたのAPIトークン'
```

### 2. インストール

以下のコマンドで gakkou-search をグローバルにインストールします。

```
npm install -g gakkou-search
```

### 3. gakkou-search コマンドを実行

コマンドを実行して学校の検索を開始します。

```
gakkou-search
```

検索条件を指定するプロンプトが表示されますので、それに従って情報を入力してください。

※検索にマッチした学校の件数が**100件を超えた場合、初めの100件のみ表示**します。

<br>
<br>

# Gakkou search

This is npm, which allows you to search for Japanese schools on the terminal.

## Preparation

To use this npm, you need to register with the "学校コード検索 API". Please follow the steps below to register.

1. Access the "学校コード検索 API" website. https://api.edu-data.jp/
1. Complete your registration and create an account. You must review and agree to the terms of use for the "学校コード検索 API".
1. After logging in, please "Generate a token" from the "Token list" page.

## how to use

### 1. API token settings

The API token must be set in an environment variable. Please run the following command to set the token.

````
export API_TOKEN='Your API token'
````
### 2. Installation

Install gakkou-search globally with the following command.

````
npm install -g gakkou-search
````

### 3. Execute gakkou-search command

Run the command to start searching for schools.

````
gakkou-search
````

You will be prompted to specify your search criteria, so enter the information accordingly.

*If the number of schools matching your search exceeds **100, only the first 100 will be displayed**.