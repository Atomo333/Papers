# CTDGに関する調査

## Title List

1. Temporally evolving graph neural network for fake news detection (2021)
2. Temporal graph networks for deep learning on dynamic graphs (2020)
3. Inductive Representation Learning on Temporal Graphs (2020)
4. 
5. 
6. 
7. 
8. 
9. 
10. 
11. 
12. 
13. 
14. 
15. 
16. 
17. 
18. 
19. 
20. 

---

## Paper Information
### 1. Temporally evolving graph neural network for fake news detection (2021)
[[Paper]](https://www.sciencedirect.com/science/article/pii/S0306457321001965)
[[Code]]()
[[bibtex]]()
<details><summary>summary</summary><div>
  
CTDGを用いたフェイクニュース検出の代表的研究．時間的に変化するグラフを使用して，ソーシャルメディア上のフェイクニュースを検出する手法を提案している．手法名TGNF．バックボーンとしてTGN[2]を利用．さらに敵対的学習を利用したTDN（時間差分ネットワーク）を設計．TDNはコサイン類似度で隣接する時間軸のグラフ特徴量の差を大きくする損失．メモリモジュールを使っているのでTGATではなくTGNと考えるのが妥当．

- 著者: "Chenguang Song / Kai Shu / Bin Wu"
- 出版年: 2021
- 出版元: Elsevier
- インパクト: CTDGの導入および精度向上

- Keywords : `Fake News Detection`, `CTDG`, `Graph Neural Network`, `Temporal Graph`
- 関連論文: `-`
- 引用数: `182`
- 実装検証: `未`


</div></details> 

<details><summary>abstract</summary><div>
ソーシャルメディアにおけるフェイクニュースの拡散は，世論や社会の発展に好ましくない影響をもたらす可能性があります．近年，効果的な検出および介入アルゴリズムを開発するために多くの努力が払われてきました．既存の拡散モデルに基づくフェイクニュース検出手法のほとんどは，【静的ネットワーク】に着目しており，学習アルゴリズムを実行する前に情報拡散ネットワークの全構造がアクセス可能であることを前提としています．しかし，現実世界の情報拡散ネットワークでは，新しいノードやエッジが絶えず出現します．そこで本論文では，構造，内容のセマンティクス，そして時間的情報を融合できる，新たな時間的拡散に基づくフェイクニュース検出のフレームワークを提案します．特に，我々のモデルは，連続時間動的拡散ネットワークの設定下でグラフが進化していくものとして，現実世界のニュースが持つ【時間的進化】のパターンをモデル化することができます．我々は大規模な実世界のデータセットを用いて広範な実験を行い，その実験結果は，提案モデルが最先端のフェイクニュース検出手法よりも優れた性能を発揮することを示しています．
</div></details> 

### 2. Temporal graph networks for deep learning on dynamic graphs (2020)
[[Paper]](https://arxiv.org/abs/2006.10637)
[[Code]](https://github.com/twitter-research/tgn/tree/master)
[[bibtex]]()
<details><summary>summary</summary><div>
TGNの提案．TGAT[3]がベースになっている?TGNFのバックボーンはこれ．論文の内容にしっかり目を通して要確認．TGATにメモリモジュールを追加したものがTGN．


- 著者: "E. Rossi et al."
- 出版年: 2020
- 出版元: ICML2020
- インパクト: TGNFのバックボーン

- Keywords : `CTDG`, `Temporal Graph`, `Dynamic Graph`
- 関連論文: `Inductive Representation Learning on Temporal Graphs`
- 引用数: `963`
- 実装検証: `進行中`


</div></details> 

<details><summary>abstract</summary><div>
グラフニューラルネットワーク（GNN）は、生物学や素粒子物理学からソーシャルネットワーク、推薦システムに至るまで、幅広い問題で生じる関係性や相互作用の複雑なシステムを学習できる能力を持つことから、近年ますます人気が高まっています。グラフ上の深層学習モデルは多数存在しますが、何らかの動的な性質（例：時間とともに変化する特徴や接続性）を持つグラフを扱うためのアプローチは、これまでにほとんど提案されてきませんでした。

本稿では、「テンポラルグラフネットワーク（TGN）」を提案します。これは、時間情報付きイベントのシーケンスとして表現される動的グラフに対する深層学習のための、汎用的かつ効率的なフレームワークです。TGNは、メモリモジュールとグラフベースの演算子という新たな組み合わせにより、既存のアプローチの性能を大幅に上回りつつ、同時により高い計算効率を実現します。

さらに、動的グラフで学習を行ういくつかの既存モデルが、我々のフレームワークの特殊なインスタンスとして位置づけられることも示します。我々は、本フレームワークの様々な構成要素について詳細なアブレーションスタディ（除去実験）を行い、動的グラフにおける複数の変換的（transductive）および帰納的（inductive）な予測タスクにおいて、最先端の性能を達成する最適な構成を考案しました。
</div></details>

### 3. Inductive Representation Learning on Temporal Graphs (2020)
[[Paper]](https://openreview.net/pdf?id=rJeW1yHYwH)
[[Code]](https://github.com/StatsDLMathsRecomSys/Inductive-representation-learning-on-temporal-graphs)
[[bibtex]]()
<details><summary>summary</summary><div>
TGATの提案．


- 著者: "Da Xu et al."
- 出版年: 2020
- 出版元: ICLR2020
- インパクト: TGNsのベースとなったモデル?

- Keywords : `CTDG`, `Temporal Graph`, `Dynamic Graph`
- 関連論文: ``
- 引用数: `817`
- 実装検証: `未`


</div></details> 

<details><summary>abstract</summary><div>

</div></details>

### 4. Predicting Dynamic Embedding Trajectory in Temporal Interaction Networks (2019)
[[Paper]](https://dl.acm.org/doi/abs/10.1145/3292500.3330895)
[[Code]]()
[[bibtex]]()
<details><summary>summary</summary><div>
  
JODIE．トレーニングを9倍高速化するt-Batchアルゴリズムを開発．

- 著者: "S. Kumar"
- 出版年: 2019
- 出版元: SIGKDD2019
- インパクト: CTDGの処理機構として代表的．

- Keywords : `CTDG`, `Temporal Graph`, `Dynamic Graph`
- 関連論文: `関連する論文へのリンクや名称`
- 引用数: `928`
- 実装検証: `一部（TGNにベースラインとして用意されている）`


</div></details> 

<details><summary>abstract</summary><div>

## ユーザーとアイテムのシーケンシャルなインタラクションモデリングにおけるJODIEの提案
eコマース、ソーシャルネットワーキング、教育といった領域では、ユーザーとアイテム（商品）間のシーケンシャルなインタラクションをモデリングすることが非常に重要です。表現学習は、ユーザーとアイテムの動的な進化をモデリングする魅力的な機会を提供します。この手法では、各ユーザーやアイテムをユークリッド空間に埋め込み、その進化をこの空間内の埋め込み軌跡としてモデル化できます。しかし、既存の動的埋め込み手法は、ユーザーがアクションを起こしたときにのみ埋め込みを生成し、埋め込み空間におけるユーザーやアイテムの将来の軌跡を明示的にモデル化していません。

本稿では、ユーザーとアイテムの埋め込み軌跡を学習する結合型リカレントニューラルネットワークモデル「(JODIE)」を提案します。(JODIE)は、インタラクションごとにユーザーとアイテムの埋め込みを更新するために、2つのリカレントニューラルネットワークを採用しています。([特筆すべき点としては])、(JODIE)はユーザーやアイテムの将来の埋め込み軌跡もモデル化します。この目的のために、(JODIE)は将来の任意の時点でのユーザーの埋め込みを推定することを学習する新しい射影演算子を導入しています。これらの推定された埋め込みは、将来のユーザーとアイテムのインタラクションを予測するために使用されます。

### スケーラビリティと実験結果
この手法のスケーラビリティを確保するため、我々は時間的に一貫性のあるバッチを作成し、トレーニングを9倍高速化する(t-Batchアルゴリズム)を開発しました。

(JODIE)を検証するために、4つの実世界データセットを用いて、将来のインタラクション予測と状態変化予測という2つの予測タスクで6つの実験を行いました。(JODIE)は、これらのタスクにおいて、将来のインタラクション予測で少なくとも20%、状態変化予測で12%以上、6つの最先端アルゴリズムを上回るパフォーマンスを示すことができました。
</div></details>

### 5. Each Fake News Is Fake in Its Own Way: An Attribution Multi-Granularity Benchmark for Multimodal Fake News Detection (2025)
[[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/31999)
[[Code]]()
[[bibtex]]()
<details><summary>summary</summary><div>
  
最新のフェイクニュース検出モデル．トップカンファレンスであるAAAI2025に採択されているので目を通す．
フェイクニュースのパターン分析．真実のニュースは互いに類似しているのに対し，フェイクニュースはそれぞれ特徴があることを指摘．それらを類型化し，マルチタスク分類を行う．

- 著者: "Hao Gao et al."
- 出版年: 2025
- 出版元: AAAI2025
- インパクト: AAAI2025に採択

- Keywords : `Fake News Detection`
- 関連論文: `https://aaai.org/proceeding/aaai-39-2025/` AAAI2025の論文リスト
- 引用数: ``
- 実装検証: `未`


</div></details> 

<details><summary>abstract</summary><div>

偽ニュース検出におけるマルチグラニュラリティの重要性
ソーシャルプラットフォームは情報へのアクセスを容易にする一方で，偽ニュースで溢れかえり，その結果として((負の影響 (negative consequences)))をもたらしています。このような状況において，((マルチモーダル偽ニュースの自動検出 (automatic multimodal fake news detection)))は，((追求する価値のある課題 (a worthwhile pursuit)))です。

既存のマルチモーダル偽ニュースデータセットは，真実か偽りかという((二値のラベル (binary labels)))しか提供していません。しかしながら，真実のニュースは互いに類似しているのに対し，偽ニュースはそれぞれ((独自の方法で (in its own way)))偽りであるという特徴があります。これらのデータセットでは，様々なタイプのマルチモーダル偽ニュースが持つ((混合された性質 (mixed nature)))を十分に反映できていません。

この((ギャップを埋める (bridge the gap)))ために，私たちは((属性付けされたマルチグラニュラリティマルチモーダル偽ニュース検出データセット (attributing multi-granularity multimodal fake news detection dataset)))である((AMG))を構築し，((内在する偽パターン (inherent fake pattern)))を明らかにしました。さらに，マルチモーダル偽ニュースの検出と属性付けを行うために，((マルチグラニュラリティ手掛かりアライメントモデル (multi-granularity clue alignment model)))である((MGCA))を提案します。実験結果は，AMGが((挑戦的なデータセット (challenging dataset)))であり，その((属性付け設定 (attribution setting)))が((将来の研究に新たな道 (new avenues for future research)))を開くことを示しています。

</div></details>


---

## テンプレート（新規論文追加用）
### X. 論文タイトル (出版年)
[[Paper]](論文リンク)
[[Code]](コードリポジトリリンク)
[[bibtex]](引用用bibtexリンクまたは内容)
<details><summary>summary</summary><div>
  
ここに論文の簡潔な概要を記入します．主な貢献，手法，結果などを簡潔に説明します．

- 著者: "主著者名 / 共著者名1 / 共著者名2 ..."
- 出版年: YYYY
- 出版元: ジャーナル/会議名
- インパクト: 重要な貢献，新しい手法，結果や評価指標

- Keywords : `キーワード1`, `キーワード2`, `キーワード3`
- 関連論文: `関連する論文へのリンクや名称`
- 引用数: `Google Scholarなどでの引用数`
- 実装検証: `実施済/未/一部`


</div></details> 

<details><summary>abstract</summary><div>
ここに論文のアブストラクトや詳細な要約を記入します．元の論文のアブストラクトを翻訳したものや，重要なポイントを強調したり，【重要な概念】などをハイライトしたりすることで，後で参照する際に役立ちます．

アブストラクトでは以下のポイントを含めることが推奨されます：
1. 研究の背景と問題設定
2. 既存手法の課題
3. 提案手法の新規性
4. 実験結果と評価
5. 研究の意義や将来の展望
</div></details>

