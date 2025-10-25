# 🍄 MycoPredict

# 🧠 Project Overview

- Predict whether a mushroom is edible 🍽️ or poisonous ☠️ using machine learning.
- This project compares Gradient Boosting 🌳 and XGBoost ⚡ classifiers to achieve high accuracy, providing insights into which features are most important for classification.

# 📂 Dataset

- Source: UCI Mushroom Dataset

- Features: 22 categorical attributes such as cap shape, cap color, odor, gill size

- Target: class (0 = edible 🍄, 1 = poisonous ☠️)

# Dataset size: 8,124 samples

# 🛠️ Implementation Steps

1️⃣ Load Dataset & Inspect – check structure, missing values, and unique categories
 
2️⃣ Label Encoding – convert categorical features into numeric values for ML models

3️⃣ Train-Test Split – 75% train, 25% test for unbiased evaluation

4️⃣ Train Models:

# Gradient Boosting Classifier 🌳

# XGBoost Classifier ⚡

5️⃣ Predictions & Evaluation:

# Accuracy ✅

- Precision, Recall, F1-Score 📊

- Confusion Matrix 🔹
  
6️⃣ Feature Importance Visualization – identify top predictors like odor, cap color, and gill size

| Metric    | Gradient Boosting 🌳 | XGBoost ⚡ |
| --------- | -------------------- | --------- |
| Accuracy  | 0.99                 | 0.99      |
| Precision | 0.99                 | 0.99      |
| Recall    | 0.99                 | 0.99      |
| F1-Score  | 0.99                 | 0.99      |

# 🔍 Key Learnings

- Ensemble methods like Gradient Boosting and XGBoost handle categorical data effectively.

- Feature importance reveals which attributes (e.g., odor, spore print color) are critical for identifying poisonous mushrooms.

- Demonstrates the full ML workflow: Data Preprocessing → Model Training → Evaluation → Interpretation.

# 📈 Visual Insights

- Confusion matrices show almost perfect classification ✅

- Feature importance plots highlight odor, gill size, and cap shape as strongest predictors

- Helps in understanding risk factors in mushrooms

    ### 👨‍💻 Author

   **Aswin Kumar D**

💌 *AI/ML Enthusiast | Deep Learning Developer*

