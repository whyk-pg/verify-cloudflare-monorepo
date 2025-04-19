# Verify Cloudflare Stack
![Status: ToDo](https://flat.badgen.net/static/Status/ToDo/red)
<!-- ![Status: In Progress](https://flat.badgen.net/static/Status/In%20Progress/yellow) -->
<!-- ![Status: Done](https://flat.badgen.net/static/Status/Done/green) -->

## 本リポジトリの目的
クライアントとサーバーをできるだけCloudflare Stackで構築してみたい

## 本リポジトリの達成目標
- [x] クライアントとサーバーをCloudflare Workersプロジェクトして初期化
- [ ] クライアントにサーバーのService Bindingsを設定
  - [ ] Service Bindings設定時のCORSを確認
- [ ] サーバーとCloudflare D1をPrismaで繋ぎ込み
- [ ] 双方をCloudflareにホスティング
- [ ] クライアントの前段にプロキシを配置してコンテンツをキャッシュする

## 参考資料
- [Hono Service bindings入門](https://zenn.dev/sui_water/articles/db763fe80216a8)
- [Service Binding | Honoを使ってCloudflare Multi Workers環境を作る](https://zenn.dev/monica/articles/feff72caee5e6b#service-binding)
- [Service bindings - Runtime APIs · Cloudflare Workers docs](https://developers.cloudflare.com/workers/runtime-apis/bindings/service-bindings/)
- [Cloudflare PagesでService Bindingsを設定するときの注意](https://zenn.dev/sushichaaaan/articles/5e6a03f29d7d3b)
- [（実践Cloudflare Workers）Service bindingsの使い方](https://zenn.dev/moutend/articles/f9409d43724da5)
