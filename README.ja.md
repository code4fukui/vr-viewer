# vr-viewer

360度写真をドロップするとぐるぐる見渡せます

シンプルなクライアントサイドの360°写真ビューアです。ブラウザにJPEGファイルをドラッグ＆ドロップするだけで、A-Frameを利用した没入感のあるVRシーンで閲覧できます。

## デモ

- **[ライブデモ](https://code4fukui.github.io/vr-viewer/)**

## 機能

- **ドラッグ＆ドロップ:** ローカルマシンから360°のJPEG画像を即座に読み込みます。
- **VR対応:** デスクトップやVRヘッドセットで没入感のある表示を実現するため、A-Frameで構築されています。
- **ミニマルなUI:** ビューアは「Drop 360deg JPG File here」というシンプルな指示から始まり、画像をドロップするとその画像に置き換わります。
- **クライアントサイド処理:** すべてのファイル処理はブラウザ内で行われます。データがアップロードされることはありません。

## 使い方

1.  [ライブデモ](https://code4fukui.github.io/vr-viewer/)を開きます。
2.  コンピュータから360°JPEGファイル（`.jpg`拡張子）をブラウザウィンドウにドラッグ＆ドロップします。
3.  シーンが即座に更新され、`<a-sky>`の背景として画像が表示されます。

## コアライブラリ

- [A-Frame](https://aframe.io/) (v1.2.0): バーチャルリアリティ体験を構築するためのWebフレームワーク。
- [waitDropFiles.js](https://js.sabae.cc/waitDropFiles.js): ファイルのドロップイベントを処理するユーティリティ。
- [readAsDataURLAsync.js](https://js.sabae.cc/readAsDataURLAsync.js): ローカルファイルをData URLとして読み込むためのユーティリティ。

## ライセンス

MIT License
