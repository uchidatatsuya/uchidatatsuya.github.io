# 使い方
## 概要
舞台芸術の構成表をwebブラウザ上で制作するアプリケーションのプロトタイプ。
アイコンを動かし、全員がぶつからずに移動できるかシュミレートできる。

## 起動方法
node app.jsコマンドで、localhost:3000からの受付を始めます。

## 操作方法
![実行画像1](https://ecls.info.kindai.ac.jp:8443/gitbucket/1810370225/open-campas/blob/master/img/open.png?raw=true)
操作できる箇所は上部の題名、中央のキャンバス、下部のボタンです。右のグリーン部分には、アイコンのプロパティ(名前等)を設定するUIを設置予定です。

キャンバス内のアイコンはそれぞれドラッグして動かせます。
クリックしたアイコンには枠が表示され、右下の四角をドラッグするとサイズの変更ができます。
また、範囲選択が可能であり、複数のアイコンを同時に動かすことができます。
表示されるアイコンは8つまでです。

以下、各ボタンの説明。
- 青追加：青いアイコンを追加する。
- 赤追加：赤いアイコンを追加する。
- JSON：キャンバスの情報をJSONデータとしてアラート表示される。
- 削除：アイコンを選択した状態で押す。選択したアイコンを削除する。
- アニメーション：全アイコンがランダムに移動する。

## 追加予定機能
レイヤー(アイコンの座標を保存するもの)を任意で追加する
レイヤーの保存情報に沿ってアイコンを移動させる
アイコンごとに名前などの情報を持たせる
