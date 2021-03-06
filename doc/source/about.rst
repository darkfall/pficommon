=================
pficommonについて
=================

これは何か？
============

これはPreferred Infrastructure (以下PFI)で開発された
C++の汎用ライブラリである。

これには以下のものが含まれる。

* Boostおよびtr1に含まれる十分有用であると確認された準標準的ライブラリの内、特に利用の推進が望まれるもの。利用することによりC++のコードの質が飛躍的に改善されると思われるもの、の再実装。

* 利用しやすいネットワークライブラリ

* 利用しやすいスレッドライブラリ

* データ構造及びアルゴリズムの実装

* http、msgpack-rpcなどのネットワークプロトコルのサポート

* html、json、csvなど、テキストフォーマットのサポート

主として、C++でネットワークサーバを書く際に便利なものが揃っている。

なぜBoostの再実装が含まれるのか
===============================

このライブラリはBoostと共に使われることを想定していない。というのも、ソフトウェアのインストールとメンテナンスを用意にするために、ソフトウェアパッケージにBoostを同梱したくないという動機が先にあるからである。また、C++0xおよび新しめのコンパイラが利用できない環境も想定している。それ故に、tr1やBoostに含まれるいくつかのライブラリの再実装が含まれている。

ライセンス
==========

本ライブラリは `New BSD License <http://www.opensource.org/licenses/bsd-license.php>`_ に基づき頒布される。
