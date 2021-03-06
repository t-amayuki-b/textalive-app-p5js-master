# TextAlive App API p5.js example

TextAlive App API のサンプルコードで、 [p5.js](https://p5js.org/) を使った作例です。

デモページ: https://textalivejp.github.io/textalive-app-p5js/

TextAlive ホストと接続された状態をテストするには [TextAlive App Debugger](https://developer.textalive.jp/app/run/?ta_app_url=https%3A%2F%2Ft-amayuki-b.github.io%2Ftextalive-app-p5js-master%2F&ta_song_url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DXSLhsjepelI) のページにアクセスしてください。

![sample](screenshots/p5js-10fps-640.gif)

## 違う楽曲で試すには

TextAlive App API で開発されたWebアプリケーションは、（特定の楽曲向けに作り込んでいない限り）URLのクエリパラメタで `ta_song_url={楽曲のURL}` を指定すると異なる楽曲で演出を試せます。

- [愛されなくても君がいる by ピノキオピー feat. 初音ミク](https://t-amayuki-b.github.io/textalive-app-p5js-master/?ta_song_url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DygY2qObZv24)
- [ブレス・ユア・ブレス by 和田たけあき feat. 初音ミク](https://t-amayuki-b.github.io/textalive-app-p5js-master/?ta_song_url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3Da-Nf3QUFkOU)
- [YY by 23.exe feat. 初音ミク](https://t-amayuki-b.github.io/textalive-app-p5js-master/?ta_song_url=https%3A%2F%2Fwww.nicovideo.jp%2Fwatch%2Fsm35791694)

## 開発

[Node.js](https://nodejs.org/) をインストールしている環境で以下のコマンドを実行すると、開発用サーバが起動します。

```sh
npm install
npm run dev
```

## ビルド

以下のコマンドで `docs` 以下にビルド済みファイルが生成されます。 [サンプルコードのデモページ](https://t-amayuki-b.github.io/textalive-app-p5js-master/) は [GitHub Pages](https://pages.github.com/) で、このリポジトリの `docs` 以下のファイルが提供されています。

```sh
npm run build
```

## TextAlive App API

![TextAlive](https://i.gyazo.com/thumb/1000/5301e6f642d255c5cfff98e049b6d1f3-png.png)

TextAlive App API は、音楽に合わせてタイミングよく歌詞が動くWebアプリケーション（リリックアプリ）を開発できるJavaScript用のライブラリです。

TextAlive App API について詳しくはWebサイト [TextAlive for Developers](https://developer.textalive.jp/) をご覧ください。

---
https://github.com/TextAliveJp/textalive-app-p5js
