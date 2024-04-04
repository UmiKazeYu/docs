# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

Mintlifyスターターキットをコピーするには、`Use this template`をクリックしてください。スターターキットには以下の例が含まれています

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development（開発）

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

[Mintlify CLI](https://www.npmjs.com/package/mintlify)をインストールして、ドキュメントの変更をローカルでプレビューしてください。インストールするには、以下のコマンドを使用します。

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

ドキュメントのルート（mint.jsonがある場所）で以下のコマンドを実行してください。

```
mintlify dev
```

### Publishing Changes（変更の公開）

Install our Github App to autopropagate changes from youre repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

Github App をインストールして、あなたのリポジトリからデプロイメントに変更を自動転送してください。デフォルトのブランチにプッシュした後、変更は自動的に本番環境にデプロイされます。ダッシュボードにインストール用のリンクがあります。

#### Troubleshooting（トラブルシューティング）

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Mintlify dev is not running - `mintlify install` を実行してください。
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`
- Page loads as a 404 - `mint.json` があるフォルダで実行されていることを確認してください。
