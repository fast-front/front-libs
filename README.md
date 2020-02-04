# 利用方法

読み込み側の `package.json` で以下のように追加する.

```json
{
  "name": "my-awesome-project",
  "scripts": {},
  "dependencies": {
  "front-libs": "git+https://db1026921cb14117ecb42c94eb4ba648f4b93a83:x-oauth-basic@github.com/fast-front/front-libs"
  }
}
```

## 設定方法

初期設定

https://github.com/settings/tokens/  
gitの管理画面でトークンを発行する  
権限はリポジトリを追加する

```
{
  "dependencies": {
    "<modulename>": "git+https://<発行したトークン>:x-oauth-basic@github.com/<githubユーザ名>/<リポジトリ名>"
  }
}
```

参考
https://qiita.com/shinout/items/c6f12d69e68b312d62fa

