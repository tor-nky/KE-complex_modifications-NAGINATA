# Mac で薙刀式を使うスクリプト

### 薙刀式配列v14（集大成版） 2021年12月10日付

[【薙刀式】v14集大成版](http://oookaworks.seesaa.net/article/484704326.html#gsc.tab=0)

* docs/json/Naginata_v14-TypeB

Karabiner-Elements に登録してください。

同時連続シフトを使いたい場合は、"薙刀式v14《同時連続シフト拡張》"、"薙刀式配列v14（集大成版）" の順に登録します。

通常シフトのみでよければ、"薙刀式配列v14（集大成版）" だけを登録します。

![Karabiner-Elements画面](Karabiner設定.png)

そして "キーボード"環境設定 で、英語の「U.S.」、その他の言語の「Unicode 16進数入力」を登録します。

![キーボード環境設定](キーボード環境設定.png)

## 特徴

* JISキーボードにもUSキーボードにも対応しています。
* 2キー同時押しは 50ミリ秒以内に、3キー同時押しは 80ミリ秒以内に押してください。
* カーソル移動系のみリピートします。
* 左右シフトキーを押しながらだと一時的に英字入力ができます。

## 動作確認

iMac (Retina 5K, 27-inch, Late 2015)
* macOS Big Sur (11.6.1) + Karabiner-Elements (v14.3.0) + 日本語IM または かわせみ3 (3.0)

ローマ字入力を使います。

# 不具合

* 変換確定前の文字がある時に編集モードの記号をともなう入力をすると、記号が前の方に入ることがある。

# 参考

* [【薙刀式】v14集大成版](http://oookaworks.seesaa.net/article/484704326.html#gsc.tab=0)
* [Karabiner-Elementsの設定項目をまとめました](https://qiita.com/s-show/items/a1fd228b04801477729c)
* [Documentation | Karabiner-Elements](https://karabiner-elements.pqrs.org/docs/)
* [Mac薙刀式v11 sorshi版](https://github.com/sorshi/KE-complex_modifications-NAGINATA)
* [Mac 記号や特殊文字のキーボードショートカットまとめ](http://inforati.jp/apple/mac-tips-techniques/system-hints/how-to-use-special-characters-and-symbols-keyboard-shortcut-with-macos.html)
* [Mac のキーボードショートカット](https://support.apple.com/ja-jp/HT201236)
* [Mac で日本語の英字とかなの文字対応を調べる](https://support.apple.com/ja-jp/guide/japanese-input-method/jpim10277/6.2.1/mac/10.14)
* [薙刀式v13 QMK版](https://github.com/eswai/qmk_firmware/tree/master/keyboards/crkbd/keymaps/naginata_v13u)

# 補足

[Mac薙刀式v11 sorshi版](https://github.com/sorshi/KE-complex_modifications-NAGINATA) の考え方を発展させて作りました。

なお、スペースキーの定義以外の全てを jsonファイル直接編集で作成しています。

編集モード、濁点、半濁点、小書き文字の連続入力ができますが、これは [薙刀式v13 QMK版](https://github.com/eswai/qmk_firmware/tree/master/keyboards/crkbd/keymaps/naginata_v13u) のソースコードを参考にしました。

「だが」「自動」「画像」「議事堂」「磁場」などの入力が楽になります。

ほか「ので」の入力を スペース押す→J押す→スペース離す→E押す→全部離す で入力できるようにアレンジしてあります。
