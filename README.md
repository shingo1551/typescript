# TypeScript

**Typed JavaScript at Any Scale.**

## 今、もっとも学ぶべき言語は?

- JavaScript は、求人が多い
- TypeScript は、需要が伸び勢いがあり、単価も高い

## 言語の特徴

- JavaScript の上位互換
- 型の定義により、JavaScript より安全で堅牢なコードが可能
- Object 指向を採用しており、Java からの移行がしやすい
- asyc/await により、非同期 IO が実装しやすい
- 型推論により、堅牢で有馬がら記述量が少ない
- 高度な Type Guard により、安全な Duck Typing を実現
- Object 指向より、簡潔で柔軟で堅牢なプログラミングが可能

## どこで使用できるか？

    TypeScriptはJavaScriptにトランスパイルされるため、あらゆるプラットフォームで使用できる

- ブラウザ
- コマンドライン
- サーバ, クラウド
- サーバーレス
- エッジコンピューティング
- IoT
- AI, 機械学習
- Native Application

## ブラウザ

    WebApplication
    Angularだけでなく, React, Vue, Svelteなどでの利用が進んでいる

### SPA, PWA

    ブラウザでありながら、Desk Top AppのようなUX

- [Angular](https://angular.io)
- [React](https://reactjs.org)
- [Vue.js](https://vuejs.org)

### Micro Frontend (Web Component)

- [stencil](https://stenciljs.com)

## コマンドライン

    Node.js, Denoで、コマンドラインのツールを作成できる

- データ分析
- 業務効率化, 自動化
- Web スクレイピング

## サーバ、クラウド

    Node.js, Denoで

### Framework

- [Fastify](https://www.fastify.io/)
- [Prisma](https://www.prisma.io/)
- [Fresh](https://fresh.deno.dev/)

### C10K 問題 と Stop The World

    Apacheでは、メモリ不足によるC10K問題が起きた
    Nginxは、非同期IOにより　C10K問題を解決

    Javaもメモリ不足によって Stop The World が引き起こされていた
    Node.jsは、非同期IOによりメモリ不足が起きにくく、Javaより高いスループットを実現

## サーバーレス

    AWS lambda, GCP Function, ...

## エッジコンピューティング

    Lambda@Edge(Amazon CloudFront Functions), deno deploy, ...

## IoT (ARM)

    node.js, WebAssembly

## AI, 機械学習

### Version

    Versionの差は拡大中

- Python の TensorFlow は、Ver2.7
- JavaScript の TennsorFlow.js は、Ver3.15

### JavaScript の利点

    WebRTCを利用することで、ブラウザであっても、カメラやマイクから動画や音声を取得できる
    今のスマートフォンには、高性能なGPUやニューラルエンジンが搭載されている
    よって、データをサーバに送ることなく、スマートフォンで処理できる

    上記理由により、JavaScript版が優先的に開発されている

## Native Application

    iPhone, Android, Windows, Mac, Linux

- React Native
- Ionic
- Electron

## 2D, 3D, Game

- [PixiJS](https://pixijs.com/)
- [three.js](https://threejs.org/)
- [babylon.js](https://www.babylonjs.com/)

## WebAssemply

    高速なnativeのコードをbrowserで実行させる技術
    このSandboxを利用し、軽量コンテナとして、コマンドラインやサーバーレスで利用されるようになった
    AssemblyScriptでコンパイルすることで、TypeScriptでWebAssemblyを作成できる

## 注目の DB サービス

    AWS, GCP, Azureなどで管理されている

- [MongoDB Atlas](https://www.mongodb.com/atlas)
- [supabase](https://supabase.com/)
- [ArangoDB](https://www.arangodb.com/)
