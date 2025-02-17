# 🚢 Titanic Survival Prediction - Kaggle Competition 🏆

## 📖 專案介紹
本專案參與了 **Kaggle 鐵達尼號生存預測競賽**，最終排名 **Top 8%（1194 / 16264）**，最佳預測準確率達 **0.79425**。
<img width="668" alt="image" src="https://github.com/user-attachments/assets/b4eacea3-325e-4cbe-80d2-112fb731940b"><br><br>

### 📊 競賽目標
- 預測乘客是否能夠在鐵達尼號沉船事故中生還。
- 根據提供的乘客資訊（性別、年齡、票價、艙等等）來建構分類模型。

---

## 🚀 **使用技術**
本專案運用了 **多種機器學習模型** 來進行預測，並透過 **VotingClassifier** 提升準確度：
- 🔹 **Logistic Regression**
- 🌲 **Random Forest**
- 🔥 **Gradient Boosting**
- 💡 **Support Vector Classifier (SVC)**
- 🔍 **K-Nearest Neighbors (KNN)**
- 🎯 **VotingClassifier**（集成學習）
- 📈 **GridSearchCV**（超參數調整）

---

## 📦 **環境與依賴**
請確保你的環境具備以下軟體：
- Python 3.9.8
- Jupyter Notebook / Google Colab
- 主要使用的 Python 函式庫：
  ```bash
  pip install pandas numpy scikit-learn seaborn matplotlib
