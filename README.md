はじめに
-------------------------------------------------------------
FloatWindow は動的にフロートウィンドウを生成するライブラリです.

機能
-------------------------------------------------------------
FloatWindow には以下の機能を設けています.

1. 表示 /　非表示の切り替え
2. 幅 / 高さを設定
3. 背景色の設定
4. 表示したフロートウィンドウのドラッグ＆ドロップ

使い方
-------------------------------------------------------------
sample.html をご参照ください.

API
-------------------------------------------------------------
## v0.0.4
現在、次のAPIを提供しています.

### setWidth(width)
* フロートウィンドウの幅を設定する.

### setHeight(height)
* フロートウィンドウの高さを設定する.

### setBgColor(header_bg, contents_bg, footer_bg)
* フロートウィンドウのヘッダ、コンテンツ、フッタの各背景色を設定する.

### show()
* フロートウィンドウを表示する.

### hide()
* フロートウィンドウを非表示にする.

### isDraggable(is_drag)
* フロートウィンドウに対してDrag & DropのON/OFFを設定する.
 * ON(is_drag == true)の場合, フロートウィンドウの移動ができる
 * OFF(is_drag == false)の場合, フロートウィンドウの移動ができない

### isRestrictMoveRange(is_restrict)
* フロートウィンドウの移動範囲に対する制限のON/OFFを設定する.
 * ON(is_restrict == true)の場合, ブラウザの領域から外れてフロートウィンドウが隠れないよう制限する
 * OFF(is_restrict == false)の場合, ブラウザの領域内から外れてフロートウィンドウが隠れても移動できる
