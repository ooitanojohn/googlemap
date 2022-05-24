# google map API 入門
- google-doc[https://developers.google.com/maps/documentation/javascript/examples/map-geolocation]
- googlemap-sample[https://github.com/googlemaps/js-samples]
- websocket ws:localhost:port 原因分からん[https://docs.brekeke.jp/uc/troubleshooting-wss-connection]
  - npx y-websocket
  - [socket通信のport指定先](https://qiita.com/tomopict/items/2c321374e917cc679efb)
  - ws API
  - [怪しいファイル](node_modules/vite/src/client/client.ts)
  - [その2](node_modules/vite/dist/client/client.mjs)

## index.html
- HTML5宣言[index.html]

## style.css
- ブラウザによっては後方互換モードで読み込む為、body,html,mapタグに指定が必要

# Maps JavaScript API を読み込み
- 静的読み込み<script></script>
  - async 非同期で実行
- [動的読み込み](./map.ts)
- [package](./loader.ts)
  - よく分からん

## 地図のオプション
- すべての地図には、center と zoom の 2 つの必須オプションがあります。
