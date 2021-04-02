# python_sample
Pythonのサンプルコード

# コメント

pythonではシャープ `#` で始める行がコメントとなる

# 演算子

## 算術演算
以下の演算子に対応

- 四則演算 (+-*/)
- 剰余 (%)
- べき乗 (**)
- 整数除算 (//)

## 代入

`変数名 = 値` で代入
変数名は英数字とアンダーバー(_)の組み合わせが使える。ただし数字で始めてはならない。

# 関数

## 算術

- abs: 絶対値
- round: 丸める
- min: 最小値
- max: 最大値


# import文

- モジュールを読み込む文
  - `import モジュール名` の形式
    - `モジュール名.関数名` で呼び出せるようになる

# io

入出力ストリームを扱う

## BytesIO

インメモリのバイナリストリーム

- コンストラクタ: 初期データを引き渡してバイナリストリームを作る


# requests

HTTPを扱うライブラリ
https://requests-docs-ja.readthedocs.io/en/latest/

- get: GETメソッドによるデータ取得

# Pillow(PIL fork)

画像操作を扱うライブラリ。
https://pillow.readthedocs.io/en/stable/

## Image
画像を扱うモジュール

- open: ファイルまたはファイルオブジェクトを指定して開く

# MatPlotLib
チャート表示を扱うパッケージ
https://matplotlib.org/

## pyplot

MATLAB形式のプロットを行うモジュール

- bar: バーチャートを作る
- plot: X-Yデータをプロットする
- show: プロットを画面に表示

# Numpy

数値演算を行うためのパッケージ
https://pandas.pydata.org/

## よく使う関数

### 配列生成関数
- arange: 範囲とステップを指定してndArray配列生成
- array: 引数に配列やタプルを指定してndArray配列生成
- zeros: 形状を指定して値が0のndArray配列生成
- ones: 形状を指定して値が1のndArray配列生成
- empty: 形状を指定して値が未初期化(不定)のndArray配列生成

### ndArray型のメソッドなど

- dtype: 要素の型を取得
- ndim: 次元を取得
- size: サイズ(要素数)を取得
- itemsize: 要素1個のバイト長を取得
- shape: 配列の形状(次元とサイズ)を取得
- reshape: 配列の形状を組み替える
