# TypeScript

**Typed JavaScript at Any Scale.**

## 今、もっとも学ぶべき言語は?

- JavaScriptは、求人が多い
- TypeScriptは、需要が伸び勢いがあり、単価も高い

## 言語の特徴

    - JavaScriptの上位互換
    - 型の定義により、JavaScriptより安全で堅牢なコードが可能
    - Object指向を採用しており、Javaからの移行がしやすい
    - asyc/awaitにより、非同期IOが実装しやすい
    - 型推論により、堅牢で有馬がら記述量が少ない
    - 高度なType Guardにより、安全なDuck Typingを実現
    - Object指向より、簡潔で柔軟で堅牢なプログラミングが可能

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

## コマンドライン

    Node.js, Denoで、コマンドラインのツールを作成できる

- データ分析
- 業務効率化, 自動化
- Webスクレイピング

## サーバ、クラウド

    Node.js, Denoで

### C10K問題 と Stop The World

    Apacheでは、メモリ不足によるC10K問題が起きた
    Nginxは、非同期IOにより　C10K問題を解決

    Javaもメモリ不足によって Stop The World が引き起こされていた
    Node.jsは、非同期IOによりメモリ不足が起きにくく、Javaより高いスループットを実現

## サーバーレス

    AWS lambda, GCP Function, ...

## エッジコンピューティング

    lambda edge, deno deploy, ...

## IoT (ARM)

    node.js, WebAssembly

## AI, 機械学習

### Version

- PythonのTensorFlowは、Ver2.6
- JavaScriptのTennsorFlow.jsは、Ver3.8

### JavaScriptの利点

    WebRTCを利用することで、ブラウであっても、カメラやマイクから動画や音声を取得できる
    今のスマートフォンには、高性能なGPUやニューラルエンジンが搭載されている
    よって、データをサーバに送ることなく、スマートフォンで処理できる

    上記理由により、JavaScript版が優先的に開発されている

## Native Application

    iPhone, Android, Windows, Mac, Linux

- React Native
- Ionic
- Electron

## WebAssemply

    高速なnativeのコードをbrowserで実行させる技術
    このSandboxを利用し、軽量コンテナとして、コマンドラインやサーバーレスで利用されるようになった
    AssemblyScriptでコンパイルすることで、TypeScriptでWebAssemblyを作成できる
