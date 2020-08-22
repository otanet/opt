# opt(mathematical optimization: 数理最適化)
This repo deals with Mathematical optimization, Operations Research(OR) 

# Requirements
pulp
numpy
# pulpのインストール  # https://pypi.org/project/PuLP/
pip install -U pulp # Linux
pip3 install -U pulp  # macOS

1. 線形最適化とは
  数理最適化に対し、以下の条件が付帯しているものを線形最適化と言う。
  変数は、連続変数のみ使えます。連続変数とは、実数値を取る変数です。
  目的関数と制約条件の関数は、線形の式（一次式）のみ使えます。一次式とは、一次の変数だけ利用できる式です。
  参考：線型計画法の表現・言い回しについて、線型計画法は、線形計画法の古い言い方です。最近では、線形計画法は線形最適化と言い換えるようになっています。//

2.数理最適化（最適化）とは、数理モデルを用いる手法である。数理モデル（モデル）は、変数と目的関数と制約条件から構成されている。数式を使って表現することから、数理と言う。
- 変数：意思決定の対象。
- 目的関数：評価するための関数。最大化か最小化を選べます。
- 制約条件：満たすべき条件。 

※　「ORを探せ！－暮らしに溶け込むOR －」
http://www.orsj.or.jp/members/poster.pdf
