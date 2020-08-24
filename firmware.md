# KEY_TOYS_73 ファームウェア

## キーマップ
104キーボードからFキー・テンキー他を取って、row-staggeredから格子配列風に無理やり変更し、<br>
隙間に余ったキーを入れ込んだレイアウトです。<br>
左下の2キーには特に使い道がなくてスペースを割り当ててます。<br>
2つ目のレイヤーの数字キー位置にFキーを割り当てています。

<img width="700" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/key_toys_73-keylayout.png">

## ファームウェアを書き込む

[QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases) を用意します。<br>
[key_toys_73_default.hex](https://github.com/T-toys/qmk_firmware-key_toys) を用意します。<br>
（Download ZIPでファイルをダウンロードして[key_toys_73_default.hex]を用意してください）

<img width="700" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc1.png">

QMK Toolboxでファームウェアを書き込みます。PCとプロマイクロをUSBケーブルで接続します。
1. Local file に key_toys_73_default.hex を指定します。
1. Microcontroller は atmega32u4 を指定します。
1. AUto-Flash のチェックボックスに☑をします。<img width="700" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc7.png">
1. キーボードのリセットスイッチを押して書き込みます。<img width="700" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc5.png"><br>
このような表示が出れば書き込み完了です。

## キーマップとマトリックスについて

73キーをプロマイクロ1つで動かしているので、使用できるピンを全部使ています。<br>
(Duplex-Matrixを使えばよかったんですが理解できていません)<br>
9×9のマトリックスを作り、それぞれのキーに割り当てているためコードが変な感じになってます。<br>
<img width="350" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc2.png"><img width="350" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/sc3.png"><br>
<br>
キーマップを変更する際は下の図を参照し、適宜変更下さい。<br>
<img width="700" alt="代替テキスト" src="https://github.com/T-toys/KEY_TOYS_73/blob/master/image/key_toys_73-keylayout-2.png">

