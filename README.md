# plus	![test](https://github.com/Takumi-27/robosys2022/actions/workflows/test.yml/badge.svg)

* 標準入力から読み込んだ数字を足し、標準出力する。

## インストールおよび使用方法
``` 
$ git clone git@github.com:Takumi-27/robosys2022.git
$ cd robosys2022
$ seq 5 | ./plus
15
$ seq 5 | sed 's/$/.1/' | ./plus
15.5
```
* 使用環境 Ubuntu 18.04.5
* ソフトウェア Python3.7～3.10(動作確認済み)

## plusの詳細
* 標準入力から例のように数字を読み込み足すことが出来る。読み込んだ数字が整数なら整数で出力し、少数なら少数で出力する。

## ライセンス
* このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます。
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです．
      * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)

## 謝辞
* 千葉工業大学 先進工学部 未来ロボティクス学科 上田隆一研究室の皆様には心より感謝申し上げます。

© 2022 Takumi Ochiai


