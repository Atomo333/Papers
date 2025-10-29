# フェイクニュース検出における時間的汎化能力に関する研究調査
(Research Survey on Temporal Generalization in Fake News Detection)

## 1. 概要 (Overview)

本リポジトリは、**フェイクニュース検出 (Fake News Detection)** の分野における**時間的汎化能力 (Temporal Generalization)** に関する論文調査とメモを管理するためのものです。

## 2. 時間的汎化能力とは (What is Temporal Generalization?)

**時間的汎化能力 (Temporal Generalization)** とは、モデルが**学習データよりも未来に公開された未知のデータ**に対して、どれだけ正しく性能を発揮できるかという能力を指します。

フェイクニュース検出の分野では、この能力が非常に重要です。なぜなら、誤情報の内容（トピック、イベント、使われる言葉）は時間と共に絶えず変化し、進化していくためです。

従来の評価方法（データをランダムに分割する）では、以下のような問題が指摘されています。

* **知識漏洩 (Knowledge Leakage)**: 訓練データとテストデータに同じトピックや関連イベントの記事が混入し、モデルが「誤情報の汎用的なパターン」ではなく「特定のイベント」を暗記してしまう。
* **性能の過大評価**: 上記の結果、既存のベンチマークスコアは高いものの、現実世界（＝未来の未知のデータ）では性能が発揮できない。

この分野の研究は、こうした時間的変化に適応し、実世界での運用（未来のニュースに対応し続けること）に耐えうる堅牢なモデルの構築と、そのための適切な評価方法（例：訓練データを過去、テストデータを未来に設定する）を確立することを目的としています。

## 3. 論文リスト (Paper List)

| タイトル (Title) | 一言コメント (Comment) |
| :--- | :--- |
| [1] TEMPORAL MISINFORMATION DETECTION： SIMPLE WAYS TO IMPROVE TEMPORAL GENERALIZATION AND BETTER EVALUATE LANGUAGE MODELS (2026) | 既存研究の時間的汎化能力に対する問題提起，データセットの作成 |
| [2] Learn over Past, Evolve for Future: Forecasting Temporal Trends for Fake News Detection (2023) | トピックの『流行り廃り』を時系列予測し、未来のフェイクニュース検出に備える実践的な研究 |
| [3] Unseen Fake News Detection Through Casual Debiasing (2025) | ドメイン依存バイアスを因果モデルを用いて解決．ニュースの真偽に関係する本質的特徴と特定のドメインに固有な特徴を分離して学習．グラフ構造を利用． |
| [4] Revisiting Fake News Detection: Towards Temporality-aware Evaluation by Leveraging Engagement Earliness | グラフベースの手法．エンゲージメントの速さに注目．遅いはノイジー，早い反応はシグナルとなる． |
| (論文のタイトル) | (ここにコメントを記述) |
| (論文のタイトル) | (ここにコメントを記述) |
| (論文のタイトル) | (ここにコメントを記述) |

