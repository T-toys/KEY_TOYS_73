# KEY_TOYS_73 ファームウェア

## キーマップ
104キーボードからFキー・テンキー他を取って、row-staggeredから格子配列風に無理やり変更し、<br>
隙間に余ったキーを入れ込んだレイアウトです。<br>
左下の2キーには特に使い道がなくてスペースを割り当ててます。<br>
2つ目のレイヤーの数字キー位置にFキーを割り当てています。

<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/key_toys_73-keylayout.png">

## ファームウェアを書き込む

[QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases) を用意します。<br>
[key_toys_73_via.hex](https://github.com/T-toys/qmk_firmware-key_toys) を用意します。<br>
（Download ZIPでファイルをダウンロードして[key_toys_73_via.hex]を用意してください）

<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc1.png">

QMK Toolboxでファームウェアを書き込みます。PCとプロマイクロをUSBケーブルで接続します。
1. Local file に key_toys_73_via.hex を指定します。(画像ではkey_toys_73_default.hexになっています)
1. Microcontroller は atmega32u4 を指定します。
1. Auto-Flash のチェックボックスに☑をします。<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc7.png"><br>
1. キーボードのリセットスイッチを押して書き込みます。<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc5.png"><br><br>
**このような表示が出れば書き込み完了です('ω')**
<br>
***
<br>
<br>
***

## ≪キーマップの変更≫

[Remap](https://remap-keys.app/) というブラウザ上で簡単にキーマップが変更できるようになりました。(key_toys_73_via.hexを書き込んでいる場合)<br>
1. PCとプロマイクロをUSBケーブルで接続します。<br>
1. Google Chrome 及び Microsoft Edge で[Remap](https://remap-keys.app/) へアクセスします。<br>
1. START REMAP FOR YOUR KEYBOARD　をクリックします。<br>
1. <img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/scre1.png"><br>
1. +KEYBOARD　をクリックします。<img width="700" alt="" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/scre2.png"><br>
1. KEY_TOYS_73 を選択して「接続」をクリックします。<br>　
1. キーボードが表示されたら　


