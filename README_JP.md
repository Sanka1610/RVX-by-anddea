[Back/戻る](https://github.com/Sanka1610/RVX-by-anddea)


# RVX by anddea

anddea氏のパッチを基にした、パッチ済みのYouTube・YouTube MusicのAPKとモジュールを提供しています。

ビルドは[GitHub Actions](https://github.com/Sanka1610/RVX-by-anddea/actions/workflows/build.yml)によって自動生成されています。


## サポート対象

  - ### 共通

      - アーキテクチャ : arm64-v8a

      - Rootマネージャー : Magisk系列、KernelSU系列、APatch系列

  - ### アプリ

    - #### YouTube

      - バージョン : 安定版、最新版

        - ※ 最新版は、YouTubeがプリインストールされている端末向けに提供しています。不安定な場合があるため使用にはご注意ください。

    - #### YouTube Music

      - バージョン : 安定版


## ダウンロード

最新のリリースは[こちら](https://github.com/Sanka1610/RVX-by-anddea/releases/)から入手できます。

モジュールかパッチ済みAPKを選択して使用してください。


## 使用上の注意

### Root環境

- Zygisk、またはその代替によって動作します。

- Zygisk Assistantを利用する場合は、Youtube、Youtube MusicにSU権限を与える必要があります。

- PlayStoreによる自動更新を無効化するために、[zygisk-detach](https://github.com/j-hc/zygisk-detach)の利用を推奨します。

### 非Root環境

- [MicroG/GmsCore](https://github.com/microg/GmsCore)、またはその代替によって動作します。

- 元のYoutubeアプリとは別のアプリとしてインストールされます。

- zygisk-detachは非ルートでは使用できないため、Playストアからの自動更新を手動で無効にしてください。


## クレジット

### [**j-hc**](https://github.com/j-hc)

  - [revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)

### [**anddea**](https://github.com/anddea)

  - [ReVanced Patches](https://github.com/anddea/revanced-patches)



