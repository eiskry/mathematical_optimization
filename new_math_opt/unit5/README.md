# 5 巡回路問題
## 5.1 巡回セールスマン問題
全ての点をちょうど一回ずつ経由する巡回路で、枝上の距離の合計を最小にするもの
無向グラフ：対称巡回セールスマン問題
有向グラフ：非対称巡回セールスマン問題

### 5.1.1 部分巡回路除去定式化
制約
- 次数制約
- 部分巡回路除去制約
- カットセット制約　(部分巡回路除去製薬と同じ強さ)

カットセット制約の数は机上に多いので、制約を必要に応じて切除平面法が必要になる

分離問題：問題の制約の一部だけを用いた線形緩和問題の会に対して、その解が被っている制約を見つける問題
ネットワークフロー

切除平面法
- 妥当不等式:最適解を覗かない不等式
- 切除平面：妥当不等式の中で、線形緩和問題の会をのぞくもの

### 5.1.2 ポテンシャル定式化
Miller-Tucker-Zemlinによる多項式オーダーの本数の制約を持つ定式化
部分巡回路除去制約を用いた定式化を非対称に拡張したものと比べるとはるかに弱い
持ち上げと呼ばれる操作を行おうことによって定式化を強化する


### 5.1.3 単一品種フロー定式化
### 5.1.4 多品種フロー定式化

## 5.2 時間枠付き循環セールスマン問題
## 5.3 容量制約付き配送計画問題