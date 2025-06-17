# タイタニック号のML予測

このプロジェクトは、Kaggleの入門コンペティション「Titanic - Machine Learning from Disaster」に参加して、
機械学習を用いて乗客の生存を予測するものです。

## 使用データ

- Kaggle提供のTitanicデータセット（`train.csv`, `test.csv`）
- 説明変数：Pclass, Sex, Age, SibSp, Parch, Fare, Embarked, FamilySize など

## 使用した手法

- EDA（探索的データ分析）による可視化
- 欠損値の処理、特徴量エンジニアリング（家族人数など）
- ロジスティック回帰、ランダムフォレスト、XGBoost による予測モデルの構築

## 成果

- 最終的なKaggleスコア：0.77990（ランダムフォレストによるモデル）
- 初期モデルと比較して精度向上を確認

## ファイル構成

| ファイル名 | 内容 |
|------------|------|
| `Titanic_EDA_テンプレート.ipynb` | 分析およびモデル構築のNotebook |
| `submission.csv` | 提出用ファイル（任意） |
| `README.md` | このファイル |

## 今後の展望

- クロスバリデーションによる精度検証の導入
- より高度な特徴量エンジニアリングの実装
- StreamlitなどでWebアプリ化の検討
