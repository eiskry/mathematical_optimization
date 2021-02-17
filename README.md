# Mathematical Optimization
Pythonによる数理最適化 

## 実験内容
最適化問題とは 与えられた条件下において最も良いものを選び出す問題であり、 数理最適化問題とは最適化問題を数学的に記述した問題である。 つまり、目的関数とその定義域を数学的に記述し、 目的関数の最大値/最小値を求める問題のことである。< 本実験テーマでは、 汎用的な数理モデルの１つである整数計画問題を中心に 数理最適化問題についての実験を行う。
　より具体的には、以下の内容を扱う。
 
### 1. 最適化数理モデル：問題定式化と最適化ソルバーの利用
#### 目標
様々な問題に対してその問題定式化の方法を学び、 最適化ソルバーを用いることによってそれらの問題を解くこと ができるようになる。

#### 実験内容
- 最適化ソルバー（Python + Gurobi / CPLEX etc.）を使って整数計画問題を解く。（cf. テキスト [1], [2]）
- 様々な定式化手法を習得し、解きたい問題を適切な数理モデルに定式化できるようにする。（cf. テキスト [2]）
- パズルを整数計画問題として定式化し、GurobiやCPLEXなどの整数計画ソルバーを用いて計算機実験を行う。（レポート課題１）

#### テキスト
[1] 「 データ分析ライブラリーを用いた最適化モデルの作り方 」 斉藤努（著） （近代科学社） 2018年 
[2] 「 あたらしい数理最適化　Python言語とGurobiで解く 」 久保幹雄・J.P.ペドロソ・村松正和・A.レイス（著） （近代科学社） 2012年 

#### レポート課題1
パズルの定式化とそれに関する計算機実験

### 1. 最適化アルゴリズムの基礎：線形計画・分枝限定法・整数計画
#### 目標
汎用的な最適化数理モデルである整数計画問題に対する最適化アルゴリズムについて 理解する。

#### 実験内容
- 線形計画問題およびその解法（単体法）について理解し、実装する。（cf. テキスト [3] 第2章）
- ナップサック問題に対する分枝限定法を理解し、実装する。（cf. テキスト [3] 第3章）
- 0-1整数計画問題ソルバーを作成する。（レポート課題２）

#### テキスト
[3] 「 Pythonによる数理最適化入門 」 久保幹雄（監修）／並木誠（著） （朝倉書店） 2018年

#### レポート課題2
0-1整数計画ソルバーの作成と計算機実験
（問題例の解が出力されるかどうかの確認、 あと問題サイズを変えたときの計算時間比較も行う。）

### 1. 最適化理論の応用
#### レポート課題3
自分の興味がある数理最適化に関するトピックに関して、 詳しく調べ、理論の理解、アルゴリズムの実装、計算機実験 を行い結果をまとめよ。

## 使用ライブラリー

- Jupyter
- PuLP
- pandas
- Numpy
- NetworkX
- matplotlib
- more-itertools
- pillow
- ortoolpy
- dual
- japanmap
- gurobi
