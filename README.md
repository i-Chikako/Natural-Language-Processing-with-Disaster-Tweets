# Natural-Language-Processing-with-Disaster-Tweets　- Kaggleコンペティション

このリポジトリは、Kaggleの「Natural-Language-Processing-with-Disaster-Tweets」分類コンペティションに取り組んだ内容をまとめたものです。
(https://www.kaggle.com/competitions/nlp-getting-started)

## 🏆 結果
- 最終順位：966チーム中 235位　上位25％（リーダーボード、2025年5月24日時点）
- 使用モデル：スタッキング（ベースモデル：LGBMClassifier + XGBoost　メタモデル：RandomForestClassifier）
- 評価指標：F1スコア
- 最終スコア：0.82776

## 📄 概要
ツイートが本当の災害についてのものか、そうでないかを予測する分類問題に取り組みました。

## 💻 開発環境
- Python 3.12.3
- Jupyter Notebook
- scikit-learn 1.6.1
- XGBoost 3.0.0
- lightgbm 4.6.0
- pandas 2.2.2
- numpy  1.26.4

## 🔍 アプローチ
- 特徴量エンジニアリング（特徴量の作成、テキストの処理）
- OOF予測、スタッキングモデル学習

## 📁 ファイル構成
- `NLP_tweets.ipynb`: 整理された最終モデル

## 📝 補足
このコンペティションでは、NLP分類問題の実践・特徴量エンジニアリング・スタッキングの練習として非常に有意義でした。
今回、スタッキングすることにより予測精度が上がることを学びました。
今後ほかのモデルや特徴量エンジニアリングの方法についての知識を増やしていきたいと思います。
