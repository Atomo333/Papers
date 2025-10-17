# マルチモーダルフェイクニュース検出手法 調査

## 📚 参考文献
- [ScienceDirect: A systematic review of multimodal fake news detection on social media using deep learning models](https://www.sciencedirect.com/science/article/pii/S2590123025008291)

---

## 🔍 概要

### MFND (Multimodal Fake News Detection)
マルチモーダルフェイクニュース検出は、複数の情報源を組み合わせてフェイクニュースを検出する手法です。

#### モダリティの組み合わせ
- **テキスト × 視覚情報**（中心的な研究領域）
- テキスト × ビデオ
- オーディオ × ビデオ
- ユーザプロフィール × ニュースコンテンツ

---

## 🤖 使用される深層学習モデル

### 主要モデル
- **Transformer**
- **RNN** (Recurrent Neural Network)
- **CNN** (Convolutional Neural Network)

### その他のモデル
- アンサンブル手法
- **GAN** (Generative Adversarial Network)
- **AE** (Autoencoder)

---

## 📊 データセット

### テキスト × 画像の代表的データセット
| データセット名 | 説明 |
|--------------|------|
| Twitter Dataset | Twitter上のデータ |
| Weibo Dataset | Weibo（微博）上のデータ |
| Politifact Dataset | 政治関連のファクトチェックデータ |
| Gossipcop Dataset | ゴシップニュースデータ |
| Fakeddit | Reddit由来のデータ |

> **📌 注意**: 収集期間は全体的に古く、2018年までのものが多い

---

## 📈 評価指標

### 一般的な分類タスク指標
- **Accuracy** (正解率)
- **F1スコア**
- **Recall** (再現率)
- **Precision** (適合率)

### その他の評価指標
- **AUC-ROC** (ROC曲線下面積)
- 計算コスト

---

## ⚠️ 現在の課題

### 1. モダリティ間の関連性
既存のマルチモーダル手法はモダリティ間の関連性を十分に考慮していない

### 2. 多言語対応の不足
ほとんどの研究が英語を対象としており、多言語性がない

### 3. 虚偽の程度の測定
- 現在の研究のほとんどは**二項対立**のアプローチを採用
- 真実と虚偽の両方を含むニュースも存在するが、その程度を測定できない

### 4. 早期発見の重要性
フェイクニュースの拡散を食い止めるには早期の発見が不可欠

### 5. データセットの不足
マルチモーダルデータセットが不十分