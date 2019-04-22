#  書籍「はじめてのディープラーニング -Pythonで学ぶニューラルネットワークとバックプロパゲーション- (Machine Learning)」

## 章構成と、そこで学習すべきポイント

### 1章　ディープラーニングとは

* 「人工知能」「機械学習」「ディープラーニング」の関係性・位置付け
* ニューラルネットワークについて
* ディープラーニングの歴史

### 2章　Python の概要

* python に慣れる
* Jupyter Notebook を使う
  * numpy、matplotlib に慣れる

### 3章　ディープラーニングに必要な数学

* シグマ（Σ）、自然対数（log）、ネイピア数（e）
* 行列（スカラー、ベクトル、テンソル）
* 微分、偏微分、全微分
* 正規分布

### 4章　ニューラルネットワーク

* 神経細胞ネットワークについて
* 神経細胞のモデル化（入力・出力、重み、バイアス、活性化関数）
  * （このあたりの説明は、別書籍「ゼロから作るDeep Learning ―Pythonで学ぶディープラーニングの理論と実装」の方が、ひょっとしたら詳しいのかも）
* 回帰問題、分類問題
* 活性化関数（シグモイド関数、ReLU、ソフトマックス関数）
* ニューラルネットワークの実装（回帰、分類）

### 5章　バックプロパゲーション

* この章の内容はしっかりと把握しておきたいところ
* バックプロパゲーションとは
  * 順伝播、逆伝播
* one-hot 表現
* 損失関数（二乗和誤差、交差エントロピー誤差）
* 勾配降下法
  * 勾配降下法の最適化アルゴリズム
* バッチサイズ（エポック、バッチ、バッチ学習、オンライン学習、ミニバッチ学習）
* バックプロパゲーションの実装（回帰の場合、分類の場合）
* この章では数式が多数登場するものの、これを Python のコードでプログラム化することで、その数式の意味するところをイメージしやすくなると思われる。
  * 具体的には、 https://www.sbcr.jp/support/14734.html から取得できるサンプルコードの中の、5-9 章、5-10 章 用のサンプルコードを読み解き、その挙動を確認することで、よりイメージがしやすくなるだろう。

### 6章　ディープラーニングの実装

* ・・・

### 7章　畳み込みニューラルネットワーク（CNN）

* ・・・

### 8章　ディープラーニングの関連技術

* ・・・