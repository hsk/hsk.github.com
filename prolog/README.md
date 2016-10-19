# Prologでの型理論

ここでは、Prologを使って型理論の学習を行います。

## [hello.html](hello.html)

Prologをウェブ上で実行するための仕組みpengineを使います。

## [calc.html](calc.html)

ラムダ計算をビックステップ評価器としてPrologで書いたものです。

## [calc2.html](calc2.html)

ラムダ計算をビックステップ評価器としてシーケント計算の形式に近づけて書いたものです。論文や教科書で出てくるような数学的な式に近い形で記述しました。

## [calc3.html](calc3.html)

ラムダ計算をスモールステップ評価器として書いたインタプリタです。

## [calc4.html](calc4.html)

ラムダ計算をスモールステップ評価器としてシーケント計算で書いたものです。

## [calc5.html](calc5.html)

ラムダ計算を評価文脈と置換を使って行います。 評価文脈の穴を[]で表し、式を述語eを用いて、分解し、subst述語で置き換えます。

## [calc6.html](calc6.html)

ラムダ計算を評価文脈を使って行います。 述語eに評価文脈の穴をPrologの変数として受け取り、置換は穴変数への束縛するだけにして高速化しました。

## [dot](dot)

Dependent Object TypesをPrologで実装します。
calcのノウハウを活かして更にラムダ計算を発展させScalaの理論的な裏付けとなるDOT計算を実装します。

## [index.html](index.html)

線時相論理型言語TLLPのインタプリタです。
