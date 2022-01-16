# Babylon.js WebAR Sample App

## About

技術書典 12 で頒布した本のサンプルプロジェクト。
豆腐のシーンを WebAR で動かして Azure にデプロイするまでをやっています。

## Tested Environment

- Node.js v14
- yarn
- Vite 2
- TypeScript
- Babylon.js 5.0.0-beta.4
- Windows 10 Home(開発機)
- Pixel 4a 5G(デバッグ機)

## Install

手元で試す場合、openssl コマンドを使って SSL/TLS 証明書を作成してください。
Windows の場合、WSL を使うと実行できます。

```sh
openssl req -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem
```

Common Name?という質問で、`https://<ローカルIP>:3000`と回答します。

そしたら`yarn dev`コマンドで dev サーバを起動します。

## Contact

何かございましたら[にー兄さんの Twitter](https://twitter.com/ninisan_drumath)までお願いいたします。
